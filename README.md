# Russian DC Observatory

Internet incidents, provider announcements and website-access measurements answer different questions. Russian DC Observatory brings them into one research workspace while keeping their sources and uncertainty visible. It helps users compare evidence about Russian Internet connectivity, named services and infrastructure without treating every complaint or missing observation as proof of an outage.

## Tech stack

| Layer | Technologies |
|---|---|
| Application | Python; SQLite |
| Dashboard | JavaScript; HTML; CSS; SVG |
| Companion administration | WordPress; PHP |

## Start with the evidence available

The overview brings service observations, network incidents, traffic context and source freshness together. It provides a starting point for deciding which observation deserves closer attention. Unknown and stale information remains distinguishable from healthy or failed observations, so gaps do not quietly become conclusions.

## Follow providers, services and maintenance

The Services view groups provider-reported components, incident references and scheduled maintenance. Named-service complaint reports add a separate perspective rather than replacing official evidence. Source dates and available regional context help users see what each report actually covers.

Incidents can be filtered by their reported state, including active, recovered, unconfirmed and scheduled observations. The distinction helps separate a current source report from maintenance or an event without a confirmed outcome.

## Investigate website access and remote observations

The Access view presents website-access measurement samples and their coverage. Category counts, domain subsets and network context help users interpret the available observations. A sample percentage describes those measurements rather than the whole population.

The Remote view separates HTTP responses, DNS timing, TLS information and observation age for the configured sites. It supports comparing the evidence available from a particular observation point. A redirect or restricted response does not automatically mean that the underlying service is down.

## Compare infrastructure and network context

Facility and map views make the infrastructure catalogue easier to explore geographically. Network inventory, existing measurement anchors and latency observations provide additional context. The Compare view brings selected facility metadata and evidence together without inventing a ranking of unknown availability.

Traffic views offer another source-specific signal. Keeping traffic, access samples and provider reports distinct helps users examine whether observations agree without compressing them into an unexplained health score.

## Watch relevant changes

Watchlists let users focus on the sites and provider components they care about. The in-app change feed helps revisit meaningful accepted changes to watched evidence. Watching an item does not start new checks, and notifications stay inside the application.

## Keep the workspace readable

Source and health views expose freshness, errors, empty results and disabled sources. Evidence details retain context for closer inspection. Collapsible navigation, a narrow-screen drawer and appearance preferences help make a dense research workspace easier to use over longer sessions.

## Use the observations in context

The current product is a personal, non-commercial research workspace. Coverage depends on the available sources and configured observations; facility catalogue membership alone does not establish service availability. Source licensing determines how observations may be shared or reused, including any public or commercial use.

---

Private project components: [monitor](https://github.com/logicencoder/russian-dc-observatory-monitor) and [companion WordPress component](https://github.com/logicencoder/russian-dc-observatory-plugin).

See [REPOS.md](REPOS.md) for the related repositories.

**[Logic Encoder](https://logicencoder.com)** · [GitHub](https://github.com/logicencoder) · [Contact](https://logicencoder.com/contact/)
