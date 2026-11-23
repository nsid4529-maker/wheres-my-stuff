# Insurance Vertical: Competition for "Portals As A Service" (US agencies, MGAs, wholesalers, brokers), as of Nov 2026

Method note: In this session WebFetch was blocked for every domain tried (covera-agents.com, ycombinator.com, skyvern.com). All findings come from WebSearch result summaries, not full-page reads, so check key numbers at the source before using them. Many "comparison" pages are written by competitors (QuoteSweep, Sonant, Selectsys, InsureAssistAI), so their claims about rivals may be biased. Dates are given where known. Anything from before 2025 is marked [possibly stale].

## Incumbents: comparative raters and connectivity. What they cover, which lines, and where real-time carrier connectivity is missing

### Takeaway
Applied Systems now owns much of the connectivity stack: Ivans, EZLynx, Tarmika, Indio, and Cytora (acquired Sept 2025). Personal-lines comparative rating is mature (EZLynx, Vertafore PL Rating, Zywave TurboRater). Small-commercial real-time quoting reaches only about 30–60 carriers per platform (Tarmika, Semsee, Bold Penguin, CoverForce), usually just for BOP/GL/WC. E&S, mid-market, endorsements, claims status, and most servicing still run through individual carrier portals, email, or PDFs. That is the gap.

