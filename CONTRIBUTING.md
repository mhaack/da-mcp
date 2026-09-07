# Contributing to da-mcp

Thanks for contributing! Please open an issue before starting significant work, fork the repo, make your changes on a branch, and open a pull request that references the issue it addresses.

# Issue and PR Housekeeping Automation

To keep the backlog healthy, this repo runs a few GitHub Actions bots. Here is what to expect.

## Filing an issue

Issues are created through issue forms (blank issues are disabled). A few fields are **required** and power automatic triage:

- **Scope / Area** — applies a `scope:*` label and **auto-assigns** the area owner(s):

  | Scope / Area | Auto-assigned |
  | --- | --- |
  | Editor / Canvas | @svynod, @hannesolo |
  | Blocks / Rendering | @svynod, @hannesolo, @mhaack |
  | Heli | @mhaack, @hannesolo |
  | Config / Sheets | @mhaack, @hannesolo, @anfibiacreativa |
  | Auth / Permissions | @mhaack, @hannesolo, @anfibiacreativa |
  | AI Assistant / Agent | @anfibiacreativa, @mhaack |
  | MCP / Tooling | @anfibiacreativa |
  | Infra / CI | @mhaack, @hannesolo, @anfibiacreativa |
  | Docs | whole team |
  | Other / Unsure | whole team |

- **Customer request or developer need?** and **Priority (P0–P3)** — required so we can rank work.
- For **bugs**: a description, **steps to reproduce**, and a **reproduction link**. A short **video is optional** but appreciated.

### Completeness check

When an issue is opened or edited, a bot verifies the required information is present. If anything is missing it applies the `triage-incomplete` label and leaves a comment (tagging you) listing exactly what to add. The comment and label clear automatically once the issue is complete, so just edit the description — no need to open a new issue.

## Pull request notifications

When a PR is opened, marked ready for review, or reopened, a short notice is posted to Slack. PRs from the **core team** and from **outside contributors** are routed to separate channels so nothing slips through.

## Stale issues and PRs (auto-close)

Inactive items are closed automatically after a warning period. **Any activity** — a comment, a new commit, or removing the `stale` label — resets the clock.

| Type | Marked `stale` after | Closed after the warning |
| --- | --- | --- |
| Issues | 60 days (2 months) of inactivity | 21 days (3 weeks) later |
| Pull requests | 49 days (7 weeks) of inactivity | 14 days (2 weeks) later |

When an item goes stale the bot comments so you are notified with time to act. To keep something open, comment on it or remove the `stale` label. Items labeled `pinned`, `security`, `keep-open`, or assigned to a milestone are never auto-closed.
