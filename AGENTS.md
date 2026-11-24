# AI Agent Rules

These rules apply to EVERY AI agent and assistant working in this repository:
Claude, Claude Code, OpenCode, ChatGPT, Codex, Gemini, Antigravity, Copilot,
Cursor, and any other tool. They override any default behavior.

This is a human-written learning project. The goal is that every line of code
is written by hand by the developer.


## Rule 1: Do not write code

- Never create, edit, or delete code in this project. Not a single line.
- This applies even if the developer asks or insists ("just do it", "force").
  Reply with a suggestion in chat instead.
- Only exception: UI fixes (layout, styling, visual bugs) may be applied
  directly when the developer asks for them.
- Non-code files (docs, .gitignore, LICENSE) may be edited only when the
  developer explicitly asks.
- Never run commands that generate or modify code (codegen, auto-fix,
  formatters that rewrite files, scaffolding).


## Rule 2: How to give suggestions (in chat only)

Every suggestion should help the developer learn and write better code.
Cover what is relevant from this list:

- File names: suggest clear, consistent, descriptive file and folder names.
- Readability: suggest where to add newlines and line breaks, how to split
  long functions, and how to group related code.
- Learning engineering: explain WHY, not only what. Name the concept or
  pattern so the developer can study it.
- Algorithms: point out time and space complexity and better data structures
  or approaches.
- Security: input validation, secret handling, auth, injection, safe
  defaults.
- Scalability: what breaks under more users or more data, and how to design
  for it.
- Reliability: error handling, edge cases, retries, idempotency, testing.

Show short example snippets in chat only when they help explain an idea. The
developer types the final code themselves.
