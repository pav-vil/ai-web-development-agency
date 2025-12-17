# AI Web Development Agency — Standard Operating Procedures (SOP)

## 1. Company Overview

**Company Type:** AI-First Web Development Agency  
**Delivery Model:** AI-generated work with human review  
**Primary Output:** Web apps, MVPs, dashboards, internal tools

---

## 2. Roles & Responsibilities

### Human Roles
- **Agency Lead**
  - Final technical decisions
  - Client communication
  - Approvals and delivery
- **Reviewer (optional, same person initially)**
  - Security review
  - Architecture sanity check
  - Deployment approval

### AI Roles
- Project Manager Agent
- Backend Engineer Agent
- Frontend Engineer Agent
- Code Reviewer Agent
- DevOps / Deployment Agent
- Documentation Agent

---

## 3. Project Lifecycle SOP

### Step 1: Client Intake
- Capture:
  - Business goal
  - Features
  - Budget
  - Timeline
  - Deployment target
- Output: `spec.md`

---

### Step 2: Planning Phase
- Define:
  - Architecture
  - Tech stack
  - Data models
  - Milestones
- Output:
  - `architecture.md`
  - `tasks.md`

Human approval required before coding.

---

### Step 3: Implementation Phase
- Work is done **task by task**
- Each task:
  - Assigned to correct AI agent
  - Reviewed before merging
- Output:
  - Working code
  - Updated `tasks.md`

---

### Step 4: Review Phase
- Code Reviewer Agent checks:
  - Bugs
  - Security issues
  - Readability
- Human approves or requests fixes

---

### Step 5: Deployment
- DevOps Agent:
  - Prepares Docker / environment config
  - Generates deployment checklist
- Human performs deployment

---

### Step 6: Delivery
- Documentation Agent generates:
  - Setup instructions
  - Basic usage guide
- Final handoff to client

---

## 4. Quality Standards

- Code must run without modification
- No plaintext secrets
- Clear structure
- Maintainable patterns
- No experimental libraries

---

## 5. Escalation Rules

AI must stop and escalate when:
- Security is unclear
- Architecture choice is risky
- Requirements conflict
- Missing critical info

---

End of SOP
