# Nevo Engine Bug Tracker

Welcome to the official bug tracker for **Nevo Engine**. This is the central hub for reporting bugs, issues, and unexpected behaviour in the engine. Following the guidelines below ensures that issues are clear, actionable, and can be resolved efficiently.  

---

## 📝 Reporting Guidelines

Before creating a new issue, **search existing issues** to avoid duplicates. Duplicate or vague reports slow down development and waste everyone's time.  

### Required Information for Every Issue
Every issue must include the following:

1. **Title** – Concise and descriptive (e.g., `Renderer crashes when loading .fbx meshes`).
2. **Description** – Detailed explanation of the problem.
3. **Steps to Reproduce** – List the exact steps needed to trigger the bug.
4. **Expected vs Actual Behavior** – What you expected to happen vs what actually happened.
5. **Environment** – Include:
   - OS and version
   - Graphics API (e.g., DirectX 11)
   - Engine version/build
6. **Attachments (if applicable)** – Screenshots, logs, or minimal reproducible examples.

> ⚠️ Issues that lack clear steps or minimal reproducible examples may be closed immediately.

---

## 🧹 Formatting Rules

- Use **clear, precise language**. Avoid vague terms like “doesn’t work.”
- Use **code blocks** for code snippets or error messages.
- **Do not** include unrelated discussion, feature requests, or opinion-based comments—this is a bug tracker, not a forum.
- Assign **priority** if possible (Low / Medium / High / Critical).

---

## 🚫 What Not to Report

- General feature requests → Use the Discord forum instead.
- Personal support questions → Use Discord.
- Duplicate issues → Search first. Duplicate reports will be closed and linked to the original.

---

## ⚡ Severity Levels

| Severity | Description |
|----------|-------------|
| Critical | Engine crashes, corrupts data, or completely blocks workflow. |
| High     | Major functionality broken, workarounds not available. |
| Medium   | Minor feature broken or partially working; workaround exists. |
| Low      | Cosmetic issues, typos, or minor annoyances. |

---

## 🏷️ Tagging Issues

Use tags whenever possible:

- `bug` – Actual bug affecting engine functionality
- `crash` – Issue that crashes the engine
- `performance` – Lag, memory leaks, or slow operations
- `graphics` – Rendering-related issues
- `input` – Input, controls, or key handling issues
- `build` – Compilation or linking issues

---

## ⚙️ Workflow

1. **New Issue Created** → Triaged by developers  
2. **Confirmed / Reproduced** → Assigned a severity and tag  
3. **In Progress** → Actively being fixed  
4. **Fixed / Closed** → Patch merged or resolved  

> Issues may be closed if they cannot be reproduced, lack details, or are duplicates.

---

## 💡 Tips for Effective Reporting

- Always test against the **latest stable build** before reporting.  
- Include **minimal reproducible examples** whenever possible.  
- Be concise but thorough—developers shouldn’t have to guess what went wrong.  

---

Nevo Engine development relies heavily on **high-quality bug reports**. Following these rules ensures your issue will be taken seriously and fixed quickly.
