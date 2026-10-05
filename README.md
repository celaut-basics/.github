# .github

Shared files of the celaut-basics organization.

- [prompts/audit-celaut-basics.md](prompts/audit-celaut-basics.md): prompt for an agent that audits, validates and judges all repos against the current nodo.

## How to run the audit prompt

Start the agent with Claude Opus (`claude --model opus`) and a high reasoning effort. Subagents for the validation and judgment phases must use Opus too. A weaker model gives a shallow review.
