
# ⛪ SOP: Sermon Content Processing
**Goal:** Turn a raw PDF transcript into a YouTube video, social posts, and an email.

## 🛠 Preparation
1. **PDF:** Drag the pastor's PDF into `01_Transcripts`.
2. **Transcript Note:** Create a new note in `02_Sermon_Notes` named `Transcript - [Date] - [Title]`.
3. **Sermon Note:** Create a second note named `Sermon - [Date] - [Title]`.
    - Add the **Properties** (Date, Pastor, CTA) to the top.
    - Add the link: `Source: [[Transcript - [Date] - [Title]]]`

## 🚀 The Execution (Gemini Chat)
Open the **Sermon Note** and paste this command into the Gemini sidebar:

> "Load **[[Skill - Ministry Content Director]]** and **[[Skill - Markdown Architect]]**. 
> Please execute **[[Workflow - Sermon Repurposing Engine]]** using the text in **[[Transcript - [Date]]]**."

## 🔄 The "Hand-off" Workflow
1. **Phase 1 (Cleanup):** Copy the clean text from the chat and replace the messy text in your `Transcript` note.
2. **Phase 2 & 3 (Drafting):** Let the Agent finish the YouTube and Social drafts.
3. **Distribution:** - Copy the final "Outputs" from Obsidian.
    - Paste into the **Team Google Doc**.
    - Update the **Status** in your Sermon Note properties to `✅ Published`.

---
## 🔗 Quick Links
- [[EFC - Sermon Repurposing Dashboard]]
- [[90_System/Prompts/Workflow - Sermon Repurposing]]