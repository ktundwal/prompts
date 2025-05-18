# Developer Productivity Boost

A list of a few productivity boosts to help your team ship faster, learn more effectively, and build better systems.

---

## 1: Leveraging AI for Parallel Task Execution

**Actions:**
- Use GitHub Copilot in VS Code for TypeScript/C# boilerplate and small edits
- Batch tasks via prompts (e.g., multiple test generations)
- Use ChatGPT for code review drafts before human review

**Prompt Templates:**

### Generate Unit Tests

**TypeScript (Jest)**
```ts
// Prompt:
"Write Jest unit tests for the following TypeScript function. Include edge cases and one failure scenario."
```

**C#**
```csharp
// Prompt:
"Generate xUnit tests for the following C# method. Include both success and failure cases."
```

### Refactor Code

**TypeScript**
```ts
// Prompt:
"Refactor the following TypeScript function to be more concise and readable without changing its behavior:"
```

**C#**
```csharp
// Prompt:
"Extract a well-named method from the highlighted C# code block and replace it in the original method."
```

### Review Code
```ts
// Prompt:
"Review this code diff for correctness, performance, readability, and maintainability. Suggest improvements."
```

---

## 2: Support Early-in-career Dev Growth

**Actions:**
- Use AI in "shadow mode" (juniors try first, compare later)
- Require justification of AI suggestions
- Manual Fridays for skills reinforcement

### Explain AI Suggestions
```ts
// Prompt:
"Explain why this AI-suggested solution works. What are the edge cases it may miss?"
```

---

## 3: Ethical Open Source & Code Use

**Actions:**
- Maintain prompt-safe snippet repo
- Use GitHub Advanced Security for license scanning
- Tag AI code with `// @copilot-suggested`

---

## 4: Measuring Productivity

**Actions:**
- Track `Time to PR`, `PR to Deploy` via Azure DevOps Analytics
- Weekly blocker logs
- Feature flags + telemetry via Azure App Insights

---

## 5: Improving Developer Experience

**Actions:**
- Auto-format + lint on save (Prettier, ESLint, EditorConfig)
- Use Hot Reload (.NET 6+)
- GitHub Codespaces or Azure Dev Boxes for disposable envs
- One-click new project templates

---
