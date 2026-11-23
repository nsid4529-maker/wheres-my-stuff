# Other Verticals and White Space for "Portals As A Service" (as of Nov 23, 2026)

Scope: verticals beyond insurance and healthcare where US businesses depend on legacy web portals without APIs. The product being tested is computer-use agents that drive portals behind a REST API, priced per transaction. Every fact is dated. Facts from before 2025 are flagged **[pre-2025, possibly stale]**. Many search results came from aggregators or vendor blogs. Where only a weak source was available, that is noted.

---

## Q1. Candidate verticals compared on pain, volume, willingness to pay, competition and blocking/legal risk, with a recommended first vertical

### Takeaway
Freight and bank-data aggregation are already crowded or controlled by incumbents. Freight has a $1.2B AI-native unicorn plus several funded challengers. Bank data is dominated by Plaid and is now governed by bank-negotiated fees and an unsettled 1033 rule. The clearest white space for an *infrastructure* (API-first, per-transaction) entrant is **supplier/procurement portals on the accounts-receivable side**: submitting invoices and pulling payment status and remittance from Coupa, Ariba and buyer portals. The current competitors there are small, unfunded-or-undisclosed AR *applications*, not an API layer. A strong second option is **government/DMV title and permit portals**, where the jurisdictional long tail suits computer-use. That vertical already has a well-funded vertical app (PermitFlow) but no neutral API layer.

### Cited Findings

