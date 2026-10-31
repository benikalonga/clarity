# Upstream / Attribution

This repository is a copy of **[SchroederNathan/clarity](https://github.com/SchroederNathan/clarity)**.

- Original repository: https://github.com/SchroederNathan/clarity
- Copied from branch `main` at commit [`297e699ea039`](https://github.com/SchroederNathan/clarity/commit/297e699ea03902d4f3172aa7b1f3ddbc2ef8900c) on 2026-10-31
- License: MIT. The original [LICENSE](./LICENSE) file is kept unchanged. All copyright belongs to the original authors.
- Full git history and original commit authorship are preserved.

Please send issues and contributions to the original project.

## Changes from the original

- Secrets, API keys, account IDs and personal data (emails, phone numbers, names) were replaced with placeholders such as `your_email@fakeemail.com`, `0810000000`, `YOUR_NAME` and `00000000-0000-0000-0000-000000000000`, across the whole git history.
- Personal email addresses in commit metadata were replaced with GitHub no-reply addresses or a placeholder. Author names are kept.
- AI agent configuration files (`.claude/`, `.agents/`, `.codex/`, `AGENTS.md`, `CLAUDE.md`, `.mcp.json`) were removed.
- All code comments, UI strings and documentation were translated to English. Non-English text that the code must match at runtime (for example server messages or test data for charset decoding) is kept as `\uXXXX` escapes with an English comment.
- Screenshots, generated output folders and machine-specific scripts were removed, along with README references to them.
- Automation was removed to keep this a plain source repository: CI/CD workflows (GitHub Actions, EAS workflows, Dependabot), helper/build/release scripts, editor and agent tool configs, and package.json scripts that pointed at removed files. Test suites are kept.
- The original LICENSE and its copyright notice are unchanged.
