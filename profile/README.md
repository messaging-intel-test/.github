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
