# 🤖 Copilot Chat FAQ

## 1. General Questions

### 1.1 What is Microsoft Copilot?
Microsoft Copilot is an AI assistant built into Microsoft 365 apps (Word, Excel, Outlook, Teams). It helps you create content, generate summaries, automate tasks, and analyze data using natural language.

### 1.2 What is Copilot Studio?
Copilot Studio is a no-code/low-code platform for building your own AI Copilots. You can design conversation flows, integrate workflows, and connect to custom data sources.

### 1.3 What is the difference between Copilot and Copilot Studio?
- **Copilot (M365)**: Prebuilt AI assistant inside Microsoft apps.
- **Copilot Studio**: A platform to design and deploy customized Copilots tailored to your team or business needs.

### 1.4 Is Copilot secure and private?
Yes. Copilot follows Microsoft’s enterprise-grade security and compliance standards, ensuring data protection and privacy.

### 1.5 What apps does Copilot work with?
Copilot integrates with Outlook, Excel, Word, Teams, Power Platform, SharePoint, and can connect to custom APIs using Power Automate.

## 2. Copilot Studio FAQs

### 2.1 Can I build a Copilot without coding?
Yes! Copilot Studio offers a visual designer where you can drag & drop conversation topics, decision logic, and actions—no coding required.

### 2.2 What are topics in Copilot Studio?
Topics are conversation triggers and dialogues—e.g., you might create a "reset password" or "order status" topic that activates when users ask about those subjects.

### 2.3 What role does Power Automate play?
Power Automate allows your Copilot to perform actions such as sending emails, calling APIs, or updating databases—all from conversational flows.

### 2.4 Can I connect to SharePoint or Excel?
Absolutely. Use Power Automate connectors to integrate SharePoint Lists, Excel files, Dataverse tables, and more as back-end data sources.

### 2.5 How do I publish and share my Copilot?
Once built, you can share the Copilot via:
- A web embed
- A Teams App
- A direct URL link

## 3. Copilot Chat Agent FAQs

### 3.1 Can I control what the agent says?
Yes! In the free Copilot Chat, you can paste instructions or FAQs directly into the agent’s setup to guide its responses.

### 3.2 Can the agent answer only from my document?
Yes. If you provide a public document with **2-level deep headings**, the agent will restrict its answers to content from there.

### 3.3 What does “2‑level deep” mean?
Your document structure should look like this:
- Heading (e.g., “3.3 Question”)
  - Subheading (e.g., “Answer or details”)
    - (No deeper nesting than this)

### 3.4 Can the chat agent perform actions like sending emails?
Not in the free version. That functionality requires Power Automate integration, which is available in paid plans.

---

## 🔗 How to Use This in Copilot Chat

1. Host this file publicly (e.g., on GitHub).
2. In Copilot Chat settings, add the **public link** to this README under the “Knowledge source” or “Instruction” section.
3. Ensure the bot can access the file (it must not be private).
4. Demo by asking questions like:
   - “What is Copilot Studio?”
   - “Can the agent send emails?”
   - “Is Copilot secure?”
