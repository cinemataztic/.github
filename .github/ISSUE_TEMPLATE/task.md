---
name: 🔧 Technical Task
about: Standalone technical work — tech health, security, upgrades, debt paydown, or feature enablement.
title: ''
labels: ['engineering-inbox']
assignees: ''
type: Task
---

### 📍 Target Repository
*Which GitHub repository should this change be made to?*
- Repo: `cinemataztic/name-of-repository`

### 🔨 Technical Context
*What needs to be done?*
*(e.g. "Upgrade React to v18", "Provision DB for new market", "Refactor auth middleware", "Patch CVE-XXXX")*

### 🎯 Motivation
*Why is this needed now? (e.g., security CVE, version EOL, performance debt, refactoring blocker, feature enabler)*

### 📍 Affected Components
- **Service/Module:**
- **Version/Dependency (if applicable):**

### 🔗 Parent Relation
*Link this as a sub-issue to a Story or Epic if applicable.*

### ✅ Definition of Done
- [ ] Changes implemented
- [ ] Tests added/updated
- [ ] No regression in dependent services

---
### ⚠️ Classification Check
*Default classification for technical tasks is **Maintenance** (proactive technical health — tech debt, security, refactoring, EOL).*

- [ ] **Is this enabling a specific Feature/Epic?** → Set Classification to **Innovation** and link the parent.
- [ ] **Is this incident remediation or reactive support?** → Set Classification to **KTLO**.
- [ ] **Is this research, spike, or due diligence?** → Set Classification to **Strategic**.
- [ ] **Otherwise (tech debt, security upgrade, EOL, refactor):** → Keep default **Maintenance**.

> [!TIP]
> **Triage:** Default Classification is **Maintenance** in [Project 91](https://github.com/orgs/cinemataztic/projects/91). Adjust based on the check above.
