# Healthcare Vertical: Competition for AI Payer-Portal Automation (as of Nov 23, 2026)

Scope: US payer-portal automation (eligibility/benefits, prior auth submission and status, claim status, denials/appeals, credentialing). This note maps incumbents and AI-native startups and looks for gaps for a "Portals As A Service" entrant: computer-use agents behind a REST API, priced per transaction.

How to read this note:
- Each fact is dated where the source dates it.
- Items marked [PRE-2025, POSSIBLY STALE] predate 2025.
- Many figures come from search-engine snippets or aggregators, not primary pages. Several primary sites could not be fetched from this session because their hosts are outside its allowed network domains: index.caqh.org, availity.com and asteroid.ai. Verify those figures before using them.

---

## 1. Incumbents: clearinghouses and connectivity — EDI coverage versus portal and phone work

### Takeaway
- Incumbents own the standard X12 rails (270/271 eligibility, 276/277 claim status, 837/835) and, increasingly, FHIR prior-auth APIs.
- The incumbents are now moving into agentic AI themselves:
  - Availity Extend (Nov 2026) offers REST, a sandbox and MCP access for AI agents.
  - Waystar shipped agentic AI in Jan, Mar and Aug 2026.
  - Optum launched Digital Auth Complete (Feb 2026).
- Availity has explicitly banned bots from its portal and steers automation to its APIs. That is a direct threat to a scraping or computer-use model on the largest multi-payer portal.
- Medical prior auth is still only about 40% electronic per CAQH, so the portal, fax and phone long tail remains large.

