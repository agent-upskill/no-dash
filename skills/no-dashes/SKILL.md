---
name: no-dashes
description: "Enforces no-dashes rule — never use \"--\" as a decorative separator in output. Always-on background hook, no invocation needed. Trigger words: no-dashes, strip dashes, remove dash separators."
---

No-dashes rule is always active via UserPromptSubmit hook. No manual invocation needed.

Rule: Never use "--" as a decorative separator or visual divider. No standalone "--" lines between sections.

Exceptions: inside fenced code blocks, CLI flag syntax (--flag), inline code (`--`), markdown HR (---).
