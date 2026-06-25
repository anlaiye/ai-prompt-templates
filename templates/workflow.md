# Generic Workflow Template

Copy this template, replace `[ ]` placeholders, and send it to AI.

---

## [Workflow Name]

### Roles

- **[Role 1](variable_name)**: [what they do]
- **[Role 2](variable_name)**: [what they do]
- **[Role 3]**: [what they do]

### Main Flow

```mermaid
graph TD
  A[Start] --> B[[Step 1]]
  B --> C[[Step 2]]
  C --> D{[Branch Point]}
  D -- [Condition 1] --> E[[Step 3]]
  D -- [Condition 2] --> F[[Step 4]]
  E --> G[End]
```

### Branch Conditions

**Branch Point Name:**

| Action | Condition | Target | Description |
|--------|-----------|--------|-------------|
| [Action 1] | [var=value] | → [target] | [business meaning] |
| [Action 2] | [var=value] | → [target] | [business meaning] |

### Special Paths

- **Loop**: [Node A] → [Node B] → [back to Node A] (reason)
- **Shortcut**: [Node A] → skip [Nodes B/C] → directly to [Node D]

### Technical Details (optional)

- Engine: [e.g. Activiti / Camunda / custom]
- Key variables: [var]=[value] meaning
- Form mapping: [node] → [form path]
