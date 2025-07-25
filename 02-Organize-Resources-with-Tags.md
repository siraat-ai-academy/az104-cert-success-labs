
## 📌 Lab Title
**Organize Azure Resources with Tags**

---

## 🔮 Scenario Setup

A soft breeze swirled around the windows of the Azure lab in Aarhus. Mr. eks2 arrived with a flask of chamomile tea and a question in his eyes.

“Good morning, eks2,” Kasper grinned. “Today we’re learning how to use **tags**. These help you label your Azure things so you don’t get lost in the cloud.”

“Like sticky notes on boxes?” Mr. eks2 asked.

“Exactly!” said Sofia. “Just imagine you’re organizing a cozy storage room. With tags, everything has a name and a purpose.”

---

## 🛠️ Step-by-Step with Story & Dialogues

### 🌱 Task 1: Create a Virtual Machine

Kasper leaned forward. “Let’s build a new machine and give it a friendly name. How about **TagBuddy-VM**?”

1. Go to **Virtual Machines** in the **Azure Portal**.
2. Click **+ Create > Azure Virtual Machine**.
3. On the **Basics** tab, enter:
   - **Resource Group**: Create or select one like **TagCentral-RG**
   - **VM Name**: TagBuddy-VM
   - **Region**: East US
   - **Availability options**: No infrastructure redundancy
   - **Security type**: Standard
   - **Image**: Windows Server 2019 Datacenter - x64 Gen2
   - **Size**: Click *See all sizes*, choose **B1s**, click **Select**
   - **Username**: taguser
   - **Password**: StrongPassword@123
   - Leave **Azure Spot Instance** unchecked
   - Leave **Public inbound ports** as default

4. Move to **Disks**, select **Standard SSD**
5. Click **Review + Create**, then **Create**

Mr. eks2 sipped his tea. “So we just made a little Windows machine with no distractions. Simple and light.”

Sofia smiled. “And soon it will have a name tag.”

---

### 🔒 Task 2: Apply Tags to the Virtual Machine

“Let’s label our friend now,” said Kasper.

1. Go to **Resource Groups** in the portal.
2. Open **TagCentral-RG**.
3. Click the **TagBuddy-VM**.
4. In the left panel, select **Tags** under **Settings**.
5. Add a tag:
   - **Name**: Department
   - **Value**: IT
6. Click **Apply**.

“So this tells Azure, 'Hey, this machine is for the IT team',” Kasper explained.

Mr. eks2 asked, “Can we tag it with more things? Like... 'Testing', or 'Production'?”

Sofia nodded, “Yes, and that’s the beauty of tags. You can organize things your way.”

---

### 📝 Task 3: Filter Resources by Tag

“Now let’s use those tags to find what we need,” said Kasper.

1. Go to **Resource Groups**.
2. Open **TagCentral-RG**.
3. Click **Add filters** in the toolbar.
4. Select the tag **Department**, choose the value **IT**
5. Click **Apply**

“See?” Sofia said gently. “Only the resources with that tag appear. It's like whispering to Azure, 'Show me the IT things.'”

Mr. eks2 giggled. “Azure has good ears.”

---

### 🧹 Cleanup

Kasper stretched. “Nice tagging work, eks2. Now let’s clean the cloud.”

“Delete all the resources,” Sofia guided. “A tidy cloud is a happy cloud.”

Mr. eks2 whispered, “And a tagged cloud is a smart one.”

---

## 🌍 Real-World Reflection

In real IT work, Azure grows fast. Suddenly, you have hundreds of machines, storage accounts, and databases. Tags help you organize, sort, bill, and manage it all without losing your way. For beginners or career changers, learning tagging is like learning to name files on your computer—simple, but powerful.

---

## 📘 Bonus: Learn 7 Danish Tech Words

| English Term         | Danish Word            |
|----------------------|-------------------------|
| Tag                  | Mærkat                |
| Resource Group       | Ressourcegruppe         |
| Virtual Machine      | Virtuel Maskine         |
| Filter               | Filter                  |
| Apply                | Anvend                  |
| Department           | Afdeling                |
| Delete               | Slet                    |

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

✍️ Created & Curated by  
**Muhammad Naveed Ishaque**  
_Content Creator | AI Writer | Narrative Simplifier_  
_With the inner voice of eks2 — the whisper behind the work._

**Siraat AI Academy**  
_“The Straight Path — Empowering minds with clarity, illuminating paths with purpose.”_
