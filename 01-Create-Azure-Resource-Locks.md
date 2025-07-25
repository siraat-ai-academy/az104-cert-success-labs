## 📌 Lab Title
**Create Azure Resource Locks**

---

## 🔮 Scenario Setup

It was a bright Thursday morning in Aarhus. Mr. eks2 walked gently into the training room, his notebook full of stars, clouds, and little Danish words he was trying to learn. He was ready.

“Godmorgen, eks2!” said **Kasper Madsen**, waving with a cinnamon bun in his hand. “Ready for another cozy adventure in Azure?”

**Sofia Zaymera** smiled warmly, “Today, we’ll learn something very important: **Resource Locks**. These help protect your work from being deleted or changed by accident. It’s like adding a lock to your digital door.”

Mr. eks2 blinked thoughtfully. “Locks... in the cloud?”

“Yes,” Kasper chuckled. “Even the cloud needs a padlock sometimes.”

---

## 🛠️ Step-by-Step with Story & Dialogues

### 🌱 Task 1: Create a Virtual Machine

“Let’s start by planting a little machine in the cloud garden,” said Kasper.

1. “Go to the **Azure Portal** and click **Create a resource**,” he guided. “Now choose **Virtual Machine**.”

2. Sofia whispered, “Use an existing **Resource Group** or create a new one. Let’s name it **NordicVault-RG** — sounds secure, doesn’t it?”

3. Kasper continued, “Name the machine **NordicVault-VM**. For the rest:
   - **Availability Options**: No infrastructure redundancy
   - **Security Type**: Trusted launch
   - **Image**: Ubuntu Server 20.04 LTS Gen2
   - **Size**: Click *See all sizes*, pick **B2s**
   - **Authentication**: Use password
   - **Username**: kasperadmin
   - **Password**: StrongPassword@123”

4. “Click **Next: Disks**, and choose **Standard SSD (Locally-redundant Storage)**,” Sofia added.

5. “Then click **Review + create** and finally **Create**,” said Kasper.

Mr. eks2 nodded slowly. “So... it’s like I just built a tiny Linux robot in the cloud.”

“Exactly!” beamed Kasper. “A robot with a trusted heart.”

---

### 🔒 Task 2: Add a Delete Lock to the Virtual Machine

Kasper rubbed his hands. “Time to put a safety helmet on our little robot.”

1. “Find your **NordicVault-VM**,” he said.

2. “In the left menu, go to **Locks** under **Settings**,” Sofia pointed out.

3. “Click **Add**, and fill it like this:
   - **Lock Name**: VMDeleteLock
   - **Lock Type**: Delete
   - Then click OK.”

Mr. eks2 asked, “So if someone tries to delete the robot...”

“Azure will say nope!” smiled Kasper. “It’s protected.”

---

### 📦 Task 3: Add a Read-Only Lock to the Resource Group

“Now,” said Sofia gently, “Let’s protect the whole **Resource Group [ressourcegruppe]**.”

1. “Go to **NordicVault-RG**,” said Kasper.

2. “On the left menu, click **Locks**,” added Sofia.

3. “Now click **Add** again:
   - **Lock Name**: RGReadOnly
   - **Lock Type**: Read-only
   - Click OK.”

“So now no one can change anything inside the group?” asked Mr. eks2.

Sofia nodded. “Exactly. It's like a museum exhibit: look, but don’t touch.”

---

### 🧹 Cleanup

“We’ve learned, now let’s tidy up,” said Kasper.

“Delete all the resources,” Sofia smiled. “But remember, remove the locks first, otherwise Azure won’t let you.”

Mr. eks2 whispered, “The locks really *do* protect... like magic words.”

---

## 🌍 Real-World Reflection

In a real job, accidents can happen. A colleague might delete a **Virtual Machine** by mistake. These **Resource Locks** are gentle but strong guards that help cloud administrators keep things safe. For anyone just starting in IT or switching careers, understanding locks is like learning how to protect your first bicycle: simple, powerful, and essential.

---

## 📘 Bonus: Learn 7 Danish Tech Words

| English Term         | Danish Word            |
|----------------------|-------------------------|
| Resource Group       | Ressourcegruppe         |
| Virtual Machine      | Virtuel Maskine         |
| Storage Account      | Lagerkonto              |
| Lock                 | Lås                   |
| Read-only            | Kun læsning             |
| Delete               | Slet                    |
| Disk                 | Disk                    |

---

## 🧾 Final Summary (Character Intros)

### Muhammad Naveed Ishaque
Naveed is a content creator who believes that even shy voices can shine through writing. His work helps beginners feel confident and calm while learning hard things like cloud and Azure administration.

### Mr. eks2
Mr. eks2 was once a quiet whisper — now, he is a beginner Azure Administrator trainee in Denmark. He learns slowly, kindly, and deeply. In every task, he gently asks, “Can this be more human?” reminding everyone that even the cloud needs a heart.

### Kasper Madsen
Kasper is a warm and funny Azure Administrator. He believes that labs should be joyful, not scary. He loves guiding new learners by turning complex admin tasks into simple, human experiences. For him, the cloud isn’t just about machines — it’s about people learning with smiles.

### Sofia Zaymera
Sofia was born in Spain and brings both kindness and clarity to every Azure administration lab. Though she understands complex cloud operations, she explains them in soft, simple words — so learners feel peace, not pressure, while learning.

### Siraat AI Academy
“The Straight Path — Empowering minds with clarity, illuminating paths with purpose.”
Siraat is a creative initiative to make hard tech feel easy, especially for those new to IT, from non-tech backgrounds, or from hidden corners of the world.
Built with purpose. Built for peace.

---

✅ Signature Close

---

✍️ Created & Curated by  
**Muhammad Naveed Ishaque**  
_Content Creator | AI Writer | Narrative Simplifier_  
_With the inner voice of eks2 — the whisper behind the work._

**Siraat AI Academy**  
_“The Straight Path — Empowering minds with clarity, illuminating paths with purpose.”_
