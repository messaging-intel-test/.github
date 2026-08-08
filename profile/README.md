# messaging-intel-test

Independent acceptance organization for **messaging-intel**.

Read-only connectors, SDK/API, privacy, analytics, scheduled profiles, browser extension, and Flutter certification.

## Portfolio

| Repository | Class | Readiness | Primary dependency path |
|---|---|---|---|
| `clients-consumer-matrix` | SDK consumer | `ready` | `matrix` |
| `whatsapp-web-connector` | provider adapter | `ready` | `matrix` |
| `instagram-messenger-connectors` | provider adapter | `ready` | `matrix` |
| `tinder-badoo-connectors` | provider adapter | `ready` | `matrix` |
| `cupid-sites-connectors` | provider adapter | `ready` | `matrix` |
| `scheduled-profile-rotation` | scheduler/failover | `ready` | `matrix` |
| `privacy-redaction` | security | `ready` | `matrix` |
| `analytics-pipeline` | performance/scale | `ready` | `matrix` |
| `browser-extension-flutter-e2e` | UI/accessibility | `ready` | `matrix` |

Pull requests run deterministic harness checks. Emulators, desktop matrices, live APIs/providers, databases, chaos, scale, and soaks are scheduled/manual. Missing upstreams or credentials are blocked readiness—not false passes or product regressions.

<!-- org-project-routing:start -->
## Planning and delivery

- [GitHub Project: messaging-intel-test-project](https://github.com/orgs/messaging-intel-test/projects/1)
- [Linear planning project](https://linear.app/denman/project/githubcommessaging-intel-test-2c47a9893ffe)
- [Detailed project-routing contract](../docs/PROJECTS.md)

GitHub owns code and delivery evidence; Linear owns planning and dependencies. The linked organization Project provides the cross-repository execution view.
<!-- org-project-routing:end -->


<!-- ore-org-baseline:begin -->
## Planning and governance

- Canonical Linear project: https://linear.app/denman/project/githubcommessaging-intel-test-2c47a9893ffe
- Organization defaults: https://github.com/messaging-intel-test/.github
- Canonical agent policy: https://github.com/messaging-intel-test/.github/blob/main/agents.md
- Security policy: https://github.com/messaging-intel-test/.github/security/policy

Repositories in this organization use semantic conflict resolution with 3–10 relevant prior commits when useful, full cross-repository context, pull-request delivery, and a hard automated-agent denylist for destructive or history-rewriting operations.
<!-- ore-org-baseline:end -->
