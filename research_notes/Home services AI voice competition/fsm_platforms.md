# FSM Platforms' Native AI Voice / AI Receptionist Features (US home services, as of Nov 2026)

Method note: research conducted 2026-11-23 via web search only. Direct page fetches failed because the session's network policy blocked these hosts: servicetitan.com, plg.servicetitan.com, benzinga.com and saastr.com. As a result, many facts below come from search-result summaries of primary pages and from third-party blogs. Many of those blogs are run by competing AI-voice vendors (usecarly, fieldcamp, fieldproxy, tradevulcan and others) and have an incentive to criticize native tools. Each claim is dated where possible. Items dated before 2025 are flagged [PRE-2025, possibly stale].

## Q1. What AI voice/phone features have the FSM platforms launched (timing, pricing, capabilities, limits, adoption)?

### Takeaway
By late 2026, the three largest SMB/mid-market FSMs each sell a native AI phone agent: ServiceTitan's AI Voice Agent / Virtual Agents, Jobber's AI Receptionist and Housecall Pro's CSR AI. Workiz (Genius Answering, "Jessica") and FieldPulse (Operator AI) also have native agents. FieldEdge, Service Fusion, Successware, ServiceTrade and BuildOps rely on third-party voice partners and have no confirmed native voice agent. The natively priced offerings are usage-based or cheap add-ons: Jobber charges $29/mo for 30 conversations, and ServiceTitan is reported at about $2.75 per call. Adoption is still described as early, even by ServiceTitan.

### Cited Findings

