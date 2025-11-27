# ReviewDesk

> One desk for every approval.

---

## ✨ Features

- **Multi-step approval workflows**  
  Create custom workflows like: `Employee → Manager → Finance → Director`.

- **Reusable request types**  
  Use ReviewDesk for leave, expenses, purchase orders, document approvals and more.

- **Role-based access control (RBAC)**  
  Define roles like *Requester*, *Approver*, *Admin* and control who can do what.

- **Status tracking & history**  
  Every request has a timeline: who approved, rejected, or commented – and when.

- **Versioning & Compare Mode**  
  Track every change made to a request and compare different versions side by side to see exactly what was updated before approval.

- **Notifications**  
  Notify approvers when a new request arrives and requesters when decisions are made.

- **Audit-friendly logs**  
  Keep a clear record of all decisions for compliance and future reference.

---

## 🧩 Core Concepts

- **Request** – Something that needs approval (leave, expense, purchase, document, etc.)
- **Workflow** – A sequence of approval steps.
- **Step** – A single stage in the workflow (e.g., Manager Approval).
- **Approver** – User/role responsible for a step.
- **Action** – Approve, reject, or send back with a comment.

---

## 🏗️ Architecture

- **Frontend:** Angular  
- **Backend:** Nest.js
- **Database:** PostgreSQL

Suggested high-level modules:

- `auth` – users, roles, permissions  
- `workflows` – workflow definitions and steps  
- `requests` – individual approval requests  
- `actions` – approvals, rejections, comments  
- `notifications` – email / in-app notifications

---

## 🧭 Roadmap / Ideas

- [x] Template workflows (e.g. Leave Approval, Expense Approval, PO Approval)
- [ ] Simple analytics dashboard (average approval time, bottlenecks)
- [ ] Integration webhooks (trigger events to other systems)
- [ ] Multi-tenant support (multiple companies using one instance)