### Cited Findings
**Availity**
- Availity Extend (announced Nov 2026) lets organizations use Availity network capabilities "inside their own applications, automation and AI agents through a single secure integration." It offers REST APIs, sandbox access and Model Context Protocol (MCP) tooling for customer-managed agents. — [Availity press release (via search snippet; page not fetchable from this session)](https://www.availity.com/news/availity-extend-securely-opens-the-nations-largest-health-intelligence-network-to-builders-automation-and-ai-agents/)
  - Initial workflows: coverage and benefits, patient estimates, claims submission/validation/status, remittance, provider access and prior authorization.
- Availity says it "decided to eliminate bot access to Availity Essentials, our provider portal" and offers RESTful API connections instead. The post is undated and probably several years old. — [Availity blog "Why APIs are better than bots"](https://www.availity.com/blog/why-apis-are-better-than-bots/)
- The Availity Essentials Organization Access Agreement (version V2024.0718, July 2024) names "screen scraping," "web scraping" and "web bots" as prohibited Scraping Methods. Availity may monitor use and suspend or terminate access. — [Availity OAA PDF](https://essentials.availity.com/availity/documents/Availity_OAA.pdf) [2024]
- Jan 2026 (JPM26): Abridge is embedding Availity's FHIR-native prior-auth APIs into its ambient AI, aiming for payer determination during the visit. — [Fierce Healthcare](https://www.fiercehealthcare.com/ai-and-machine-learning/jpm26-abridge-teams-availity-scale-real-time-prior-authorization); [Becker's](https://www.beckershospitalreview.com/healthcare-information-technology/digital-health/abridge-availity-team-up-on-real-time-prior-authorization/)
- Availity AuthAI covers CMS-0057-F prior-auth APIs (CRD, DTR and PAS) and returns recommendations to the EHR or the Availity portal. This comes from a vendor buyer's guide, 2026. — [beri.net](https://www.beri.net/article/best-ai-prior-authorization-software-payers-providers-cms-0057-f-2026)

**Waystar**
- Jan 2026: introduced agentic AI built on Waystar AltitudeAI. — [Waystar IR](https://investors.waystar.com/news-releases/news-release-details/waystar-introduces-agentic-ai-advance-toward-autonomous-revenue)
- Mar 5, 2026: expanded its Google Cloud collaboration. — [Google Cloud press corner](https://www.googlecloudpresscorner.com/2026-03-05-Waystar-Advances-AI-Innovation-with-Google-Cloud-to-Accelerate-the-Autonomous-Revenue-Cycle)
- Aug 26, 2026: unveiled agentic capabilities, including autonomous resubmission of denied claims. — [TechTarget](https://www.techtarget.com/revcyclemanagement/news/366649778/Waystar-expands-AI-powered-agentic-revenue-cycle-tools); [Unite.ai](https://www.unite.ai/waystar-puts-agentic-ai-to-work-on-claims-denials-and-patient-bills/)
- Financials, from a search summary of a secondary source: Q2 2026 revenue was $319.7M (+18% YoY), and FY2026 guidance was raised to $1.276B–$1.294B. Verify against Waystar's 10-Q. — [Unite.ai / TechTarget, as above]
- Waystar is named as a medical-benefit prior-auth platform alongside Silna and Rhyme. — [Silna "Best Prior Authorization Software"](https://www.silnahealth.com/resources/best-prior-authorization-software/) (competitor-authored)

**Optum / Change Healthcare**
- Feb 2026: Optum launched the provider-side tool Digital Auth Complete. This is per a search summary; the primary source was not retrieved. — [pabau.com roundup](https://pabau.com/blog/prior-authorization-software/)
- Optum's pharmacy ePA page lists six submission routes: CoverMyMeds, Surescripts, PreCheck MyScript, DrFirst, CenterX and Allscripts. — [Optum ePA page](https://business.optum.com/en/pharmacy-services/electronic-prior-authorization.html)
- Optum is reportedly "retiring most fax numbers" for pharmacy PA requests. No date was given, so treat this as unverified. — [faxpigeon](https://faxpigeon.com/resources/optumrx-prior-authorization-fax-number)

**Experian Health**
- Its AI products include Patient Access Curator and AI Advantage (denials). No 2026 specifics were found. — [nirmitee roundup](https://nirmitee.io/blog/agentic-ai-startups-healthcare-2026-20-companies/)

**Infinx**
- Described as KKR-backed, AI-driven RCM outsourcing that reportedly eyes a ~$300M IPO in India, with ~$186M total funding per a third-party tracker. Unverified. — [nirmitee roundup](https://nirmitee.io/blog/agentic-ai-startups-healthcare-2026-20-companies/)

**CoverMyMeds, Surescripts and Rhyme**
- CoverMyMeds (McKesson) and Surescripts are the main pharmacy ePA networks (NCPDP SCRIPT) and are "often free to providers."
- Rhyme focuses on medical-benefit prior auth inside the EHR, where the payer has joined its network.
- CoverMyMeds routes some requests to payers by fax or X12 278. — [Silna resource page](https://www.silnahealth.com/resources/best-prior-authorization-software/); [IntuitionLabs ePA explainer](https://intuitionlabs.ai/articles/ncpdp-script-epa-surescripts)

**Stedi (developer-first clearinghouse — the closest "API-first" analog)**
- Pay-as-you-go 270/271 pricing: $0.30 per check for 1–250 checks a month, $0.15 for 251–3,500, $0.10 for 3,501–10,000 and $0.08 above 10,000. There is no monthly minimum. — [Stedi pricing](https://www.stedi.com/pricing)
- Funding: $50M Series C (Mar 2026, led by Addition) after a $70M Series B (2025, Stripe and Addition), ~$142M total. — [Stedi blog](https://www.stedi.com/blog/series-c); [yespress](https://yespress.io/stedi)
- Stedi has published guidance on dental payer portal scraping for eligibility, which shows that even an EDI-native vendor supplements X12 with portal scraping where 271 data is thin, notably in dental. — [Stedi blog](https://www.stedi.com/blog/how-to-scale-real-time-dental-eligibility-checks-with-portal-scraping) (undated)

**CAQH Index (electronic vs. manual)**
- Medical prior auth electronic adoption rose from 31% (2023 Index) to 40% (2025 Index).
- Providers save ~15 minutes per PA by using X12 278 instead of fax, email or mail.
- The industry has a >$20B savings opportunity (2025 Index; CAQH 2026 eSolutions slides). — [CAQH 2026 eSolutions slides](https://s3.amazonaws.com/amo_hub_content/Association361/files/CAQH_2026%20eSolutions%20Xchange%20Slides.pdf); [AJMC May 1, 2026](https://www.ajmc.com/view/caqh-index-finds-20-billion-in-cost-savings-opportunities); [CAQH blog](https://www.caqh.org/blog/2025-caqh-index-shows-u.s.-healthcare-avoided-258-billion-and-accelerated-automation-interoperability-and-ai-adoption)
- Cost per manual transaction:
  - Becker's cites $14.24 for a manual prior auth and $8.77 for a manual eligibility/benefit verification. The Index year is not stated, probably the 2024 Index. — [Becker's](https://www.beckershospitalreview.com/finance/what-8-manual-tasks-cost-the-healthcare-industry-per-transaction/)
  - A secondary blog cites the 2023 Index: $10.97 for a manual PA and $7.97 for a manual eligibility check to the provider. — [ibl.ai](https://ibl.ai/blog/what-ai-prior-authorization-actually-costs-2026) [PRE-2025 data, POSSIBLY STALE]
  - The two sets of figures conflict. Use the 2025 Executive Report, which could not be fetched, for definitive numbers.

### Inferences
- Eligibility (270/271) and claim status (276/277) are largely commoditized through EDI at $0.08–$0.30 per transaction (Stedi). A portal agent cannot compete on price for these. It can win only where the 271/277 response is thin, for example:
  - service-type-specific benefits, accumulators, visit limits and carve-outs
  - dental breakdowns
  - DME/behavioral carve-out vendors
  - claim-level denial detail and attachments
- Medical prior auth (still ~60% non-electronic), appeals, attachments and credentialing are the clearest current portal and phone work.
- Availity Extend with MCP tooling is the biggest strategic threat. It gives AI agents a sanctioned, structured path to the largest multi-payer network, removing the need to click through Availity's portal for many payers. The opportunity is in payer-proprietary portals not fronted by Availity, such as:
  - UHC, Cigna, Humana and Medicaid MCO portals
  - utilization management (UM) vendor portals such as eviCore, Carelon and Cohere
  - DME, dental and behavioral health carve-outs
- Incumbents are bundling agentic AI into existing contracts, so a standalone per-transaction API must sell to builders (RCM software, AI startups, outsourcers), not compete for health-system enterprise deals.

### Gaps
- Exact 2025 CAQH Index cost per manual, portal and electronic transaction for each transaction type: index.caqh.org could not be fetched.
- Portal versus EDI share for claim status and eligibility. CAQH reports "partially electronic" (portal) separately, but those numbers were not retrieved.
- Availity Extend pricing, and whether it covers non-Availity payer portals.
- Primary source for Optum Digital Auth Complete. Status of Change Healthcare portal/EDI after the 2024 cyberattack; not researched.
- Experian Health and Infinx 2026 product/AI details.

---

## 2. AI-native startups (funding, pricing, traction)

### Takeaway
- The space is crowded and well funded. The largest players are:
  - Infinitus: ~$103M raised, phone-call agents
  - Tennr: $101M Series C at a $605M valuation
  - Cohere Health: $200M total, payer-side
  - Latent Health: $80M Series A, ~$600M valuation, pharmacy/specialty PA
  - Stedi: $142M, EDI API
- Only a small set of mostly YC startups explicitly sell portal automation through an API: Asteroid (W25), Clicks Health (F25), and Pledge Health (browser extension, not an API).
- Most AI-native players sell vertical workflow apps or outsourced services, not a horizontal portal API.

### Cited Findings
**Phone-first**
- Infinitus raised a $51.5M Series C (Oct 24, 2024; a16z lead), ~$102.9M total. — [MobiHealthNews](https://www.mobihealthnews.com/news/infinitus-systems-raises-515m-automating-healthcare-calls) [PRE-2025, POSSIBLY STALE]
  - 2026 launches: agentic AI for health-plan member services (Feb 2026), Lens (May 2026), Clinical Escalations (Jul 2026) and FieldForce for pharma. — [Fierce Healthcare](https://www.fiercehealthcare.com/ai-and-machine-learning/infinitus-launches-agentic-ai-support-health-plans)
  - No 2026 funding round was found.
- Prosper (YC S23): phone agents for claim status checks, benefit verification and prior auths. — [YC Healthcare IT directory](https://www.ycombinator.com/companies/industry/healthcare-it)

**Prior auth, provider and pharmacy side**
- Latent Health: $80M Series A (Spark Capital, Transformation Capital), >$20M annualized revenue, ~$600M valuation (Forbes, Mar 18, 2026). — [Forbes](https://www.forbes.com/sites/rashishrivastava/2026/03/18/this-600-million-ai-startup-is-speeding-up-paperwork-so-patients-get-drugs-faster/)
- Develop Health: $14.3M Series A. The date is roughly mid-2025 (the snippet put the article at "~459 days ago"). — [MobiHealthNews](https://www.mobihealthnews.com/news/develop-health-garners-143m-ai-prior-authorization-platform)
- Forus (Tandem): reportedly a $150M Series C (Sep 8, 2026; Bain Capital Ventures, $3B valuation). The data conflicts and the figure is unverified. — [RevCycleAI deals tracker](https://revcycleai.com/deals-and-raises/)
- Coral: $12.5M (Apr 2026; Z47, Lightspeed). This conflicts with another source citing a ~$14.5M seed. — [RevCycleAI](https://revcycleai.com/deals-and-raises/)
- Silna: Predictive Document Intelligence (Jan 29, 2026); ~$27M total funding including a $22M Series A (Mar 2025; Accel, BCV); claims support for >150,000 patients. It is strong in ABA/behavioral and specialty authorization. — [HIT Consultant](https://hitconsultant.net/2026/01/29/silna-launches-industrys-first-predictive-document-intelligence-to-proactively-clear-patients-for-care/); [Breaking News ABA](https://breakingnewsaba.com/business/silna-uses-ai-to-revolutionize-the-process-of-obtaining-aba-authorizations-and-it-is-mind-boggling)
- Tennr: $101M Series C at a $605M valuation (2025); $37M Series B and $18M Series A (2024). It is piloting with OpenAI to test AI agents completing prior-auth tasks (2026). It focuses on referral intake and is strong in DME and specialty. — [MobiHealthNews](https://www.mobihealthnews.com/news/tennr-openai-test-ai-agents-prior-authorization)

**Payer-side utilization management (customers are payers, not portal users)**
- Cohere Health: $90M Series C (May 2025, Temasek), $200M total; reportedly auto-approves ~90% of 12M+ PA requests a year. — [nirmitee roundup](https://nirmitee.io/blog/agentic-ai-startups-healthcare-2026-20-companies/)
- Anterior: ~$40M (early 2026; NEA, Sequoia), ~$64M total. — [RevCycleAI](https://revcycleai.com/deals-and-raises/)
- ClarityCare: $16.5M Series A (late Oct 2026). — [RevCycleAI](https://revcycleai.com/deals-and-raises/)

**Specialty front office**
- Basata: $21M Series A (May 8, 2026; Basis Set Ventures), $24.5M total. It builds administrative agents for specialty practices. — [LucidQuest](https://www.lqventures.com/lucid-diligence-brief-basata-21-million-series-a/)

**RCM platforms and services**
- AKASA: automates coding, claims follow-up and prior auth. Funding figures conflict: about $205M–$250M disclosed, with the last confirmed round a $60M Series B in 2021. — [startupintros](https://startupintros.com/orgs/akasa) [stale/aggregator]
- Thoughtful AI: $20M Series A (Jul 2024; Drive Capital). — [AI Insider](https://theaiinsider.tech/2024/07/21/thoughtful-ai-launches-human-capable-ai-agents-raises-20m-in-new-funding/) [PRE-2025, POSSIBLY STALE]
  - It has reportedly combined with SmarterDx and Access Healthcare into "Smarter Technologies." Unverified. — [Menlo VC 2025 State of AI in Healthcare](https://menlovc.com/perspective/2025-the-state-of-ai-in-healthcare/)
- Notable Systems: XiFin made a strategic investment in its Series B. Amount and date were not found. — [Dealroom](https://dealroom.co/news/144495-xifin-backs-notable-systems-series-b-to-build-agentic-ai-for-healthcare/)
  - Note: "Notable Systems" may differ from Notable Health (notablehealth.com), the intake/automation company. Disambiguate.

**Not a portal competitor**
- Fortuna Health: $18M Series A (Jul 21, 2025, a16z). It does Medicaid eligibility and enrollment for consumers and plans (MVP Health Care, Highmark Wholecare). — [BusinessWire](https://www.businesswire.com/news/home/20250721481890/en/Fortuna-Health-Raises-$18M-Led-by-Andreessen-Horowitz-to-Modernize-Medicaid-Access-and-Infrastructure-Amid-Federal-Reforms)

**Explicit portal automation via API or agents — closest analogs to "Portals As A Service"**
- Asteroid (YC W25): a "HIPAA compliant API for EHRs, payer portals and desktop apps, including ones with no API." It covers 100+ payer portals, EHRs and registries, offers eligibility verification, and says integrations go live in days. — [asteroid.ai (search snippet; page not fetchable)](https://asteroid.ai/); [YC RPA directory](https://www.ycombinator.com/companies/industry/Robotic%20Process%20Automation)
- Clicks Health (YC F25): agents automate back office for RCM companies and providers across EHRs, payer portals, desktop apps and legacy systems. — [YC Health Tech directory](https://www.ycombinator.com/companies/industry/health-tech)
- Pledge Health (YC W23, NYC): an AI browser assistant inside the EHR across payer portals that verifies benefits, submits PAs and checks claim status. Directories conflict on whether it was acquired. — [YC Healthcare IT NY](https://www.ycombinator.com/companies/industry/healthcare-it/new-york)
- Sohar Health (YC S23): AI insurance verification; listed as acquired. — [YC directory](https://www.ycombinator.com/companies/industry/Healthcare%20IT)
- Optexity: vendor blog arguing that "FHIR APIs and RPA fall short" for prior auth because of payer portals. — [Optexity](https://optexity.com/blog/prior-authorization-automation-in-healthcare-the-payer-portal-problem-no-api-solves)
- Ventus AI: verification and denials across 300+ payers for dental and specialty groups; also markets "Availity automation" with AI agents (2026 guide). — [Ventus](https://www.ventus.ai/); [Ventus blog](https://www.ventus.ai/blog/availity-automation-health-systems-ai-agents-2026-guide/)
- Toothy AI (YC W25): dental agents that call payers and check portals for coverage, fix claims and follow up on denials; ~15 employees. — [YC](https://www.ycombinator.com/companies/toothy-ai)
- Kairos Health (YC F2026): dental calls and insurance checks. — [YC Health Tech](https://www.ycombinator.com/companies/industry/health-tech)
- Simplex (YC S24): AI agents for end-to-end provider enrollment (credentialing). — [YC RPA directory](https://www.ycombinator.com/companies/industry/Robotic%20Process%20Automation)
- Aegis (YC Spring 2025): detects denied claims, drafts and files appeals. — [healthcarediscovery.ai](https://healthcarediscovery.ai/companies/aegis/)
- Altair Health (YC F2026): AI-native billing service. — [YC](https://www.ycombinator.com/companies/industry/healthcare-it)

**Published pricing (sparse)**
- Specialty PA AI vendors typically charge $2–$5 per transaction or $50–$100 per clinician per month (2026 blog analysis; low-quality source). — [ibl.ai](https://ibl.ai/blog/what-ai-prior-authorization-actually-costs-2026)
- Others cite $5–$15 per request.
- Agentman lists its PA agent at $25 per submission, pay-as-you-go. — [Agentman](https://agentman.ai/prior-authorization-agent)
- Azure Marketplace PA agents are cited at ≥$100K per agent per year (same ibl.ai source).
- The same search summary attributed "$0.30→$0.08 per eligibility check" pricing to Silna. Those numbers exactly match Stedi's 270/271 pricing, so this is very likely a misattribution. Do not use it.
- Most vendors quote prices only after a demo.

### Inferences
- There is a clear horizontal gap: almost all well-funded players are vertical apps (Tennr, Silna, Basata, Latent), voice-first (Infinitus, Prosper), payer-side (Cohere, Anterior) or RCM services (AKASA, Thoughtful/Smarter, Infinx). A developer-facing per-transaction portal API is a small field, mostly seed-stage YC startups (Asteroid, Clicks). It resembles "Stedi for portals."
- A plausible pricing anchor sits between EDI ($0.08–$0.30) and manual labor ($8–$14 per transaction, CAQH):
  - roughly $1–$3 for a portal eligibility or claim-status lookup
  - roughly $5–$25 for a PA submission or appeal

  This is an inference from the sourced price points above, not a sourced figure.
- The vertical AI apps (Tennr, Silna, Basata, Toothy, Ventus) are candidate customers as well as competitors: they could buy portal execution from a horizontal API rather than build per-portal agents.

### Gaps
- Pricing, customers and funding were not found for Develop Health, Magical, Valer, Notable, Asteroid and Clicks.
- Traction metrics (transactions per month, portal count, success rates) for portal-API startups are unknown.
- Forus/Tandem round details conflict.
- Whether Pledge Health and Sohar were acquired, and by whom.
- No full scan of YC W26, S26 and F26 batches was done; only directory snippets.

---

## 3. Regulatory tailwinds and headwinds

### Takeaway
- CMS-0057-F requires impacted payers (Medicare Advantage, Medicaid/CHIP, QHP issuers on the federally facilitated exchanges) to stand up FHIR Prior Authorization, Provider Access, Payer-to-Payer and Patient Access APIs by Jan 1, 2027. As of Sep 2026 there was no announced delay.
- The voluntary AHIP/BCBSA pledge targets real-time answers for ≥80% of electronic PAs in 2027.
- Together these shrink the portal window for big MA, Medicaid and exchange plans over 2027–2029. Several categories are outside the rule's mandate:
  - commercial employer and ERISA plans
  - drugs (excluded from the rule)
  - DME and dental carve-outs
  - utilization management vendors
  - small payers
- Real-world provider adoption of FHIR PA lags, because it depends on EHR CRD/DTR support.
- Payer and Availity terms of use broadly prohibit bots and scraping, which is the biggest legal and operational headwind.

### Cited Findings
**CMS-0057-F (Interoperability and Prior Authorization Final Rule)**
- API requirements must be implemented by Jan 1, 2027. — [CMS fact sheet](https://www.cms.gov/files/document/fact-sheet-cms-interoperability-and-prior-authorization-final-rule-cms-0057-f.pdf)
- Operational provisions took effect Jan 1, 2026:
  - 72-hour expedited / 7-day standard decision timeframes
  - specific denial reasons
- First public PA metrics were due Mar 31, 2026. — [nirmitee explainer, late Sep 2026](https://nirmitee.io/blog/cms-0057-f-explained-prior-authorization-rule-2027/)
- CMS's Electronic Prior Authorization page (modified Sep 14, 2026) still listed the Jan 1, 2027 API date. The only enforcement discretion is the Feb 28, 2024 notice allowing an all-FHIR PA API without X12 278. — [nirmitee](https://nirmitee.io/blog/cms-0057-f-explained-prior-authorization-rule-2027/); [blueBriX](https://bluebrix.health/blogs/cms-0057-f-prior-authorization-rule-for-billing)
- EasyPA claims there is enforcement discretion through 2026 for operational provisions. This is unverified, vendor-sourced, and conflicts with the above. — [EasyPA](https://easypa.ai/cms-0057-f)
- The rule excludes drugs; it covers items and services. MA, Medicaid/CHIP and QHP issuers on the FFEs are impacted, while commercial employer plans are not directly covered. — [CMS fact sheet](https://www.cms.gov/files/document/fact-sheet-cms-interoperability-and-prior-authorization-final-rule-cms-0057-f.pdf)

**AHIP/BCBSA voluntary pledge (Jun 23, 2025)**
- About 50 insurers signed, including UHC, Aetna, Cigna, Elevance and Kaiser.
- Commitments:
  - reduce PA scope by Jan 1, 2026
  - common electronic PA submission requirements by Jan 1, 2027
  - ≥80% of electronic PAs with complete documentation answered in real time in 2027 — [AAMC](https://www.aamc.org/advocacy-policy/washington-highlights/health-plans-announce-voluntary-commitment-prior-authorization); [Axios](https://www.axios.com/2025/06/23/health-insurers-simplify-pre-approvals)
- Progress: insurers reported an 11% reduction in PAs since the pledge. — [Fierce Healthcare](https://www.fiercehealthcare.com/payers/insurers-have-eliminated-11-prior-authorizations-under-reform-pledge)
- An AMA survey found that physicians see the pledge as falling short. — [AMA](https://ama-assn.org/practice-management/prior-authorization/inside-payers-latest-plans-streamline-prior-authorization)
- Aug 26, 2026: AJMC FAQ asking whether the changes "go far enough by 2027"; the 80% target is not 80% of all requests. — [AJMC](https://www.ajmc.com/view/faq-prior-authorization-reform-will-changes-go-far-enough-by-2027-)
- UnitedHealthcare said (May 5, 2026) it would remove PA requirements for 30% of services by year-end. Secondary source; verify. — [search summary citing Menlo/aggregators](https://menlovc.com/perspective/2025-the-state-of-ai-in-healthcare/)

**Payer terms of service**
- UnitedHealth Group terms bar using software to "scrape," "crawl," or "spider" its Online Services. — [UHG Terms of Use](https://www.unitedhealthgroup.com/terms-of-use.html); [UHC Terms](https://unitedhealthpremium.uhc.com/legal/terms-and-conditions)
- Cigna terms prohibit access by "robots, crawlers, scripts, or other automated means (unless approved in writing)." This was seen in search summaries; a primary page was not retrieved.
- HealthPartners prohibits automated scripting and screen scraping of its provider portal without a separate written agreement. — [HealthPartners](https://www.healthpartners.com/provider-public/legal/terms-of-use/)
- The Availity OAA prohibits bots and scraping; see section 1. — [Availity OAA](https://essentials.availity.com/availity/documents/Availity_OAA.pdf)
- Vendors advise automating portals only where terms allow or with written approval, and re-reading terms on a schedule. — [Opexia](https://opexia.io/insights/commercial-payer-era-enrollment-aetna-cigna-uhc-humana-bcbs)

**HIPAA/BAA**
- No specific 2026 source was retrieved. A portal API vendor handling PHI would be a business associate (BA), or a subcontractor BA to RCM vendors, requiring BAAs. Competitors such as Asteroid market themselves as "HIPAA compliant." — [asteroid.ai](https://asteroid.ai/)

### Inferences
- For prior auth at MA, Medicaid and exchange plans, the portal window probably narrows over 2027–2029 as FHIR PAS/CRD/DTR APIs go live. It will not close immediately: provider-side EHR adoption, payer implementation quality and the non-mandated lines of business remain.
- Durable portal demand is likely in:
  - commercial/ERISA lines
  - UM vendor portals (eviCore, Carelon, etc.)
  - dental
  - DME
  - behavioral/ABA
  - workers' comp/auto
  - small regional plans
  - appeals and credentialing (not covered by the new APIs)
- ToS risk favors business-model choices that reduce detection and termination risk:
  - operate under the provider's own credentials (agent-as-the-user)
  - seek payer partnerships
  - prefer sanctioned APIs, such as Availity Extend and payer FHIR APIs, where they exist, with the portal agent as fallback ("API-first, portal-fallback")
- Availity Extend shows incumbents will channel AI agents onto sanctioned rails.

### Gaps
- Whether any payer has sued or terminated an AI portal-automation vendor for ToS violations (none found).
- An official CMS statement as of Nov 2026 on any enforcement discretion for the 2027 APIs; checked only through secondary sources dated Sep 2026.
- No HIPAA Security Rule update status (the proposed 2025 rule) was researched.

---

## 4. Underserved buyer segments

### Takeaway
- Dental is the most active AI-native cluster (Toothy, Kairos, Ventus, Stedi's dental portal scraping), which is evidence of thin 271 data and heavy portal use.
- Behavioral/ABA (Silna) and DME/referrals (Tennr) are served by vertical apps.
- Home health, DME-specific verification and RCM outsourcers buying a horizontal API look under-addressed by YC-stage companies. Evidence is thin.

### Cited Findings
- Dental eligibility often requires payer portals because X12 data is thin; Stedi published a guide to scaling dental portal scraping. — [Stedi](https://www.stedi.com/blog/how-to-scale-real-time-dental-eligibility-checks-with-portal-scraping)
- Dental-focused AI startups: Toothy AI (W25), Kairos Health (F26), Ventus AI (300+ payers, dental and specialty). — [YC Toothy](https://www.ycombinator.com/companies/toothy-ai); [Ventus](https://www.ventus.ai/)
- Opexia blog on the cost of RPA bot development for dental billing prior auths. — [Opexia](https://opexia.io/insights/cost-of-rpa-dental-billing)
- Behavioral health: the 2023 CAQH Index found behaviorists' cost per manual PA exceeds generalists' by more than $7. — [CAQH 2023 Provider Specialty brief](https://www.caqh.org/hubfs/CAQH%20Insights_2023%20Index%20Report_Provider%20Specialty%20Issue%20Brief_Final.pdf) [PRE-2025, POSSIBLY STALE]
- Silna targets ABA authorizations. — [Breaking News ABA](https://breakingnewsaba.com/business/silna-uses-ai-to-revolutionize-the-process-of-obtaining-aba-authorizations-and-it-is-mind-boggling)
- Home health: the only YC result was Sage, which does home-care intake communication, not insurance. No YC 2025–26 DME- or home-health-specific verification startups were found. — [YC Health Tech](https://www.ycombinator.com/companies/industry/health-tech)
- RCM outsourcers and companies:
  - Clicks Health explicitly targets RCM companies.
  - Infinx is an AI-enabled RCM outsourcer.
  - Thoughtful AI merged with Access Healthcare (a large RCM BPO) into Smarter Technologies.

  Sources: [YC](https://www.ycombinator.com/companies/industry/health-tech); [Menlo VC](https://menlovc.com/perspective/2025-the-state-of-ai-in-healthcare/)
- Specialty practices: Basata (specialty practices, $21M, May 2026) and Develop Health (specialty pharmacy PA) are active. — [LucidQuest](https://www.lqventures.com/lucid-diligence-brief-basata-21-million-series-a/)

### Inferences
- Best-fit early customers for a horizontal per-transaction portal API:
  - (a) vertical AI startups and RCM software companies that need portal execution without building their own agents
  - (b) mid-size RCM outsourcers whose margins depend on reducing per-transaction labor; consolidation such as Smarter Technologies may push independents to buy rather than build
  - (c) dental DSOs and dental RCM vendors
  - (d) DME and home-health billers dealing with Medicare Advantage and Medicaid MCO portals and UM vendors
- Credentialing and enrollment are under-served by portal APIs, with only Simplex (S24) found. Credentialing runs largely through CAQH ProView plus payer-specific portals and is untouched by CMS-0057-F, so it is a potentially durable niche. CAQH's role was not researched.

### Gaps
- No market-size data per segment (number of DME suppliers, home health agencies, or dental practices using portals).
- No direct evidence on DME or home-health portal pain intensity in 2026.
- No pricing benchmarks for RCM outsourcers' per-transaction labor costs (offshore RCM costs per verification or PA).
