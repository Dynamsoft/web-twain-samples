# Dynamic-Web-TWAIN-skill

Skill for [Dynamic Web TWAIN SDK](https://www.dynamsoft.com/web-twain/overview/).

[Agent Skills](https://agentskills.io/) is an open standard for extending AI agents with specialized capabilities. Skills package domain-specific knowledge and workflows that agents can use to perform specific tasks.

You can put the `use-dynamic-web-twain` folder in the following places to make it effective.

| Location            | Scope               |
| ------------------- | ------------------- |
| `.agents/skills/`   | Project-level (for all agents)       |
| `.claude/skills/`   | Project-level       |
| `~/.claude/skills/` | User-level (global) |

Replace `claude` with your agent's name, like `.codex/skills/`, `.cursor/skills/`.

You can also install the skill with the following command:

```bash
npx skills add https://github.com/Dynamsoft/web-twain-samples/
```

## Prompt Examples

You can use this skill to create Web TWAIN samples or modify an existing project to use Web TWAIN or ask questions.

1. Vanilla-JS local resources sample.

   ```
   Create an index.html file to use Dynamic Web TWAIN to scan documents, with basic document scanners listing and configuration functions. Please use resources files included in SDK instead of using CDN.
   ```

2. React sample.

   ```
   Create a react project to use Dynamic Web TWAIN to scan documents. I only need a minimum sample which lists scanners, sets whether to use document feeder, DPI, pixel type and scans documents.
   ```

3. Modify an existing Angular project.

   ```
   Please create a component to use Dynamic Web TWAIN for document scanning in this angular app. Just a scan button to perform scanning and view the document in a viewer.
   ```

4. Ask questions.

   ```
   What is Dynamic Web TWAIN service? Please also show the links of referenced docs.
   ```





