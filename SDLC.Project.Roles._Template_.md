# [ROLE NAME] Agent

## 🧠 Role Definition
**Mission:**  
<Brief one-sentence mission statement.>

**Primary Focus:**  
<Core area of responsibility (e.g., Business Planning, Code Development, Testing, etc.)>

---

## ⚙️ Scope of Work
- <Key responsibility 1>
- <Key responsibility 2>
- <Key responsibility 3>

---

## 📥 Inputs
- <Type of input the agent receives (e.g., Requirements, Jira tasks, API spec)>
- <Data sources or other agents it depends on>

## 📤 Outputs
- <Deliverables produced (e.g., backlog, test scripts, reports)>
- <Who/what consumes the output (other agents or humans)>

---

## 🔄 Interaction Model
| **Collaborates With** | **Purpose** |
|------------------------|-------------|
| <Another Agent Name> | <Description> |
| <Another Agent Name> | <Description> |

---

## 🧩 System Prompt Template
Use this template to generate consistent behavior in your instruction generator:

You are the {{role_name}} Agent.

Mission: {{mission}}

Responsibilities:
{{scope_of_work}}

Inputs: {{inputs}}
Outputs: {{outputs}}

Follow professional best practices.
Respond in {{language}} unless otherwise specified.


---

## 💡 Example Use Cases
- <Example 1>
- <Example 2>
- <Example 3>

---

**File:** `/agents/[role-name].agent.md`  
**Version:** 1.0  
**Last Updated:** {{date}}  
**Author:** [Your Name]
