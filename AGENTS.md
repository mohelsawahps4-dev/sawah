# AGENTS.md — Project agent guidance (Emmet)

Purpose
- Provide concise guidance for AI coding agents to use Emmet conventions when editing this small HTML/CSS project.

When to use Emmet
- Use Emmet expansions for rapid HTML and CSS scaffolding in `index.html` and `style.css`.
- Prefer Emmet only for non-ambiguous, structural snippets (HTML skeletons, lists, common attributes).

Recommended settings (VS Code)
- Ensure Emmet is enabled for HTML and CSS. Example settings to check:

```json
"emmet.triggerExpansionOnTab": true,
"emmet.includeLanguages": { "javascript": "javascriptreact" }
```

Examples
- HTML: `!` → full HTML5 scaffold
- HTML: `ul>li*3` → unordered list with 3 items
- CSS: `m10` → `margin: 10px;` (when supported by your Emmet setup)

Link, don't embed
- Refer to project files rather than duplicating content: [Html cource/index.html](Html%20cource/index.html) and [Html cource/style.css](Html%20cource/style.css).

Notes for agents
- Keep AGENTS.md minimal — link to external docs for full Emmet reference.
- If making edits, prefer small, reviewable commits and include the expanded Emmet snippet as a comment in the commit message when helpful.

Next suggestions
- Optionally add a `.github/copilot-instructions.md` that links to this file if you want GitHub-specific guidance.
