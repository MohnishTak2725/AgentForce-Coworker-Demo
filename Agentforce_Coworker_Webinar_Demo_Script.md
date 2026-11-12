# Agentforce Coworker: Live Webinar Demo Playbook

**Target Presentation Time**: 8 – 10 Minutes  
**Audience**: Salesforce Admins, Architects, Business Stakeholders, and End Users  
**Environment**: Developer Edition / OrgFarm with Agentforce Coworker & Data Cloud enabled  

---

## At-A-Glance Timeline & Stage Plan

```
┌────────────────────────────────────────────────────────────────────────┐
│  00:00 - 01:30  │ ACT 1: The Hook & The Problem Statement              │
│  01:30 - 03:15  │ ACT 2: Under the Hood: 2-Minute Setup in Setup       │
│  03:15 - 04:00  │ ACT 3: The Big Reveal: [✨ Ask] Button & AI Canvas   │
│  04:00 - 07:00  │ ACT 4: The 3 Live Superpowers (Find, Catch Up, Act)  │
│  07:00 - 08:15  │ ACT 5: Boundaries & Limitations in Plain English     │
│  08:15 - 09:30  │ ACT 6: Enterprise Governance & Wrap-up / Q&A         │
└────────────────────────────────────────────────────────────────────────┘
```

---

## ACT 1: The Hook & The Tab-Fatigue Problem (00:00 – 01:30)

### Visual on Screen
- Start on the **Salesforce Lightning Home Page** (Sales or Service App).
- Have a clean browser window with no distractions.

### Spoken Script
> *"Hello everyone, and welcome!
> 
> Let me start with a quick question: **How many browser tabs do you typically have open when working in Salesforce?** 
> 
> If you're like most sales reps, support agents, or account managers, you're constantly 'swivel-chairing'—jumping between 15 different browser tabs, account records, chatter feeds, emails, and spreadsheets just to answer basic questions like: *'What is going on with this customer?'* or *'What high-priority issues happened overnight?'*
> 
> Today, we're not talking about another isolated chatbot sitting in an external window. We are talking about **Agentforce Coworker**—Salesforce's native, conversational AI teammate built directly into the search bar you already use every day.
> 
> In this demo, I'm going to show you how easy it is to enable in Setup, how the new **'Ask'** button transforms your interface, and three real-world superpowers you can use immediately."*

---

## ACT 2: Behind The Scenes: 2-Minute Setup (01:30 – 03:15)

### Mouse Action
- Click the **Gear Icon** (⚙️) in the top-right header and select **Setup**.

### Step 1: User Security & Permission Set Group (01:45)
1. In the Quick Find box on the left, type `Users` and click **Users**.
2. Click into your active user record.
3. Scroll down to **Permission Set Group Assignments** and highlight **`Agentforce Coworker User`** (`Access_Ai_Search`).

#### Spoken Script
> *"Before we turn on any AI, let's talk about the number one concern for enterprise teams: **Security and Data Access.**
> 
> Coworker is 100% compliant with your existing Salesforce security model. By assigning the **Agentforce Coworker User** permission set group, the AI instantly inherits standard Profiles, Field-Level Security (FLS), and Sharing Rules. 
> 
> If a user doesn't have permission to see an Opportunity amount, a custom field, or a private case in standard Salesforce, the AI will never read or reveal it. There is zero risk of data leakage across departments."*

### Step 2: The Setup Detail Page & Enablement Toggle (02:30)
1. In the Quick Find box, type `Agentforce Coworker`.
2. Click **Get Started with Agentforce Coworker**.
3. Point out the setup dashboard and the **Turn On** status toggle.

#### Spoken Script
> *"Now, look at how simple enablement is. In Setup, you simply search for 'Agentforce Coworker' and open the setup panel.
> 
> When you flip this toggle to **On**, Salesforce automatically connects the backend `SearchAgent` engine, links your Data Cloud unified indices, and provisions the conversational search interface for all assigned users. That's it—no complex code deployments, no custom middleware."*

---

## ACT 3: The Big Reveal: The [✨ Ask] Button (03:15 – 04:00)

### Mouse Action
- Click the App Launcher (9 dots) or navigate back to the **Sales** or **Service** app.
- Slowly move your cursor up to the top **Global Search bar**.

### Visual Highlight
- Hover over the **[✨ Ask]** button with the AI wand icon sitting right inside/alongside the search bar.
- Click **[✨ Ask]**.
- Watch the screen transition into the full-canvas conversational workspace.

### Spoken Script
> *"Now, let's look at the magic from an end-user's perspective.
> 
> Notice right here, right next to the standard Global Search bar, we have a brand new button: **'Ask'** with an AI wand icon.
> 
> When an employee clicks **'Ask'**, instead of getting a static list of 50 blue record links, it opens this clean, modern conversational canvas. It feels just as intuitive as ChatGPT or Gemini, but it is **natively grounded** in your enterprise CRM records, customer history, and Data Cloud."*

---

## ACT 4: The 3 Live Superpowers (04:00 – 07:00)