**ServiceTitan**
- ServiceTitan sells a native "AI Voice Agent", also called "AI Virtual Agents", which is marketed as "the smartest AI CSR". It handles overflow and after-hours calls and books jobs directly against the account's Business Unit, Job Type and technician availability. — [ServiceTitan webinar recap](https://www.servicetitan.com/blog/webinar-recap-ai-virtual-agents-call-booking); [ServiceTitan onboarding docs](https://help.servicetitan.com/docs/voice-agent-onboarding-part-1-set-up)
- Capabilities in the help documentation include confirming and rescheduling appointments and rule-based escalation to a live agent. Setup supports both "Basic Phones" and "Phones Pro" telephony, which suggests the agent works best with ServiceTitan's own phone system. — [ServiceTitan help: Voice Agent onboarding](https://help.servicetitan.com/docs/voice-agent-onboarding-part-1-set-up)
- An April 2026 release note added a voice library with voice preview and tuning of speed, stability and "similarity boost". "Similarity boost" is ElevenLabs-style terminology, so the agent may run on a third-party TTS engine; this is an inference, not a confirmed fact. — [ServiceTitan Release Hub](https://help.servicetitan.com/release-hub/docs/customize-your-voice-agent-persona-to-match-your-company-s-brand)
- Pricing: third-party sites report $2.75 per call for the voice agent and $0.10 per text for the SMS agent, billed monthly on usage, on top of a quote-priced ServiceTitan subscription. The search summary says ServiceTitan's own overview page lists this rate, but another reviewer, checking on 2026-10-16, says the rate is not published. — [Roonly pricing breakdown](https://roonly.ai/pricing/servicetitan-ai-voice-agent-pricing); [CallbotScore](https://callbotscore.com/servicetitan-ai-voice-agent/); [ServiceTitan VA overview page](https://plg.servicetitan.com/va) (not directly fetched)
- Contact Center Pro, the multi-location call-center product, "centralizes calls across locations and includes AI virtual agents that help you book jobs 24/7". It is aimed at larger, multi-location operators. — [ServiceTitan: Contact Center Pro](https://www.servicetitan.com/blog/webinar-recap-contact-center-pro)
- At Pantheon 2025 (fall 2025), ServiceTitan unveiled "Atlas", an AI that "lives in your business", alongside AI product expansions. — [ServiceTitan Pantheon 2025 press](https://www.servicetitan.com/press/servicetitan-major-product-expansions-pantheon-2025); [Vahe Kuzoyan keynote recap](https://www.servicetitan.com/blog/pantheon-2025-vahe-keynote-atlas?utm_promo=fall2025)
- Adoption claims, a single unverified vendor-adjacent blog from January 2026: a 70% booking rate and 23% more booked jobs. — [GrowwStacks](https://growwstacks.com/blog/servicetitan-ai-voice-agent)
- A Q2 2026 competitive analysis notes that review volume specific to the AI Voice Agent is "still thin". — [Toarn: ServiceTitan AI competitive analysis](https://toarn.com/insights/servicetitan-ai)
- Acquisition: ServiceTitan agreed on 2025-09-18 to acquire Conduit Tech, and the deal closed on 2025-10-03. Conduit Tech is an HVAC design/sales platform built on LiDAR, not a voice-AI company. Some secondary sources mislabel it as an "AI workflow platform". — [ServiceTitan press](https://www.servicetitan.com/press/servicetitan-hvac-acquisition-conduit-tech); [SEC filing 2025-10-21](https://investors.servicetitan.com/static-files/c493a10b-57f4-4ad4-ad60-e609a68c17bc)
- One deal tracker lists a separate ServiceTitan acquisition of "Conduit AI", a conversational AI agent platform, dated 2026-03-02. No other source confirms it, so treat it as unverified. — [Signalbase](https://www.trysignalbase.com/news/acquisitions/conduit-ai-acquired-by-servicetitan-acquisition)

**Jobber**
- AI Receptionist became generally available in August 2025. The press release is dated Toronto, 2025-08-14, while a later blog says 2025-08-18. It answers calls and texts. At launch Jobber said it had already handled more than 200,000 conversations for beta businesses. — [Jobber launch PR via Yahoo Finance](https://finance.yahoo.com/news/jobber-launches-ai-powered-receptionist-130000716.html); [Landscape Management](https://www.landscapemanagement.net/jobber-releases-new-ai-powered-virtual-assistant/)
- Pricing, per 2026 sources citing Jobber's help center: a $29/mo add-on that includes 30 conversations, then $0.79 per extra conversation. It is included with unlimited usage on the Plus plan. The cheapest total is Core ($49) plus $29, or $78/mo. At launch in 2025 it was Plus-included and a Grow add-on. An April 2026 source cited a $99/mo Grow add-on, which conflicts with the other sources and is likely superseded. — [StackSpace review](https://stackspacesolutions.com/blog/jobber-ai-receptionist-review); [FitMyCall](https://fitmycall.com/jobber-ai-receptionist/pricing/); [TradesWithAI](https://tradeswithai.com/guides/jobber-ai-receptionist-cost/)
- Jobber plan prices conflict across sources: Plus is listed at $499/mo in one and $599/mo in another. — [Jobber pricing guides as above](https://aifrontdeskhelper.com/blog/aifdh-vs-jobber-ai-receptionist/)
- Limitations reported by third parties: it is not available in New Zealand (Capterra); it struggles with technical and pricing questions and defers to callback; and one second-hand r/HVAC anecdote describes a lost $15k system replacement because the bot could not transfer a caller who wanted a human. That anecdote was not verified against the original thread. One Reddit-summary site rates the Receptionist 6.5/10, "promising but new and limited". — [Kore Komfort comparison](https://korekomfortsolutions.com/jobber-ai-vs-housecall-pro-ai-are-they-worth-the-price-tag/); [Fieldcamp Jobber review](https://fieldcamp.ai/reviews/jobber/); [Capterra Jobber reviews](https://www.capterra.com/p/127994/Jobber/reviews/)
- An independent write-up of what it can and cannot do exists (not fetched). — [Rivet](https://therivetapp.com/blog/jobber-ai-receptionist-what-it-can-and-cant-do)

**Housecall Pro**
- The "AI Team" launched in May 2024 with an AI CSR, coach, analyst, marketer and product assistant [PRE-2025, possibly stale]. In spring 2025, CSR AI was expanded to book jobs, including after hours, with customizable voice, tone and greeting. On 2025-10-29 it added "Tell me more", which surfaces job history, balances and next steps. On 2026-02-24 it added CSR AI Chat Answering for web chat. "Coming soon" items at that point included CSR AI booking fallback and call-handling improvements. — [PR Newswire AI Team 2024](https://www.prnewswire.com/news-releases/housecall-pro-introduces-ai-team-offering-empowers-home-service-businesses-with-virtually-delivered-expertise-and-support-302147123.html); [HCP Spring 2025 release notes](https://www.housecallpro.com/resources/news-press/release-notes/spring-2025-product-updates/); [R&R fall 2025](https://www.randrmagonline.com/articles/91672-housecall-pro-unveils-major-ai-powered-updates-for-fall-2025); [HCP Feb 2026 updates](https://www.housecallpro.com/resources/february-2026-product-updates/)
- Pricing: CSR AI is a paid add-on with no published price; as of a 2026-11-09 check, sales gives a quote. Third-party estimates range from a $149 floor to $200–500+/mo, and none is official. Base plans are Basic $59, Essentials $149 and Max $299 per month, billed annually. — [Beside](https://www.beside.com/blog/housecall-pro-ai-phone-answering); [Usecarly](https://www.usecarly.com/blog/housecall-pro-ai-receptionist/); [WorkZen](https://www.workzen.io/en/blog/housecall-pro-pricing/)
- A third-party "honest review" catalogues what is "still missing" (not fetched in detail). — [AI Strategy Partners](https://www.aistrategypartners.net/guides/housecall-pro-csr-ai-review)

**Workiz**
- Workiz launched the "Genius" AI suite (PR Newswire, 2024) and then "Genius Answering", an AI agent called "Jessica" that answers calls, discusses services and books jobs or leads. Launch-era trade coverage appeared in 2024 [PRE-2025, possibly stale]. — [PR Newswire Genius launch](https://prnewswire.com/il/news-releases/workiz-launches-genius-to-revolutionize-field-service-management-with-ai-powered-offering-302088161.html); [ACHR News: Jessica](https://www.achrnews.com/articles/163805-jessica-is-the-new-ai-receptionist-for-contractors); [PM Mag](https://www.pmmag.com/articles/106226-workiz-launches-innovative-genius-answering-to-help-transform-field-service-management)
- Requirements and limits from the help docs: it requires a Workiz Genius Phone plan, so numbers must be ported to Workiz; it supports English and Spanish; it gives custom answers to FAQs; and it can book leads instead of jobs. When the monthly conversation cap is exceeded, the AI stops answering and calls fall through to the next call-flow step, such as voicemail. — [Workiz Genius Answering FAQ](https://help.workiz.com/hc/en-us/articles/30176041143697-Genius-Answering-FAQ); [Workiz settings](https://help.workiz.com/hc/en-us/articles/28907946434321)
- Pricing, unofficial: about $200/mo for Genius Answering, plus about $100/mo for the phone add-on, plus seats. — [Usecarly Workiz AI](https://www.usecarly.com/blog/workiz-ai/)

**FieldPulse**
- FieldPulse launched "Field Intelligence" in July 2025. It includes Operator AI, a 24/7 AI phone receptionist and dispatcher for after-hours, overflow and declined calls in 30+ languages, and Chat AI for the website. FieldPulse later launched Maverick, a back-office AI assistant that is not a receptionist. Before building its own, FieldPulse had partnered with Free2Grow (AI voice) and XAPP AI. — [FieldPulse 2025 feature roundup](https://www.fieldpulse.com/resources/blog/2025-feature-roundup); [Newswire Maverick](https://www.newswire.com/news/fieldpulse-launches-maverick-the-ai-assistant-built-for-field-service-22874701); [Newswire Free2Grow](https://www.newswire.com/news/fieldpulse-launches-integration-with-free2grow-to-enhance-efficiency-22462319); [PRWeb XAPP AI](https://www.prweb.com/releases/xapp-ai-announces-strategic-partnership-with-fieldpulse-to-revolutionize-ai-driven-efficiencies-for-field-service-businesses-302360531.html)

**FieldEdge, Service Fusion, Successware, ServiceTrade, BuildOps (no confirmed native voice agent)**
- FieldEdge: its public Future Features page lists no first-party AI agent. AI call answering comes through a Free2Grow integration that books into FieldEdge. — [TradeVulcan FieldEdge integrations](https://tradevulcan.com/integrations/fieldedge); [Free2Grow](https://www.free-2-grow.com/)
- Service Fusion: AI call answering comes from partner ZyraTalk, which syncs leads and booked jobs into Service Fusion. — [Service Fusion blog: ZyraTalk](https://www.servicefusion.com/blog/zyratalk-service-fusion-integration)
- Successware: AI call answering is "only available via third-party integrations", and its API is gated by plan or partner tier. — [TradesIndex: Successware](https://tradesindex.org/software/successware/)
- BuildOps: "OpsAI" covers dispatch, recap, document scanning, revenue finding and nameplate scanning. No call answering was found. — [FieldServiceSoftware.io](https://fieldservicesoftware.io/blog/ai-in-field-service/)
- ServiceTrade: no native AI voice was found. Third-party voice tools such as FieldCamp sync bookings into it. — [FieldCamp voice](https://fieldcamp.ai/voice/)
- Simpro, which was not on the assigned list, has a native "Pulse" AI receptionist. — [Simpro Pulse](https://www.simprogroup.com/features/pulse-ai-receptionist-field-service)

### Inferences
- The pricing gives the native agents a strong distribution advantage in the 1–10 truck segment. Jobber's $29 for 30 conversations makes a standalone AI receptionist that costs $150–$500/mo hard to justify for a Jobber shop that needs only basic after-hours capture. Independents will struggle on price in that segment and have to compete on quality: human handoff, trade-specific triage, pricing conversations and outbound calls.
- The native products are positioned mostly on overflow and after-hours calls, not as a primary CSR replacement. That leaves room for vendors that handle peak-hour primary answering, sales and replacement-quote calls, and live warm transfer.
- The platforms with no native agent (FieldEdge, Service Fusion, Successware, ServiceTrade, BuildOps) are the open lanes for third-party voice vendors, and incumbents already hold them via partnerships: Free2Grow, ZyraTalk and others.
- Lock-in mechanics: native agents tend to require the platform's own telephony (Workiz Genius Phone; ServiceTitan Phones). For contractors using another phone system, such as RingCentral or a call-tracking provider, this creates friction, and a third party can exploit that.

### Gaps
- No official ServiceTitan voice-agent price could be confirmed from a primary page; fetches were blocked. The $2.75/call figure is unconfirmed.
- I found no official customer or adoption counts for any native agent (Jobber, HCP, Workiz, FieldPulse), apart from Jobber's 200k beta conversations in 2025.
- The underlying LLM/voice vendors for the native agents are undisclosed.
- I could not confirm whether FieldEdge, ServiceTrade or BuildOps launched anything in Q3–Q4 2026.

## Q2. Partner/marketplace ecosystems, API openness and restrictions

### Takeaway
ServiceTitan became markedly more restrictive in 2026. It introduced a partner certification program with revenue share in June 2026, adopted API terms that require disclosure and approval of AI systems, and cut off Podium on 2026-09-15 after Podium built competing AI agents. This is the clearest evidence that the largest FSM is protecting its native AI voice revenue. Smaller FSMs remain partner-friendly, mainly because they lack native agents.

### Cited Findings
- ServiceTitan's API terms reserve the right to charge for the APIs. They bar AI systems from independently choosing which endpoints to call or what actions to take, and they treat use of an AI system without disclosure to and approval by ServiceTitan as a material breach. ServiceTitan may impose further conditions, such as requiring human authorization for write operations. Note that this text comes from a search summary of the terms, which could not be fetched directly. — [ServiceTitan API Terms](https://www.servicetitan.com/legal/api-terms); [FieldProxy API guide](https://www.fieldproxy.ai/guides/servicetitan-api)
- API access for customer-built or third-party integrations reportedly requires the higher "The Works" or Enterprise Plus tiers. Each customer generates credentials, and third-party apps are reviewed. Reported rate limits conflict: one source says 600 calls per 10 seconds per app per tenant, another 60 calls per second. — [Blurstudio](https://www.blurstudio.ai/knowledge/servicetitan-api); [FieldProxy](https://www.fieldproxy.ai/guides/servicetitan-api)
- A June 2026 certification program sets six standards: security, performance, predictability, data transparency, revenue share and "mutual benefit". One review says the criteria reference "reasonable economic arrangements comparable to other industries." Integrations now come in two tiers. — [FieldCamp: ServiceTitan integrations 2026](https://fieldcamp.ai/blog/servicetitan-integrations/)
- On the Podium cut-off, ServiceTitan emailed customers on 2026-08-12, delisted Podium on 2026-08-17 and ended the integration on 2026-09-15; one competitor blog gives 2026-08-31. About 1,000 shared customers were affected, per SaaStr. ServiceTitan says Podium's legacy agreement expired and Podium declined certification. Podium says the terms changed after it built a competing AI product and that revenue share was not part of the original deal. — [SaaStr](https://www.saastr.com/servicetitan-just-shut-off-podiums-integration-for-1000-shared-customers-agents-turned-a-9-year-partner-into-a-direct-competitor/); [TradeVulcan](https://tradevulcan.com/dispatch/servicetitan-podium-integration-ends-september-15-2026); [FieldCamp](https://fieldcamp.ai/blog/servicetitan-podium-integration-ending/)
- ServiceTitan's FY26 Q4 earnings (March 2026) cited "partner monetization" as a usage-revenue contributor alongside fintech and early Virtual Agents growth. — [Motley Fool Q4 FY26 transcript](https://www.fool.com/earnings/call-transcripts/2026/03/12/servicetitan-ttan-q4-2026-earnings-transcript/)
- Third-party AI voice vendors on or integrated with ServiceTitan include Avoca, which is listed on the ServiceTitan Marketplace and books directly into ServiceTitan, and several others claiming integrations, such as UnleashX. — [CallbotScore](https://callbotscore.com/servicetitan-ai-voice-agent/); [UnleashX guide](https://unleashx.ai/feeds/blog/integrating-voice-ai-servicetitan/)
- Partners on other FSMs: FieldEdge works with Free2Grow; Service Fusion with ZyraTalk; FieldPulse with Free2Grow and XAPP AI (pre-native). Workiz, Jobber and HCP are integrated by many standalone vendors through their APIs (e.g. NextPhone with Jobber). — sources in Q1; [NextPhone Jobber integration](https://www.getnextphone.com/blog/jobber-ai-receptionist-integration)

### Inferences
- A third-party AI voice vendor serving ServiceTitan customers now faces three risks: (a) certification plus revenue share, (b) restrictions on autonomous AI writes such as booking jobs, and (c) the risk of Podium-style de-platforming once it is seen as competitive. This raises the cost of entering the ServiceTitan base, which is the highest-value segment. Vendors already certified, such as Avoca, hold a defensible position.
- Jobber, HCP and Workiz have not publicly adopted comparable restrictions (none found), so in the SMB segment the constraint is price competition from native add-ons rather than API gating.

### Gaps
- I could not see the actual revenue-share percentage or the certification fee in ServiceTitan's program.
- I found no comparable API or AI-use terms for Jobber, Housecall Pro or Workiz, and could not confirm whether they have any.
- I have no complete list of ServiceTitan-certified AI voice partners as of Nov 2026.

## Q3. Market share / customer counts by segment; ServiceTitan public disclosures on AI

### Takeaway
ServiceTitan dominates the larger and PE-backed residential trades, with about 10,800 Active Customers (each over $10k in annual billings) and $82.1B GTV in FY26. Jobber (100k+ customers) and Housecall Pro dominate small shops. ServiceTitan's management calls virtual agents "early", but they are growing quickly: revenue and call volume more than doubled quarter over quarter in Q2 FY27. Strategy is shifting to an "agentic operating system", Max.

### Cited Findings
- FY26 (ended 2026-01-31): about 10,800 Active Customers, defined as parent organizations with over $10k in annualized billings, up 14% year over year and accounting for over 97% of billings. GTV was $82.1B, up from $68.5B. Revenue was $961M, up 24%. NDR was above 110% and GDR above 95%. — [ServiceTitan 10-K FY2026 (SEC)](https://www.sec.gov/Archives/edgar/data/1638826/000163882626000028/ttan-20260131.htm); [Yahoo Finance Q4 FY26 release](https://finance.yahoo.com/news/servicetitan-announces-fiscal-fourth-quarter-200500237.html); [TradingView 10-K summary](https://www.tradingview.com/news/tradingview:262c86c22b334:0-servicetitan-10-k-961m-revenue-1-73-eps-on-fy26-results/)
- Q4 FY26 call (March 2026): usage revenue growth drew on "early Virtual Agents growth" as well as fintech and partner monetization. — [Motley Fool Q4 FY26 transcript](https://www.fool.com/earnings/call-transcripts/2026/03/12/servicetitan-ttan-q4-2026-earnings-transcript/)
- Q1 FY27 call (2026-06-04): virtual agent offerings showed "strong early adoption", and new outbound calling and receptionist capabilities were added. — [Yahoo Q1 highlights](https://finance.yahoo.com/markets/stocks/articles/servicetitan-q1-earnings-call-highlights-230603380.html); [Motley Fool Q1 FY27 transcript](https://www.fool.com/earnings/call-transcripts/2026/06/05/servicetitan-ttan-q1-2027-earnings-transcript/)
- Q2 FY27 call (early September 2026): virtual agents remain early, but revenue and call volume each more than doubled sequentially. Adoption is concentrated in overflow and after-hours calls. The "Max" agentic OS has over 100 locations enrolled, with a target of 700 by fiscal year-end, and carries a $4–5M revenue headwind from the shift to Max. FY27 revenue guidance was raised to $1.139–1.144B. — [Yahoo Q2 FY27 summary](https://finance.yahoo.com/markets/stocks/articles/servicetitan-inc-q2-2027-earnings-123000022.html); [Drillr Q2 FY27](https://drillr.ai/stocks/TTAN/calls/2027-q2); [Benzinga full transcript](https://www.benzinga.com/news/26/09/61675337/full-transcript-servicetitan-q2-2027-earnings-call) (not fetched)
- Q3 FY27 results were not found. They are typically reported in early December, so they were likely not yet released as of 2026-11-23.
- A ServiceTitan survey of 1,000 contractors found 74% see AI as essential but only 25% use it (date unclear, cited June 2026). — [MarketingCode](https://www.marketingcode.com/industry-shift-pe-288-platforms-servicetitan-74-percent-ai-exit-multiple-jun-2026/)
- Jobber: over 100,000 customers and more than 400,000 service pros using it daily (company media page, 2026). — [Jobber media](https://www.getjobber.com/about/media/)
- Housecall Pro: positioned for 1–7 truck shops. An HCP analysis of about 2M tagged jobs said it represents about 11% of national HVAC job volume; this is a job-volume figure, not customer share. No current customer count was found. — [BDR](https://www.bdrco.com/blog/hvac-business-software-guide/); [BuiltOnTenth comparison](https://www.builtontenth.com/hvac-research/servicetitan-vs-housecall-pro-vs-fieldedge-cost-comparison)
- FieldEdge is positioned as the mid-market, QuickBooks-oriented, HVAC-rooted option; no customer count was found. — [SoftwareConnect](https://softwareconnect.com/roundups/best-hvac-service-software/)

### Inferences
- ServiceTitan's roughly 10.8k high-value customers are where per-call AI revenue is largest, and ServiceTitan is clearly working to capture that revenue: virtual agent revenue doubling quarter over quarter, Contact Center Pro, Max, and gatekeeping of partners. Its own description of adoption as "early" and limited to overflow and after-hours suggests primary inbound CSR replacement at large shops is still mostly uncaptured, whether by humans or by third parties.
- The SMB long tail (Jobber's 100k+, plus HCP and Workiz) has cheap native options available, but no adoption data was disclosed.

### Gaps
- No current customer counts were found for Housecall Pro, Workiz, FieldEdge, Service Fusion, Successware, ServiceTrade, BuildOps or FieldPulse.
- No product-level virtual agent revenue or customer count from ServiceTitan.
- No independent market-share data by segment; available market-size reports are low quality.

## Q4. Customer feedback on native AI features: what is lacking

### Takeaway
Direct, verifiable contractor feedback on native AI voice agents is sparse; review volume is "thin". The recurring complaints, mostly relayed by competing vendors, are: weak handoff or transfer to a human; generic answers to technical and pricing questions; poor handling of high-ticket sales calls; caps that silently drop calls to voicemail (Workiz); opaque, quote-only pricing (HCP); and limitation to overflow and after-hours use.

### Cited Findings
- ServiceTitan AI Voice Agent: review volume is "still thin" (Q2 2026). — [Toarn](https://toarn.com/insights/servicetitan-ai)
- Jobber AI Receptionist: rated 6.5/10, "promising but new and limited", by a site that aggregates Reddit sentiment. It has trouble with technical and pricing questions. A second-hand r/HVAC anecdote describes a lost $15k replacement job because the bot could not transfer to a human. — [Fieldcamp Jobber review](https://fieldcamp.ai/reviews/jobber/); [Kore Komfort](https://korekomfortsolutions.com/jobber-ai-vs-housecall-pro-ai-are-they-worth-the-price-tag/)
- Workiz: when the plan's conversation cap is hit, the AI stops answering and calls go to the next step, such as voicemail. — [Workiz FAQ](https://help.workiz.com/hc/en-us/articles/30176041143697-Genius-Answering-FAQ)
- Housecall Pro: no public price; quote only, add-on. As of February 2026, "booking fallback" and "call-handling improvements" were still on the coming-soon list, which implies those were gaps. — [Beside](https://www.beside.com/blog/housecall-pro-ai-phone-answering); [HCP Feb 2026 updates](https://www.housecallpro.com/resources/february-2026-product-updates/)
- ServiceTitan management says adoption centers on overflow and after-hours calls (Q2 FY27). — [Yahoo Q2 FY27 summary](https://finance.yahoo.com/markets/stocks/articles/servicetitan-inc-q2-2027-earnings-123000022.html)

### Inferences
- The likely differentiation for independents is: reliable warm transfer, trade-specific diagnostic triage, sales and replacement call handling, price-range conversations, outbound and recall campaigns, multi-location routing, and carrier-agnostic telephony.

### Gaps
- I could not access first-hand Reddit threads (r/HVAC, r/Plumbing, r/sweatystartup) or G2/Capterra reviews specific to ServiceTitan's or HCP's AI agents. Most feedback above is relayed by competitor blogs and should be treated as biased.

## Q5. Which segments are multi-platform (PE roll-ups etc.)

### Takeaway
PE roll-ups commonly inherit several FSMs from acquired shops, typically FieldEdge, Housecall Pro and Workiz at smaller targets. They usually migrate toward ServiceTitan and centralize call handling, which is the use case for ServiceTitan's Contact Center Pro. During migration, a platform-agnostic AI voice layer that books into multiple FSMs is a natural fit. Hard data on how many roll-ups run several FSMs was not found.

### Cited Findings
- ServiceTitan is the operating system at most $50M+ residential HVAC, plumbing and electrical platforms. Common post-close changes include migration to ServiceTitan or Housecall Pro and centralized call centers and scheduling. — [CT Acquisitions](https://ctacquisitions.com/how-pe-roll-ups-unlock-value-in-home-services/)
- Some PE buyers prefer targets not yet on ServiceTitan so they can apply their own playbook (ACHR, around the ServiceTitan IPO in December 2024 [PRE-2025, possibly stale]). — [ACHR News](https://www.achrnews.com/articles/164030-servicetitan-ipo-intends-dominance-amongst-all-trades)
- A cited count of 288 PE platforms in home services, from a marketing firm (June 2026, unverified). — [MarketingCode](https://www.marketingcode.com/industry-shift-pe-288-platforms-servicetitan-74-percent-ai-exit-multiple-jun-2026/)
- A study of 249 PE-acquired HVAC and plumbing companies found 92% take online bookings post-sale, up from 72%, and 27% load a booking or chat widget from an AI company after the sale, versus none before. The source is a substack and the methodology is not verified. — [Capital and Clarity](https://capitalandclarity.substack.com/p/pe-rollups-are-acquiring-their-own)
- Some PE roll-ups are acquiring their own tech stack. — [Capital and Clarity](https://capitalandclarity.substack.com/p/pe-rollups-are-acquiring-their-own)
- Contact Center Pro centralizes calls across locations and includes AI virtual agents. — [ServiceTitan](https://www.servicetitan.com/blog/webinar-recap-contact-center-pro)

### Inferences
- Roll-ups in the middle of a migration, running ServiceTitan plus legacy FieldEdge, HCP or Workiz instances, cannot use a single native agent across all locations. This is a structural gap for multi-FSM AI voice vendors. Once a roll-up is fully on ServiceTitan, Contact Center Pro, the virtual agents and the API restrictions push it toward native.

### Gaps
- No quantitative data was found on the share of PE platforms running more than one FSM, or on typical migration timelines.
