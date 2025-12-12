# Risk Log Template

Simple structure for tracking risks, assumptions and mitigations in IT projects.

| ID  | Type  | Description                                    | Impact (H/M/L) | Likelihood (H/M/L) | Owner       | Mitigation / Response                              | Status        |
|-----|-------|------------------------------------------------|----------------|---------------------|-------------|----------------------------------------------------|---------------|
| R-1 | Risk  |                                                |                |                     |             |                                                    | Open          |
| R-2 | Risk  |                                                |                |                     |             |                                                    | Open          |
| A-1 | Assumption |                                          | n/a            | n/a                 |             | How we will validate this assumption               | Under review  |
| D-1 | Dependency |                                           | If blocked, impact = ? |          |             | How we track / manage this dependency              | In progress   |

**Columns explained**

- **ID** – unique identifier (R-1, A-1, etc.).  
- **Type** – Risk, Assumption, Dependency.  
- **Description** – short, concrete description.  
- **Impact** – how serious it is if it happens.  
- **Likelihood** – how likely it is to happen.  
- **Owner** – who is responsible for watching it.  
- **Mitigation / Response** – what we plan to do about it.  
- **Status** – Open / Under review / Mitigated / Closed.

In practice this can live in a spreadsheet, Jira, Confluence or any other tool; the structure stays the same.