### Cited Findings
**Applied Systems / Ivans / EZLynx / Tarmika / Indio**
- Applied completed its acquisition of EZLynx on 9 Mar 2021 [possibly stale]. EZLynx is now Applied's flagship standalone personal-lines rater — [InsuranceSoftwareHub EZLynx review 2026](https://insurancesoftwarehub.com/vendors/ezlynx/); [QuoteSweep AMS comparison 2026](https://www.quotesweep.com/blog/ams-comparison-2026)
- Tarmika, a small-commercial comparative rater, is described as acquired by Applied in Aug 2022 [possibly stale]. Integrations named: Applied Epic, EZLynx, Better Agency, AgencyZoom, Neon. It connects to carriers via Ivans — [InsuranceSoftwareHub Tarmika review 2026](https://insurancesoftwarehub.com/vendors/tarmika/)
- Tarmika's carrier count differs by source: ~31 carriers via API ([QuoteSweep 2026 comparison](https://www.quotesweep.com/blog/commercial-insurance-quoting-tools-compared)), 35+ markets per Applied materials ([QuoteSweep buyer's guide, Apr 2026](https://www.quotesweep.com/blog/commercial-insurance-quoting-software-buyers-guide-2026)), and 40+ in a third summary — [BrokerageAudit 2026](https://brokerageaudit.com/blog/best-comparative-raters-2026). There is no independent, verified count.
- "Applied Rater" (formerly IVANS Rate) is Applied's other personal-lines rating product — [AdviceScout / comparison blogs 2026](https://advicescout.com/7-best-insurance-rating-applications-ranked-by-verified-carrier/)
- Applied acquired Cytora, an AI submission/risk-digitization company, in Sept 2025 — [FurtherAI blog 2026](https://www.furtherai.com/blog/ai-tools-for-commercial-insurance-underwriting)
- Applied claims (vendor marketing) that renewal quote requests come back inside Epic within 3 hours instead of 3+ days. Its original launch release claimed extracting carrier data into Epic would cut data entry by more than 50% — [Insurance Business, 2026](https://www.insurancebusinessmag.com/us/news/technology/applied-puts-numbers-on-ai-platform-for-independent-agencies-591874.aspx)
- Applied launched a "submissionless renewal" experience with Travelers (carrier-specific, bilateral integration) — [Insurance Business](https://www.insurancebusinessmag.com/us/news/technology/applied-systems-launches-submissionless-renewal-experience-with-travelers-581797.aspx); [IA Magazine](https://www.iamagazine.com/?p=33849) (date not confirmed in snippet)
- Teardown describes Indio as an Applied-linked tool that digitizes the client-facing application. It is adjacent to carrier connectivity, not a portal-automation competitor — [Teardown CoverForce profile](https://www.teardown.ai/companies/coverforce)

**Vertafore**
- Vertafore PL Rating reportedly lists 300+ carriers and connects to AMS360, Sagitta, QQCatalyst, and 20+ other management systems — [comparison blogs 2026, via search summary](https://www.quotesweep.com/blog/vertafore-vs-ezlynx)
- Vertafore also sells a commercial submissions product for carriers — [Vertafore data sheet](https://www.vertafore.com/sites/default/files/documents/Commercial%20Submissions%20for%20Carriers%20Data%20Sheet.pdf) (undated)

**Ivans connectivity research (2026)**
- Ivans 2026 Connectivity Survey: 702 independent agents, fielded Apr–May 2026. Re-keying is the top workflow pain point for 74%. 90% have reduced business with a carrier because of friction. Other friction points: inconsistent underwriting questions (42%), slow portals (38%), multiple logins (37%) — [Risk & Insurance](https://riskandinsurance.com/re-keying-and-workflow-friction-are-costing-carriers-placement-ivans-survey-finds/); [Insurance Business](https://www.insurancebusinessmag.com/us/news/technology/submission-friction-now-beats-price-in-where-agents-place-business-ivans-finds-587645.aspx); [Ivans 2026 Carrier-Agency Connection Report](https://www.ivans.com/resources/reports-research/unlock-the-latest-agency-carrier-connectivity-trends/); [Insurtech Analyst, 26 Aug 2026](https://insurtechanalyst.com/2026/08/26/agents-rank-automation-above-price-ivans-survey-finds/)
- Agents writing more than 75% commercial lines report re-keying data more than 70% of the time, versus 62% overall — [IndependentAgent.com "Submission Black Hole"](https://www.independentagent.com/news/the-submission-black-hole-every-agent-knows/)

**Bold Penguin, Semsee, CoverForce, Zywave, Appulate**
- Bold Penguin works as an exchange (routes submissions to carrier partners) and also offers Terminal, a comparative rater for standard commercial lines. It is reported at 45+ carriers, owned by American Family, and Terminal is free to start — [QuoteSweep "Bold Penguin alternative"](https://www.quotesweep.com/blog/bold-penguin-alternative) (competitor source)
- Semsee: ~48 carriers via API plus limited RPA. A CEO post claims "over 50 carriers with hundreds of products." Pricing runs from a free Essential tier to $50/user/month Professional. An iBynd affiliate announced its acquisition of Semsee on 24 Mar 2026 — [QuoteSweep comparison](https://www.quotesweep.com/blog/semsee-vs-tarmika-vs-quotesweep); [InsuranceSoftwareHub Semsee 2026](https://insurancesoftwarehub.com/vendors/semsee/)
- CoverForce raised a $13M Series A led by Insight Partners on 5 Mar 2025, with Nyca participating. Total raised is about $18M. In Sept 2026 it launched a Startup Program giving new brokerages access to its 60+ carrier integrations. Oct 2026 coverage describes a single API for real-time quote/bind across 60+ carriers — [Insight Partners](https://www.insightpartners.com/ideas/coverforce-secures-13-million-in-series-a-funding-led-by-insight-partners-to-build-infrastructure-and-connectivity-between-insurance-carriers-and-agencies/); [FinTech Global, 7 Oct 2026](https://fintech.global/2026/10/07/coverforce-aims-to-cut-insurance-brokerage-launch-times/); [PR Newswire](https://www.prnewswire.com/news-releases/coverforce-launches-startup-program-enabling-any-company-to-launch-a-digital-brokerage-in-days-302878521.html); [Teardown](https://www.teardown.ai/companies/coverforce)
- CoverForce publishes a carrier integration map. Partner releases name Liberty Mutual, Chubb, Nationwide, and Travelers, plus a NowCerts quote-and-bind partnership — [CoverForce API index](https://coverforce.com/carriers/api-index); [CoverForce–NowCerts](https://coverforce.com/blog/coverforce-partners-with-nowcerts-to-launch-instant-quoting-and-binding-experience)
- Zywave Fall 2026 Launch (5 Nov 2026) added 19 home/auto carriers across 18 states via TurboRater and its Personal Lines Quoting API, and one commercial carrier on MGA Hub — [Webull/press release](https://www.webull.com/news/15872481100588032)
- Appulate: no 2025–2026 coverage turned up in searches (gap).

**Carrier APIs**
- Travelers (Oct 2026) launched an AI workers' comp quoting tool inside its Travis agent portal. Agents upload ACORD apps and get a bindable small-business WC quote in "half the time." This is a portal feature, not a public API — [Insurtech Insights](https://www.insurtechinsights.com/?p=7077); [BusinessWire via FinancialContent, 28 Oct 2026](https://www.financialcontent.com/article/bizwire-2026-10-28-travelers-introduces-ai-powered-quoting-tool-for-workers-compensation)
- The Hartford expanded submission/quote APIs in 2023 for midsize and large business, not small commercial [possibly stale] — [Insurance Journal 2023](https://www.insurancejournal.com/news/national/2023/09/18/740508.htm)
- An MGA says Fortune 100 carriers lag on API integration — [Insurance Business 2026](https://www.insurancebusinessmag.com/us/news/technology/fortune-100-carriers-lag-on-api-integration-mga-says-585885.aspx). QuoteSweep (a portal-automation vendor, so self-interested) claims "98% of P&C carriers have no API" — [QuoteSweep](https://www.quotesweep.com/blog/98-percent-carriers-no-api)

### Inferences
- Real-time API connectivity is concentrated in small commercial BOP/GL/WC/cyber with roughly 30–60 large or digital carriers, and in personal auto/home via mature raters. Regional carriers, E&S/wholesale markets, specialty MGAs, and nearly all post-bind servicing (endorsements, claims status, billing, commission statements, document downloads) still go through portals. This is where a portal-agent API would add the most.
- Applied's consolidation (Ivans + EZLynx + Tarmika + Indio + Cytora) makes it the most likely incumbent to add AI portal agents. It also controls the Ivans download pipe, the closest substitute for portal scraping on policy and commission data.
- Aggregator APIs (CoverForce, Bold Penguin) charge carriers or brokers for integrations already built. A browser-agent API could reach the long tail, but fidelity will be lower.

### Gaps
- No primary 2026 carrier-count data from Applied, Vertafore, or Ivans. Counts come from third-party blogs.
- No 2025–2026 data on Appulate (wholesale/E&S submissions) or on ACORD standards progress (e.g., ACORD Next-Gen/API standards).
- Ivans Download coverage (number of carriers sending policy/commission downloads) was not found for 2026.
- Pricing for Tarmika, Bold Penguin, and CoverForce per quote or per bind is undisclosed.

## AI-native startups: funding, pricing, traction, and who explicitly drives carrier portals with browser agents

### Takeaway
At least five companies now explicitly use browser or AI agents to drive carrier portals: Covera (YC F26), Insure Stack (formerly Mulligan, YC), Strada (YC, launched browser automation 24 Sept 2026), QuoteSweep, and the horizontal agent platforms Skyvern and Asteroid. Almost all of them sell a finished agency app (quoting UI, servicing agents), not a neutral per-transaction REST API. The well-funded AI underwriting companies (Sixfold, Federato, Kalepa, Pibit, Cytora) sell to carriers and MGAs for submission triage. They are adjacent, not direct competitors.

### Cited Findings
**Direct portal-automation competitors**
- **Covera (YC Fall 2026):** AI workflows connected to the AMS, the inbox, and "100+ carrier portals." It builds a risk profile from client documents and emails, then a Chrome/Edge extension fills each carrier portal screen by screen, showing what was filled and what was missing. "Covera never submits a quote on its own"; the agent reviews and submits. Coverage varies by carrier and product. The YC page says it went live with 90+ brokers in the US and Europe in its first three months — [Covera site](https://www.covera-agents.com/); [Covera carrier portals](https://www.covera-agents.com/carrier-portals); [YC Covera](https://www.ycombinator.com/companies/covera); [Covera joins YC](https://www.covera-agents.com/blog/covera-joins-y-combinator)
- **Insure Stack (formerly Mulligan, YC):** "AI automation for insurance brokerages." It logs into each carrier portal and produces draft quotes ready to review, edit, and bind — [YC Mulligan page](https://www.ycombinator.com/companies/mulligan). Batch and funding not confirmed.
- **Strada (YC-backed):** AI phone, email, and chat agents for carriers, MGAs, TPAs, and brokers, covering endorsement processing, COI issuance, and servicing. On 24 Sept 2026 it launched browser automation for carrier portals and legacy systems without APIs, using credentials carriers, MGAs, wholesalers, and TPAs already assign to their users. It is available to all customers. Named customers include Hippo, Clearcover, and Hagerty. Built on Temporal. Funding not publicly disclosed — [Newsfile release](https://www.newsfilecorp.com/release/315832/Strada-Launches-Browser-Automation-for-Carrier-Portals-and-Legacy-Systems-Without-APIs); [Strada blog](https://www.getstrada.com/blog/browser-automation); [Temporal case study](https://temporal.io/resources/case-studies/strada); [Notch comparison](https://www.notch.cx/learn/notch-vs-liberate-vs-strada)
- **QuoteSweep:** AI web agents log into the carrier's agency portal with the agency's credentials, work through the application, and return a quote, decline, or referral. It tracks 540+ carriers but has quoting automation for only 25. Pricing is monthly plans with submission caps: free (3 submissions), Solo $49/mo (10), Pro $99/mo (30), Business $299/mo (100), enterprise by quote. An older listing showing "$99 + $12/submission" was corrected by QuoteSweep. Implied price is about $3–5 per submission — [QuoteSweep](https://www.quotesweep.com/); [InsurAItools listing](https://www.insuraitools.com/item/quotesweep); [QuoteSweep glossary](https://www.quotesweep.com/glossary/carrier-portal-automation)
- **Skyvern** (horizontal browser-agent platform) published an insurance carrier-portal automation guide in Mar 2026. Per the search summary, it cites agency staff spending 2–4 hours daily across 15–40 portals and running quotes across 15 carriers in parallel. These are vendor claims and could not be fetched to verify — [Skyvern blog, Mar 2026](https://www.skyvern.com/blog/automate-insurance-carrier-portal-workflows/)
- **Asteroid (YC launch):** "browser agents with human oversight" for regulated industries. Listed use cases include retrieving broker quotes across insurer portals — [Launch YC Asteroid](https://www.ycombinator.com/launches/MtY-asteroid-browser-agents-with-human-oversight) (date not confirmed)
- **SUPERAGENT AI** (14 Oct 2025) announced a Quoting AI Agent that navigates carrier portals as part of a sales-funnel suite. Current status unverified — [BusinessWire](https://www.businesswire.com/news/home/20251014317368/en/SUPERAGENT-AI-Launches-Suite-of-AI-Agents-to-Automate-the-Entire-Insurance-Sales-Funnel-From-First-Call-to-Final-Quote)
- **AgentSpace (YC):** agency-management AI that extracts and syncs policy data from carrier reports. This is report-based, not portal-driving — [AgentSpace](https://useagentspace.com/)
- **Carrier Connect AI** exists, but only its terms page surfaced; product details unknown — [carrierconnect.ai terms](https://carrierconnect.ai/terms.html)

**AI brokerages (can be customers or competitors)**
- **Harper (YC):** AI-native commercial brokerage. Raised a combined seed + Series A of $46.8M (~$47M), led by Emergence Capital with YC, Lobster Capital, and Peak XV, announced late Feb 2026 (one source says Mar 2026). It reports 5,000+ customers — [FinTech Global, 26 Feb 2026](https://fintech.global/2026/02/26/harper-raises-47m-to-modernise-business-insurance-with-ai/); [UrbanGeekz](https://urbangeekz.com/2026/02/yc-backed-harper-raises-47m-build-ai-insurance-brokerage/)
- **Corgi:** AI-native insurer for startups. Emerged in Jan 2026 with $108M seed + Series A — [Wikipedia](https://en.wikipedia.org/wiki/Corgi_(insurance_company))

**AI underwriting / submission intake (carrier/MGA side, adjacent)**
- Sixfold: $30M Series B (Jan 2026) led by Brewer Lane with Guidewire strategic. About $51.5M total. Launched an "AI Underwriter" in Jun 2026 — [Sixfold](https://www.sixfold.ai/content/post/series-b-ai-underwriter)
- Kalepa: $75M Series B (5 Nov 2026) at a reported $470M valuation — [Ventureburn](https://ventureburn.com/kalepa-raises-75m-ai-insurance-platform/)
- Federato: $100M Series D (Nov 2025) led by Goldman Sachs Alternatives. Totals conflict between sources (>$180M vs $80M) — [FinTech Global, Jan 2026](https://fintech.global/2026/01/30/insurtech-funding-reaches-420m-in-january-as-us-firms-secure-mega-deals/); [Teardown Kalepa](https://www.teardown.ai/companies/kalepa)
- Pibit.AI: $7M Series A (Nov 2025) led by Stellaris — [FurtherAI blog](https://www.furtherai.com/blog/ai-tools-for-commercial-insurance-underwriting)
- Cytora: acquired by Applied, Sept 2025 — same source
- Consolidation: Guidewire agreed to acquire hyperexponential for $1.7B (27 Oct 2026). Duck Creek acquired Send (Jul 2026) — [search summary of funding trackers](https://newmarketpitch.com/blogs/news/ai-in-insurance-list-deals) (verify)
- "Vooma" in search results is a freight-broker AI company ($16.6M seed + Series A, Craft/Index), not insurance — [FreightWaves](https://www.freightwaves.com/news/vooma-grabs-16-6m-in-funding-as-brokers-prepare-for-market-swing). The brief's "Vooma-type" label probably refers to the same pattern (multichannel agent doing data entry into legacy systems) applied to insurance.

### Inferences
- The closest comparables to "Portals As A Service" are Strada (enterprise, carrier/MGA/TPA side, servicing and endorsements) and Covera, Insure Stack, and QuoteSweep (agency-side quoting apps). None of the sources describe a carrier-agnostic, developer-facing REST API with per-transaction pricing. A neutral "API for AI brokerages, AMS vendors, and raters" stance looks open. Likely buyers: Harper-style AI brokerages, comparative raters needing long-tail carriers, and AMS vendors.
- Covera's and QuoteSweep's human-in-the-loop "never submits on its own" positioning suggests the market (and E&O concerns) currently rewards prefill plus human bind over fully autonomous bind.
- Servicing (endorsements, claims status, commission downloads) has less agency-side AI competition than quoting. Strada is the main player and sells to carriers and MGAs.

### Gaps
- No funding found for Covera, Insure Stack/Mulligan, Strada, or QuoteSweep. Covera is YC standard deal only (assumed, not verified).
- Nirvana, Anzen, Gradient AI, and Patra AI were not researched within the tool budget. They are primarily carrier/MGA underwriting or insurers, not portal connectivity.
- No source on actual per-transaction prices charged by any browser-agent vendor. QuoteSweep's tiers are the only public pricing.

## Agency pain: number of carrier portals, re-keying time, offshore staffing costs, willingness to pay per transaction

### Takeaway
The average independent agency had 19.7 carrier appointments in 2025, up from 17.2 in 2024 (Big I 2026 Agency Universe Study). "Dealing with multiple carrier interfaces" is again the #1 technology challenge, and 74% of agents name re-keying their top pain (Ivans 2026). The labor alternative is offshore BPO at about $1,500–2,800 per FTE per month. Per-transaction automation has to beat roughly $10–20/hour fully loaded offshore labor.

### Cited Findings
- Big I / Future One 2026 Agency Universe Study (released ~Oct 2026): 1,376 respondents (Zeldis Research). About 37,000 US independent agencies, slightly down from 2024. Average carrier appointments (all lines) rose from 17.2 (2024) to 19.7 (2025). "Dealing with multiple carrier interfaces" is the biggest technology challenge, as in prior years. Agencies accept carrier self-service for documents, billing, and claims, but not for quoting or buying — [IA Magazine, 1 Oct 2026](https://www.iamagazine.com/2026/10/01/evolving-channel-key-findings-from-the-2026-agency-universe-study/); [IndependentAgent.com](https://www.independentagent.com/news/big-i-and-future-one-release-2026-agency-universe-study/); [Insurance Business](https://www.insurancebusinessmag.com/us/news/technology/independent-agency-revenue-rose-at-three-in-four-firms-as-ai-adoption-tripled-big-i-study-finds-590958.aspx) (AI adoption reportedly tripled)
- Appointment counts rise with agency size — [Big I 2024 AUS presentation](https://trustedchoice.independentagent.com/resources/agency-universe-study-presentation-2024/) [possibly stale]
- Ivans 2026: re-keying is the #1 pain for 74%. 37% cite multiple logins, 38% slow portals. 90% have cut business with a carrier over friction. Submission friction now outranks price in placement decisions — [Insurance Business](https://www.insurancebusinessmag.com/us/news/technology/submission-friction-now-beats-price-in-where-agents-place-business-ivans-finds-587645.aspx); [AgencyChecklists, 21 Sept 2026](https://agencychecklists.com/2026/09/21/insurance-agents-carrier-submission-friction-automation-83451/)
- Vendor claim: staff spend 2–4 hours daily on carrier portal work across 15–40 systems — [Skyvern, Mar 2026 (search summary)](https://www.skyvern.com/blog/automate-insurance-carrier-portal-workflows/)
- Offshore labor benchmarks (2026, third-party/competitor sources): offshore about $1,800–2,800/FTE/month, nearshore $2,500–4,200, onshore $4,500–7,000 — [Helpware 2026](https://helpware.com/blog/insurance-bpo-companies). Another source gives offshore at $1,500–3,000/FTE/month — [Sonant 2026](https://www.sonant.ai/blog/insurance-bpo-providers)
- Patra: quote-based managed services, billed per seat/FTE plus SaaS for its AI tools. Its VA product is reported at $1,250/month for 75 hours (about $16.7/hr) plus a $2,500 setup fee and a 12-month minimum. Patra claims up to 40% opex reduction and that one VA client saves 50% versus an internal FTE — [Sonant Patra review 2026](https://www.sonant.ai/blog/patra-alternative-review); [Patra VA page](https://www.patracorp.com/insurance-operations-services/patra-virtual-assistant/)
- A competitor says Patra handles carrier downloads "per schedule; matching may be manual" — [Selectsys vs Patra](https://www.selectsys.com/compare/selectsys-vs-patra) (competitor claim)
- Unit-economics comparison of automated COI versus offshore BPO (Patra, ReSource Pro) — [InsureAssistAI](https://insureassistai.com/compare/automated-coi-vs-offshore-bpo) (figures not extracted)

### Inferences
- Pricing anchor: offshore labor at about $10–17/hour, so a 15–30 minute portal task (one quote entry, one endorsement, one commission download) costs about $3–8 in labor. A per-transaction price of about $1–5 matches QuoteSweep's implied $3–5/submission and undercuts BPO, as long as the success rate is high enough that humans rarely redo the work.
- With about 20 appointments per agency, plus MGA and wholesaler portals, each agency needs coverage of a long tail of regional carrier portals that API aggregators don't reach.

### Gaps
- No primary survey data on hours per week spent re-keying. The 2–4 hours/day figure is a vendor claim.
- No direct survey on willingness to pay per transaction.
- No Reddit/r/InsuranceAgent threads retrieved (fetch blocked).
- Brightwell and ReSource Pro pricing not found.

## Carrier stance: ToS against automation, MFA, API programs, risk of blocking

### Takeaway
No carrier's actual ToS text was retrieved. Secondary sources agree that portal terms and agency agreements tie access to named individual users, that shared or automated credentials are a compliance problem, and that MFA usually needs a human in the loop. Strada and QuoteSweep work around this by operating "with the credentials carriers already assign to users," which reduces but does not remove blocking and ToS risk. Carriers are investing in their own AI portal features (Travelers, Oct 2026) and selective APIs, often via Applied/Ivans or aggregators.

### Cited Findings
- Commentary says carrier portals often bar automated access in their terms and some actively detect it. The recommended path is written allowlisting or using the portal owner's integration channel — [Peakflo on MFA/CAPTCHA](https://peakflo.co/blog/ai-browser-agent-mfa-captcha-session-timeouts-vendor-portals). This conflicts with a vendor claim that "most carriers permit authorized agents to use tools that assist with data entry and application submission" — [QuoteSweep "Carrier Portal Automation Explained"](https://www.quotesweep.com/blog/ai-web-agents-for-insurance) (self-interested)
- Browser agents need a human to supply OTPs when MFA fires. If the OTP goes to a named employee's phone, the setup becomes impersonation rather than a service identity — [Peakflo](https://peakflo.co/blog/ai-browser-agent-mfa-captcha-session-timeouts-vendor-portals)
- Shared logins, where multiple agents use one carrier login, are named as a common failure against carrier IT requirements for agencies — [Atticus Rowan, agency IT](https://atticusrowan.com/blog/insurance-agency-it-carrier-requirements)
- Changing devices to evade a carrier's verification hold can breach the agency agreement or portal terms of use — [JustBrowser 2026](https://justbrowser.app/blog/antidetect-browser-insurance-quote-aggregator-multiple-broker-accounts)
- CAPTCHAs can still detect AI agents, so fallbacks are needed — [BaristaLabs](https://www.baristalabs.io/blog/captchas-detect-ai-agents-browser-automation-fallbacks)
- Strada's portal automation runs "using the credentials carriers, MGAs, wholesalers, and TPAs already assign to their own users" — [Newsfile, 24 Sept 2026](https://www.newsfilecorp.com/release/315832/Strada-Launches-Browser-Automation-for-Carrier-Portals-and-Legacy-Systems-Without-APIs)
- A trust risk flagged in a startup-idea writeup: whether small agencies will hand portal credentials to software — [StartupBasket KeyBot](https://startupbasket.ai/ideas/keybot-insurance-portal-autopilot/)
- Carrier APIs: The Hartford (2023, midsize/large) [possibly stale]; Travelers' Travis AI WC quoting (Oct 2026); Travelers + Applied submissionless renewal; Nationwide, Liberty, Chubb, and Travelers via CoverForce API. A blog with unverified anonymous sourcing claims The Hartford declined to expose its small-commercial BOP API to third-party raters — see sources in the incumbents section; [QuoteSweep 98% no API](https://www.quotesweep.com/blog/98-percent-carriers-no-api)
- A source says AI quoting tools have shifted from screen-scraping carrier portals to authenticated API calls where APIs exist — [GetPerspective 2026](https://getperspective.ai/blog/best-ai-tools-for-insurance-agents-2026-ranked-comparison)

### Inferences
- The main platform risk is carriers detecting non-human sessions (device fingerprinting, CAPTCHA, MFA re-prompts) and agency-agreement clauses on credential use. Mitigations: per-user credentials held in a vault, human-approved MFA relay, carrier allowlisting or partnership programs, and an API-first fallback where Ivans or aggregator connectivity exists.
- Carriers have an incentive to tolerate agent automation that increases submission flow (90% of agents cut carriers over friction). They have less reason to tolerate it on servicing or commission scraping. A carrier-partnership track ("we bring you submissions in clean form") could turn the blocking risk into a distribution channel.

### Gaps
- No actual carrier ToS clauses (e.g., Travelers, Progressive ForAgentsOnly, Hartford, Nationwide agency portals) were retrieved. They need direct review.
- No reported cases of carriers blocking AI agents or terminating agency appointments over automation found for 2025–2026.
- No information on ACORD or industry-body positions on agentic portal access.
