# 📋 Project Workflow Automation – Adonis Edge MVP

This project uses **GitHub Projects Beta (Automation Workflows)** to streamline issue tracking and project board organization.

---

## ✅ Enabled Workflows & Automations

### 🟢 Item Added to Project
- **Trigger:** When an issue or PR is added to the project.
- **Action:** Automatically sets:
  - `Status → To Do`

---

### 🔁 Item Reopened
- **Trigger:** When an issue or PR is reopened.
- **Action:** Automatically sets:
  - `Status → In Progress`

---

### ✅ Item Closed
- **Trigger:** When an issue or PR is closed.
- **Action:** Automatically sets:
  - `Status → Done`

---

### 🐞 Auto-Add to Project (Filtered)
- **Trigger:** Any new or updated item in repository `adonis-edge`.
- **Condition:** Must have:
  - `is:issue, is:open, label:bug`
- **Action:** Automatically adds the item to the project board.

---

### 🔄 Auto-Close Issue
- **Trigger:** When an issue is marked `Done` in the project.
- **Action:** Automatically closes the related GitHub Issue.

---

### 🧩 Auto-Add Sub-Issues to Project
- **Trigger:** When a parent issue with checklists/subtasks is added.
- **Action:** All sub-issues are added automatically to the project board.

---

## 📌 Columns and Status Mapping

| Project Column   | GitHub Status         |
|------------------|----------------------|
| To Do            | Newly added items    |
| In Progress      | Reopened issues or PRs |
| Done             | Closed items         |

---

## 🔐 Permissions

> These workflows use the default `GITHUB_TOKEN`, scoped to the repository.

No manual label or movement is required. Simply assign the issue to the project or apply the relevant label – automation will handle the rest.

