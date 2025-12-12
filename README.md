# Cinemataztic Engineering Standards 🎬

This repository serves as the **Single Source of Truth** for our engineering workflows, issue templates, and standard practices across the organization.

By centralizing these configurations, we ensure consistency across all projects and make maintenance easier.

## 📋 Global Issue Templates

We have standardized our issue types to simplify our board and align with our "Calm Work" philosophy. These templates apply automatically to any repository that does not have its own local templates.

| Type | Emoji | Purpose | When to use? |
| :--- | :---: | :--- | :--- |
| **Epic** | 🏔️ | **Strategy & Goals** | Large initiatives (e.g., "Big Bio Launch"). Defines the *Why*, *Scope*, and *Deliverables*. |
| **Story** | 🚀 | **User Value** | Features that deliver value to the end-user. Use checkboxes for implementation steps. **Do not create sub-issues.** |
| **Task** | 🔧 | **Tech / KTLO** | Standalone technical work, maintenance, or enabling work (e.g., "Upgrade React", "Provision DB"). |
| **Bug** | 🐞 | **Fixes** | Something is broken or behaving unexpectedly. Requires steps to reproduce. |

### ⚠️ Key Workflow Rules
1.  **No Sub-issues:** We do not use separate GitHub Issues for sub-tasks. Use **Checklists** inside the Story description instead.
2.  **Tasks vs. Stories:** If it delivers user value, it's a **Story**. If it's purely technical/maintenance, it's a **Task**.
3.  **Keep it Clean:** "Task" issues are strictly for standalone work. Do not create a "Task" issue just to track a sub-step of a Story.

---

## 🛠 How to Adopt These Standards

If a repository has a local `.github/ISSUE_TEMPLATE/` folder, GitHub will ignore these global defaults.

**To adopt these standards in a repository:**
1.  Delete the local `.github/ISSUE_TEMPLATE/` directory in that repository.
2.  The repository will immediately inherit the global templates from this repo.

---

## 🤝 Contributing

If you want to suggest changes to a template (e.g., adding a section to the Bug Report):
1.  Open a Pull Request in this repository (`.github`).
2.  Once merged, the change will propagate to **all** repositories in the organization instantly.