### Superpower 1: "FIND" Mode – Semantic Search with Citations (04:15 – 05:15)

#### Copy-Paste Prompt
```text
What are our top merchant accounts in California and what is their current status?
```

#### What to Highlight
- Point out how quickly the synthesized answer appears.
- Hover over the **clickable record pills / citations** embedded inside the AI response.

#### Spoken Script
> *"Watch this first power: **Semantic Find**.
> 
> I didn't type keywords like 'Account California status'. I asked a natural question.
> 
> Coworker analyzed the query, searched across our CRM records, and synthesized a structured answer. And look closely: **every claim has a clickable citation pill**. I can click right on this account name to inspect the real record, meaning zero hallucination and 100% auditability."*

---

### Superpower 2: "CATCH UP" Mode – Instant Workspace Briefing (05:15 – 06:15)

#### Copy-Paste Prompt
```text
Catch me up on high-priority cases and escalations logged this week.
```

#### What to Highlight
- Point out that Coworker reviews recent activity logs, chatter updates, and case comments.
- Show how it categorizes urgency into bullet points.

#### Spoken Script
> *"Here is the second superpower: **Catch Up**.
> 
> Imagine you just returned from PTO, or you're stepping into an executive briefing. Instead of scrolling through 40 unread Chatter notifications and emails, you type 'Catch me up'.
> 
> Coworker scans recent changes across records you follow or own, categorizes the critical blockers, and tells you exactly what requires immediate action today."*

---

### Superpower 3: "PLAN & ACT" Mode – Human-in-the-Loop Action (06:15 – 07:00)

#### Copy-Paste Prompt
```text
Draft a follow-up email to the account owner of our top escalated merchant proposing a resolution and a 10% promotional credit.
```

#### What to Highlight
- Show the **Interactive Action Card / Draft Preview** that appears in the viewport.
- Emphasize the **Approve / Edit / Cancel** options before anything is sent.

#### Spoken Script
> *"Finally, the third superpower: **Plan and Act**.
> 
> Coworker doesn't just read information—it can orchestrate tasks. Here, it generated a professional resolution email tailored to the specific case history.
> 
> But notice the most critical enterprise design pattern: **Human-in-the-Loop**. Coworker did not blindly send this email or write to the database. It presented an interactive preview card. I can review the text, tweak the discount amount, and click Approve. Complete automation with zero loss of control."*

---

## ACT 5: Boundaries & Limitations in Plain English (07:00 – 08:15)

### Spoken Script
> *"Now, before we wrap up and take your questions, every enterprise architect and executive in the room is wondering: **'What are the real-world boundaries, limitations, and guardrails we need to know about?'**
> 
> Let me share four key considerations in plain language:
> 
> 1. **Single-Seat Developer Limit**: In free trial or developer environments like the one I'm demonstrating today, Salesforce allocates strictly **one user license** (`AISearchUserPsl`) and one admin setup seat. It is designed for 1-to-1 evaluation. In full production, you license seats across your teams.
> 2. **The Data Cloud Backbone**: Coworker doesn't operate in a vacuum—it requires **Data Cloud** running behind the scenes. Think of Data Cloud as the AI's long-term memory and indexing engine; without it, Coworker cannot ground its answers across your CRM and enterprise documents.
> 3. **Document & Sync Boundaries**: While Coworker can search external files from SharePoint or Google Drive, documents larger than **75 megabytes** are not indexed. Also, external documents sync on a scheduled cadence (typically hourly)—so if you edit a Word doc in SharePoint, allow a little sync time before expecting Coworker to find the update.
> 4. **Strict Security Mirroring**: Coworker never peeks around corners. If a record or field is restricted from a user by your Sharing Rules or Field-Level Security, Coworker will state that no information was found. It respects your existing security model 100%."*

---

## ACT 6: Enterprise Wrap-Up & Q&A (08:15 – 09:30)

### Visual on Screen
- Return to the conversational view with the complete thread visible.

### Spoken Script
> *"To bring it all together, remember these three core pillars of Agentforce Coworker:
> 
> 1. **Zero Adoption Friction**: Your users don't need training on a new tool. It sits right in the Global Search bar they already use daily.
> 2. **Complete Data Governance**: Fully inherits your existing Roles, Sharing Rules, and Field-Level Security.
> 3. **The Einstein Trust Layer**: Enterprise-grade Zero Data Retention—your private customer data is never stored, logged, or used to train external LLMs.
> 
> Anyone can sign up for a free developer environment, flip the toggle in Setup, and start empowering their team today.
> 
> Thank you so much for your time, and let's open the floor to questions!"*

---

## Presenter Cheat-Sheet: Quick Copy-Paste Prompts

Keep these 3 lines open in a Notepad window on your secondary monitor:

1. `What are our top merchant accounts in California and what is their current status?`
2. `Catch me up on high-priority cases and escalations logged this week.`
3. `Draft a follow-up email to the account owner of our top escalated merchant proposing a resolution and a 10% promotional credit.`