**Freight / logistics (carrier/broker portals, load boards)**
- HappyRobot closed a $150M Series C at a $1.2B post-money valuation on Aug 4, 2026. It was co-led by Prysm Capital and Eurazeo, with a16z, Base10 and YC participating. It has raised about $200M across three rounds in 20 months and reports 150+ customers, including 8 of the 10 largest US freight brokers, running its agents in production. — [FreightWaves](https://www.freightwaves.com/news/happyrobot-series-c-freighttech-unicorn); [The Next Web](https://thenextweb.com/news/happyrobot-150m-series-c-enterprise-ai-agents)
- HappyRobot's agents handle check calls, load updates, appointment scheduling, payment inquiries and rate negotiation. The company is expanding into telecom, energy utilities, oil and gas, and P&C insurance (Aug 2026). — [Supply Chain Digital](https://supplychaindigital.com/news/happyrobot-raises-150m-in-funding-to-grow-agent-deployment); [TechTimes](https://www.techtimes.com/articles/323024/20260804/happyrobot-raises-150m-enterprise-ai-agents-move-chat-operations.htm)
- Earlier HappyRobot rounds: a $15.6M Series A led by a16z and a $44M Series B. — [FreightWaves Series A](https://www.freightwaves.com/news/happyrobots-15-6m-raise-will-focus-on-product-development); [Inc/Reuters Series B](https://www.inc.com/reuters/happyrobot-raises-44-million-to-expand-ai-agents/91234965)
- Vooma raised $16.6M (a $13M Series A led by Craft Ventures and a $3.6M seed led by Index), announced Dec 2024 **[pre-2025, possibly stale]**. Vooma's AI agents work across email, calls, texts and portals inside a broker's TMS. — [BusinessWire](https://www.businesswire.com/news/home/20241202150186/en/Vooma-Scores-Over-$16-Million-in-Seed-and-Series-A-Funding-Led-by-Index-and-Craft-Ventures); [FreightWaves](https://www.freightwaves.com/news/vooma-grabs-16-6m-in-funding-as-brokers-prepare-for-market-swing)
- Pallet reportedly raised a $27M Series B led by General Catalyst in 2025, for about $50M total. The only source is a secondary competitive-landscape page. — [yespress](https://yespress.io/pallet/who-competes-with-pallet-mapping-the-freight-ai-automation-field)
- Parade raised a $17M round led by I Squared Capital, for $36M total. The date was not confirmed in results. — [FreightWaves](https://www.freightwaves.com/news/parade-secures-17m-from-i-squared-capital-for-ai-endeavors)
- Freight Hero raised a $5M seed led by Field Ventures (Jul 27, 2026). It charges **a flat fee per load** and takes over each shipment from rate confirmation through proof of delivery, working inside the broker's existing systems. — [PR Newswire](https://www.prnewswire.com/news-releases/freight-hero-lands-5m-to-prove-freight-brokerage-needs-fewer-tools-more-outcomes-302835207.html); [FreightWaves](https://www.freightwaves.com/?p=576926)
- Evos (NYC) announced a $9M pre-seed on Oct 14, 2026 for AI "operators" that audit carrier invoices and build loads. — [Forwarder News](https://www.forwardernews.com/news/2026-10-14-ai-agents-in-the-freight-back-office)
- A March 2026 BCG survey, as cited by Forwarder News, found that about 40% of logistics providers had deployed AI beyond pilots but only about 10% had scaled it across core operations. This is a secondary citation. — [Forwarder News](https://www.forwardernews.com/news/2026-10-14-ai-agents-in-the-freight-back-office)
- Uber Freight launched an AI logistics network with 30+ agents. The source is a low-quality listicle. — [Rework](https://resources.rework.com/tools/ai-tools/best-ai-tools-for-logistics-2026)

**Banking / fintech data access**
- The CFPB's 2024 Section 1033 open-banking rule is enjoined. An E.D. Kentucky court stayed its compliance deadlines and barred enforcement pending reconsideration. The April 1, 2026 first compliance date passed without binding effect (2026). — [Cozen O'Connor](https://www.cozen.com/news-resources/publications/2026/section-1033-compliance-date-open-banking-rule-enjoined-and-under-reconsideration); [Consumer Finance Monitor, Jun 26 2026](https://www.consumerfinancemonitor.com/2026/06/26/open-banking-regulation-in-2026-federal-regulation-resurfaces-as-states-bring-data-sharing-into-focus/)
- The CFPB sent a revised 1033 NPRM to OIRA on Aug 6, 2026. As of Oct 2026 it was reportedly still under OIRA review. Both claims come from secondary blogs. — [unboxfuture](https://www.unboxfuture.com/2026/08/cfpb-submits-revised-section-1033-open.html); [Bloom Credit](https://bloomcredit.io/blog/where-section-1033-actually-stands-a-plain-language-guide-for-financial-institutions/)
- JPMorgan signed updated data-access contracts with Plaid, Yodlee, Morningstar and Akoya, covering more than 95% of third-party data pulls on its systems. Final fees were lower than first proposed. The original schedule was estimated at up to $300M/yr for Plaid (Nov 14, 2025). — [CNBC](https://www.cnbc.com/2025/11/14/jpmorgan-chase-fintech-fees.html); [American Banker](https://www.americanbanker.com/news/jpmorganchase-reaches-deal-to-charge-plaid-for-customer-data)
- Plaid was valued at about $8B in a Feb 2026 employee share sale, up from $6.1B in Apr 2025 and below its $13.4B peak in 2021. Sacra estimates 2025 ARR at about $546M, up 40% year over year. Sacra reported Plaid weighing a US IPO as of Jul 2026. — [Sacra](https://sacra.com/research/plaid-at-546m-arr-growing-40-yoy/); [Fortune, Apr 2025](https://fortune.com/2025/04/03/fintech-plaid-funding-round-fidelity-blackrock-franklin-templeton-nea-perret/)

**Payroll / HR / benefits**
- Finch, a unified HRIS/payroll API, prices per connection, where each connected employer is one connection. The Starter plan is $65/month per connection for up to 15 connections and employers with fewer than 500 employees. The first 5 connections are free, and higher tiers are quote-based (2026). — [Finch pricing](https://tryfinch.com/pricing); [Merge analysis](https://www.merge.dev/blog/finch-api-pricing)
- Sacra listed Finch at a $250M valuation with $68M raised and 10,000+ employers connected **[2024, possibly stale]**. Finch's support page says 40,000+ employers have connected. — [Sacra](https://sacra.com/c/finch/); [Finch support](https://support.tryfinch.com/articles/5195481049-what-is-finch)
- Pinwheel, Argyle and Atomic (payroll connectivity / direct-deposit switching) don't publish pricing. The category norm is a per-connection or per-verification fee with minimums. Argyle sells per pull with volume discounts. — [fintechspecs](https://fintechspecs.com/blog/argyle-vs-pinwheel-income-employment-api-lenders/); [Sacra on deposit-switching APIs](https://sacra.com/p/direct-deposit-switching-apis-funding-neobanks/)
- Noyo's last disclosed round was a $45M Series B (May 2022, Norwest) **[pre-2025, possibly stale]**. It launched "BenefitsOS" in 2025. Ideon (formerly Vericred) has raised $44.7M–$58.8M according to aggregators, and in 2025 partnered with Ambient on automated ICHRA enrollment. No acquisition or 2025–26 round was found for either company. — [CB Insights Noyo](https://www.cbinsights.com/company/noyo); [CB Insights Ideon](https://www.cbinsights.com/company/vericred); [yespress Noyo](https://yespress.io/noyo)

**Utilities / energy data**
- Deck (Montreal) raised a $4.5M seed in Oct 2024 **[pre-2025]** and a $12M round led by Infinity Ventures in Apr 2025, for $16.5M total. It pitches "Plaid for the 95% of platforms that don't offer APIs," starting with utility portals. It **charges per successful API call**. — [TechCrunch, Apr 16 2025](https://techcrunch.com/2025/04/16/deck-raises-12m-to-plaid-ify-any-website-using-ai/); [FinSMEs](https://www.finsmes.com/2024/10/deck-raises-4-5m-in-seed-funding.html)
- Arcadia acquired the utility-data aggregator Urjanet in 2022 **[pre-2025]**. Other competitors include UtilityAPI ($10M Series A, ~2022) and Nectar, which positions itself as a modern Urjanet replacement. — [Axios](https://www.axios.com/pro/climate-deals/2022/05/24/arcadia-acquires-utility-data-provider-urjanet); [Nectar](https://nectarclimate.com/compare/urjanet)

**Government / permits / DMV-title**
- PermitFlow raised a $54M Series B led by Accel (Dec 2, 2025), with Kleiner Perkins, Felicis, Initialized and YC participating. Total raised is about $90M, with a reported valuation of about $500M (single source). It plans AI agents for permitting, inspections and license management. Named clients are Amazon, Ikea and Lennar. — [BusinessWire](https://www.businesswire.com/news/home/20251202551013/en); [Built In](https://builtin.com/articles/ai-construction-platform-permitflow-secures-54m-series-b-20251203)
- Polimorphic, which builds constituent-service and permit agents on the government side, has raised a reported $28M. Its last round was a Series A in May 2025 (aggregator source). — [zplatform](https://zplatform.ai/guides/ai-agent-startups-funding/)
- Verra Mobility, a public incumbent, launched an AI-driven title and registration product for fleets in Sep 2026. It claims activation is up to 80% faster. — [PR Newswire](https://www.prnewswire.com/news-releases/verra-mobility-launches-ai-driven-title--registration-solution-cutting-fleet-vehicle-activation-time-up-to-80-302867237.html)
- Fairway (AI title-packet auditing for DMVs, dealers and fleets, active in Texas and Kentucky) and Cario (an AI titling agent plus a dealer/lender/DMV network) are AI-native title players. No funding was found. — [Fairway](https://www.getfairway.com/solutions/dmv); [Cario](https://cario.com/ai-titling-agent/)

**Supplier / procurement portals (AR-side invoicing)**
- Tesorio markets AI agents that log into customer procurement portals (Coupa, Ariba) to submit invoices, track payments, download remittance and resolve disputes (2026). — [Tesorio](https://www.tesorio.com/product/supplier-portal)
- Invoice Butler (Coupa, Ariba, Tipalti and custom portals), Lunos (early access for its portal product) and LedgerUp (an AI billing agent for Coupa and Ariba submissions and rejections) offer the same capability. No funding was found for any of them. — [Invoice Butler](https://www.invoicebutler.com/blog/ar-automation-tools-customer-payment-portals); [Lunos](https://www.lunos.ai/blog/coupa-supplier-portal-invoice-submission); [LedgerUp](https://www.ledgerup.ai/)
- Coupa's supplier portal is free for suppliers. SAP Ariba charges suppliers to invoice through its network. Both enforce PO matching and strict field and line-item formatting before they accept an invoice. — [Transalis](https://www.transalis.com/blogs/supplier-portal-invoicing)

### Inferences
- **Scorecard (qualitative, my synthesis of the findings above):**

| Vertical | Pain | Txn volume | WTP | Competition | Block/legal risk | Fit for API-layer entrant |
|---|---|---|---|---|---|---|
| Freight/logistics | High | Very high | Proven (per-load pricing exists) | **Saturated**: HappyRobot ($1.2B), Vooma, Pallet, Parade, Freight Hero, Evos, Uber Freight | Medium (load boards/TMS have ToS) | Low: buyers want outcome agents, not an API |
| Bank data | High | Very high | Proven | **Locked**: Plaid/Yodlee/Akoya plus bank fee contracts | High, and moving toward APIs and fees | Very low |
| Payroll/HRIS/benefits | Med-high | High | Proven ($65/connection/mo Finch) | Crowded: Finch, Pinwheel, Argyle, Atomic, Noyo, Ideon | Medium | Low-medium |
| Utilities | Medium | Medium | Proven (Deck pays per success) | Moderate: Deck, Arcadia, UtilityAPI | Low-medium | Medium, but Deck is already a horizontal analog |
| Gov/permits/DMV | High | Medium per jurisdiction, huge long tail | Proven by PermitFlow raise | Vertical apps funded; **no neutral API layer seen** | Low (public sites; user-authorized filings) | **Medium-high** |
| Supplier/AR portals | High (DSO, rejected invoices) | Very high (every B2B invoice to enterprise buyers) | Clear ROI (cash collection) | Several small AR apps; **no infra/API layer seen** | Low-medium (the supplier uses its own credentials on a buyer-provided portal) | **High** |

- **Recommendation: start with supplier/procurement portals** (Coupa, Ariba, Jaggaer, Tungsten and the long tail of buyer portals). Sell an "invoice-submit / status / remittance" REST API to AR-automation vendors, ERPs, billing platforms (e.g., Stripe-billing-like tools) and fintech factoring/lenders. The reasons: (a) the existing players are applications that each rebuild portal bots, so they are potential customers rather than competitors; (b) the account owner is the supplier acting on its own account, which lowers CFAA/ToS exposure relative to bank scraping; (c) per-invoice pricing maps naturally onto per-transaction pricing; (d) no funded API-first incumbent appeared in searches. The main risk is that Tesorio or a well-funded AR player builds this as a platform, and that Coupa or SAP offer native supplier APIs or charge for access.
- **Second choice: government/DMV/permit portals** as an API for dealers, fleets, lenders and construction software. The thousands of county and state portals are the long tail where generic computer-use beats hand-built integrations. Watch whether PermitFlow and Verra Mobility will become customers or competitors.
- Freight confirms demand and willingness to pay per transaction (Freight Hero's per-load fee), but HappyRobot's scale makes it a poor beachhead. Freight is better addressed later as a supplier of portal actions (port/terminal appointment portals, carrier-onboarding portals) to those agent companies.
- Deck is the closest horizontal precedent to "Portals As A Service" (per-successful-call pricing, "Plaid for sites without APIs"). The new entrant should study Deck's go-to-market and differentiate by vertical depth.

### Gaps
- No funding data found for Tesorio's portal product, Invoice Butler, Lunos, LedgerUp, Fairway or Cario.
- No reliable transaction-volume counts per vertical (e.g., number of invoices submitted via Coupa/Ariba portals, annual DMV title transactions). Volume ratings above are qualitative.
- Port/terminal portal automation players and court e-filing / county-records automation were not researched due to tool-call limits.
- Property management / MLS, telecom and tax-agency portals were not researched. No findings.
- Pallet's 2025 round and Parade's round date are from secondary sources only.

---

## Q2. AI-native and incumbent competitors per vertical: funding, pricing, saturation

### Takeaway
Capital has flowed heaviest into freight (HappyRobot, about $200M) and construction permitting (PermitFlow, about $90M). Horizontal browser-agent infrastructure (Browserbase, Skyvern) sits below all verticals as an enabler, not a competitor. Supplier portals and DMV/title have AI-native entrants with no disclosed funding, which signals early-stage, unsaturated markets.

### Cited Findings
- Freight: see Q1 (HappyRobot $150M Series C at $1.2B, Aug 2026; Vooma $16.6M, Dec 2024; Pallet ~$27M Series B, 2025; Parade $17M; Freight Hero $5M seed, Jul 2026; Evos $9M pre-seed, Oct 2026). — [FreightWaves](https://www.freightwaves.com/news/happyrobot-series-c-freighttech-unicorn); [Forwarder News](https://www.forwardernews.com/news/2026-10-14-ai-agents-in-the-freight-back-office)
- Pricing signal in freight: Freight Hero charges a flat fee per load (Jul 2026). — [PR Newswire](https://www.prnewswire.com/news-releases/freight-hero-lands-5m-to-prove-freight-brokerage-needs-fewer-tools-more-outcomes-302835207.html)
- Horizontal infrastructure: Browserbase raised a $40M Series B led by Notable Capital in Jun 2025 at a $300M post-money valuation. Skyvern is seed-stage with conflicting totals ($2.7M–$4.5M). — [respan.ai comparison](https://www.respan.ai/market-map/compare/browserbase-vs-skyvern); [startupfundraising.com](https://startupfundraising.com/browser-agents-rpa-fundraising)
- One tracker estimates AI-agent startup funding at $2.4B (2024), $6.6B (2025) and $13.6B in the first nine months of 2026. It is an aggregator, and totals conflict across sources. — [aifunding.me](https://aifunding.me/ai-agent-funding)
- Utilities: Deck $16.5M total (Apr 2025), with per-successful-call pricing. — [TechCrunch](https://techcrunch.com/2025/04/16/deck-raises-12m-to-plaid-ify-any-website-using-ai/)
- HR/benefits: Finch at $65/connection/mo (2026); Noyo $45M Series B (2022); Ideon $44.7M–$58.8M. — [Finch](https://tryfinch.com/pricing); [CB Insights](https://www.cbinsights.com/company/noyo)
- Government: PermitFlow $54M Series B (Dec 2025); Polimorphic about $28M (May 2025); Verra Mobility as incumbent (Sep 2026). — [BusinessWire](https://www.businesswire.com/news/home/20251202551013/en); [PR Newswire](https://www.prnewswire.com/news-releases/verra-mobility-launches-ai-driven-title--registration-solution-cutting-fleet-vehicle-activation-time-up-to-80-302867237.html)

### Inferences
- Saturation ranking, most to least saturated: bank data > freight > payroll/HRIS > benefits > utilities > permits (app layer funded, API layer open) > DMV/title > supplier/AR portals.
- HappyRobot's expansion into utilities, telecom and P&C insurance means a well-funded horizontal-ish agent company may enter adjacent verticals within 12–18 months. A vertical API entrant should pick a domain where voice/email agents add less value than portal transactions. AR portals fit this.

### Gaps
- No 2025–2026 funding found for Pinwheel, Argyle or Atomic, and no layoff or acquisition news found for them.
- No funding information found for Anon or Simular (computer-use/auth infrastructure).

---

## Q3. Business-model lessons from "API for systems without APIs" precedents (Plaid, Noyo, Ideon, Pinwheel/Argyle/Atomic, Finch, Zapier)

### Takeaway
The precedents grew by charging per connection or per successful call. Over time, the systems they scraped either became paying partners via formal APIs (Plaid moved to bank API agreements and now pays JPMorgan fees) or remained file/EDI integrations (Noyo, Ideon). The durable end state is a negotiated, sanctioned data pipe, and the scraping phase is a bridge. Expect counterparties to monetize access once volume is visible.

### Cited Findings
- Plaid's arc: valuation peaked at $13.4B (2021), fell to $6.1B (Apr 2025), and recovered to about $8B (Feb 2026). Estimated ARR is about $546M (2025, +40% y/y), and it is weighing an IPO as of Jul 2026. — [Sacra](https://sacra.com/research/plaid-at-546m-arr-growing-40-yoy/)
- Once at scale, the data source charged the aggregator. JPMorgan secured fee contracts covering more than 95% of third-party data pulls (Plaid, Yodlee, Morningstar, Akoya; Nov 2025). The original fee proposal was estimated at up to $300M/yr for Plaid. — [CNBC](https://www.cnbc.com/2025/11/14/jpmorgan-chase-fintech-fees.html)
- Regulation pushes from scraping toward APIs. The 1033 rule (enjoined, being rewritten as of 2026) was designed to move the market to permissioned API access, and reporting says the revision keeps that direction. — [Cozen O'Connor](https://www.cozen.com/news-resources/publications/2026/section-1033-compliance-date-open-banking-rule-enjoined-and-under-reconsideration); [Bloom Credit](https://bloomcredit.io/blog/where-section-1033-actually-stands-a-plain-language-guide-for-financial-institutions/)
- Noyo and Ideon sell "one API into the insurance carriers instead of a file feed per carrier." Noyo built a two-sided marketplace between benefits software and carriers. — [hrmony](https://embedded.hrmony.de/en/blog/embedded-finance-companies); [Founder-led sales stories](https://founderledsalesstories.substack.com/p/from-pdfs-to-apis-how-noyo-built)
- Finch: per-connection pricing ($65/mo Starter, first 5 free, 2026); 40,000+ employers connected per its own support page. — [Finch](https://tryfinch.com/pricing); [Finch support](https://support.tryfinch.com/articles/5195481049-what-is-finch)
- Payroll connectivity players (Pinwheel, Argyle, Atomic) use per-connection or per-verification pricing with monthly minimums, and don't publish pricing. — [fintechspecs](https://fintechspecs.com/blog/argyle-vs-pinwheel-income-employment-api-lenders/)
- Deck charges only for successful API calls (Apr 2025). — [TechCrunch](https://techcrunch.com/2025/04/16/deck-raises-12m-to-plaid-ify-any-website-using-ai/)

### Inferences
- Pricing: per-successful-transaction (Deck) and per-connection-per-month (Finch) are both market-tested. A hybrid, with a per-connected-account platform fee plus per-transaction charges and minimums, matches how Plaid-era buyers budget.
- Plan for the "JPMorgan moment": once the business carries meaningful volume through Coupa or Ariba, expect those platforms to either ship supplier APIs or charge for access. The strategic goal is to become the sanctioned partner (Plaid → bank API agreements; Noyo → carrier integrations), not to scrape forever.
- Two-sided network effects (Noyo, Plaid) came from aggregating many counterparties behind one normalized schema. The normalized data model for invoices, status and remittance across portals is the defensible asset, not the browser automation.

### Gaps
- Zapier's pricing and growth history was not researched (tool-call limit).
- No sourced details on Pinwheel, Argyle or Atomic being blocked by payroll providers (e.g., ADP), or on any of them becoming a standard.
- Noyo and Ideon revenue and pricing were not found.

---

## Q4. Legal/ToS risk (CFAA, hiQ v. LinkedIn aftermath, credential sharing) and defensibility as computer-use gets cheap

### Takeaway
The most important 2026 legal development is the Ninth Circuit's Aug 4, 2026 decision in *Amazon v. Perplexity*. It vacated Amazon's preliminary injunction and found that, on that record, the *user*, not the agent developer, is the party "accessing" the site under CFAA/CDAFA. That is favorable to user-directed, credentialed portal agents. The court limited it to its facts, and ToS/contract claims remain open. Defensibility will not come from the browser-driving itself, which is commoditizing. It will come from reliability/SLA, normalized schemas, compliance posture and sanctioned partnerships.

### Cited Findings
- The district court (Judge Maxine Chesney, N.D. Cal.) granted Amazon a preliminary injunction against Perplexity's Comet shopping agent in March 2026. It found Comet accessed Amazon "without authorization." — [CNBC, Mar 10 2026](https://www.cnbc.com/2026/03/10/amazon-wins-court-order-to-block-perplexitys-ai-shopping-agent.html); [GeekWire](https://www.geekwire.com/2026/judge-blocks-perplexitys-ai-bot-from-shopping-on-amazon-in-early-test-of-agentic-commerce/)
- The Ninth Circuit vacated the injunction (Aug 2026). It held Amazon unlikely to succeed on the CFAA/CDAFA access element because the human user, not the AI-agent developer, accesses the computers. It said the ruling is limited to the record and does not set broad principles for agentic AI. — [Troutman Pepper privacy blog, Aug 2026](https://www.troutmanprivacy.com/2026/08/ninth-circuit-holds-human-user-not-developer-of-ai-agent-responsible-for-websites-accessed/); [MediaPost](https://www.mediapost.com/publications/article/417007/appeals-court-sides-against-amazon-lifts-perplexi.html)
- Commentators note that Amazon can still regulate access under its private terms of service, and that the case continues on an amended complaint. — [ppc.land](https://ppc.land/amazon-loses-injunction-blocking-perplexitys-ai-shopping-agent/); [cryptobriefing](https://cryptobriefing.com/perplexity-amazon-lawsuit-comet-ai-agent/)
- Open banking shows a regulatory route to sanctioned access, and also its uncertainty. The 1033 rule is enjoined but still in the CFR. State AGs might argue independent enforcement authority, and New York has introduced open-banking bills (2026). — [Consumer Finance Monitor, Jun 2026](https://www.consumerfinancemonitor.com/2026/06/26/open-banking-regulation-in-2026-federal-regulation-resurfaces-as-states-bring-data-sharing-into-focus/)
- On commoditization: compute and model token prices have fallen sharply (H100 rental down about 64–75% from late 2024 to early 2026, per a blog). Commentary warns that "thin wrappers around generic APIs" face low-margin, indefensible positions. Both are opinion or low-quality sources. — [buildmvpfast](https://www.buildmvpfast.com/blog/ai-moat-compute-access-data-governance-2026); [thinkia](https://thinkia.com/thoughts/enterprise-ai-strategy-the-new-moat-beyond-the-api/)

### Inferences
- Lowest-risk legal posture: the customer's own end user or business (e.g., the supplier) provides credentials and directs each transaction. This mirrors the user-as-accessor reasoning in *Amazon v. Perplexity*. The setup should also avoid circumventing technical blocks such as CAPTCHAs or IP bans after a cease-and-desist, and keep audit logs. Supplier portals and government filings fit this model better than bank scraping or load-board data harvesting. Load-board data harvesting means pulling third-party data that the platform monetizes.
- Contract/ToS breach remains the live risk even if CFAA risk falls. Portal operators can terminate accounts, so per-customer account isolation and fast re-auth flows matter.
- Moat once computer-use is cheap: (1) a normalized cross-portal schema and an idempotent transaction semantics (retries, confirmations, receipts); (2) a coverage-and-maintenance flywheel, meaning a library of portal "skills" with monitoring and self-healing; (3) SOC 2, credential vaulting and auditability for enterprises; (4) graduating to official partnerships with portal owners. Plain "an LLM clicks the buttons" will be replicable by frontier-model vendors and browser-infra companies.

### Gaps
- **hiQ v. LinkedIn aftermath was not sourced in this session.** Background knowledge, unverified here: after the 2022 Ninth Circuit ruling narrowed CFAA for public data, hiQ lost on breach-of-contract/ToS grounds and settled in late 2022. The report writer should verify this before relying on it **[pre-2025]**.
- No sourced analysis found on credential-sharing liability specifically, such as ToS clauses that forbid sharing logins with third parties in Coupa, Ariba or state DMV portals.
- No source found on whether Coupa or SAP Ariba ToS prohibit automated or bot access by suppliers. This should be checked before committing to the vertical.
