# User Story Template

This template is for writing **clear, testable user stories** that both business and technical people can understand.



## 1. Basic information

- **ID:** US-XX  
- **Epic:** EP-XX – <Epic name>  
- **Priority:** (Must / Should / Could)  
- **Status:** (Planned / In Progress / Done)  
- **Estimate:** (S / M / L or story points)



## 2. Story statement

> **As a** `<role>`  
> **I want** `<capability>`  
> **So that** `<business value / outcome>`

Example:

> As a **team member**, I want to **create a new task with a due date** so that **I don’t lose track of my responsibilities**.



## 3. Business context (optional but recommended)

- **Problem:**  
  Short description of the pain point this story addresses.

- **Why now:**  
  Why this matters at this stage of the project (e.g. MVP, regulatory requirement, dependency).



## 4. Acceptance criteria

Write acceptance criteria as simple, testable statements.

Example structure:

- [ ] When `<condition>`, and `<action>`, then `<expected result>`.  
- [ ] Error conditions and edge cases are handled (describe them).

You can also use Gherkin style (Given / When / Then) if the team prefers:

- **Given** …  
- **When** …  
- **Then** …



## 5. UI / UX notes (if relevant)

- Screens or components affected  
- Behaviour on different devices (desktop / mobile)  
- Error messages or empty states

Attach wireframes or link to design files if available.



## 6. Dependencies & assumptions

- Other stories, features or systems this depends on  
- Assumptions we are making (e.g. “single team only”, “authentication exists already”)



## 7. Non-functional considerations

Only if relevant for this story (not every story needs all of these):

- Performance expectations  
- Security / privacy concerns  
- Accessibility notes  
- Logging / audit needs



## 8. Test notes

- Key test scenarios the QA or team should cover  
- Any special data needed for testing



## 9. Out of scope (explicitly)

List anything that might be easily assumed but is **not** included in this story.  
This reduces misunderstandings and scope creep.
