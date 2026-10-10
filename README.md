# accounting-finance-stocks-wfbholding

> Personal accounting tax preparation and investment tracking

Part of the WFB Holding portfolio.

---

## Subcategories

- [ ] Business Accounting
- [ ] Checkbook Programs
- [ ] Personal/Household Accounting
- [ ] Programs for Saving Money
- [ ] Stock Tracking and Investment Tools
- [ ] Tax Programs

## What lives here

- Business Accounting
- Checkbook Programs
- Personal/Household Accounting
- Programs for Saving Money
- Stock Tracking and Investment Tools
- Tax Programs

## What to expect

- **The taxonomy above is the boundary.** Repos map to these buckets. If
  something does not fit one of them, it belongs in a sibling org.
- **Ledger arithmetic is decimal-exact and never uses floating point. Rounding is specified per currency.**
- **Stability tiers used across this org.**
  - `stable` — semver, documented, tested, supported.
  - `experimental` — works, may break without a major version bump.
  - `archived` — superseded. Read-only, with a pointer to the replacement.
- **Support is best-effort.** These are open-source projects. There is no SLA,
  no guaranteed response time, and no contractual support commitment.
- **Releases are continuous, not scheduled.** Semver is honoured for `stable`
  repos.
- **Licensing is permissive by default.** A copyleft or source-available
  exception is deliberate and recorded per repo in `LICENSE` and `NOTICE`.
- **Vulnerability reports go to security, not issues.**

## What does *not* live here

| Belongs to | Goes to |
| --- | --- |
| `tax-calc` | `office-business-writing-wfbholding` |
| `statement-importer` | `file-folder-tools-wfbholding` |
| `brokerage-feeds` | `networking-port-forwarding-wfbholding` |

## Repo naming

The org name carries the category, so repo names do not repeat it. Each repo
maps to one subcategory bucket.

```
good:  accounting-finance-stocks-wfbholding/business-accounting
bad:   accounting-finance-stocks-wfbholding/accounting-finance-stocks-wfbholding-business-accounting
```

Pattern: `<subsystem>` in lowercase, hyphenated, no category prefix, no version
numbers, no abbreviations that are not obvious outside the team.

## Support

- **Questions and ideas:** GitHub Discussions, not issues.
- **Bugs:** issues, with a minimal reproduction.
- **Security:** see `SECURITY.md` in the repo. Never a public issue.

## License

Per-repo, stated in that repo. Default is Apache-2.0. Contact the org owner
before relicensing.

---

<sub>Maintained by WFB Holding. Questions about scope or boundaries go to org
Discussions.</sub>
