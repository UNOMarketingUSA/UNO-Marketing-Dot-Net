# UNO MARKETING: COMPLETE WEBSITE BLUEPRINT
### Production-Ready Site: Strategy, Copy, Wireframes, SEO & Design System

---

## HOW TO USE THIS DOCUMENT

This is a full production blueprint for the UNO Marketing website. Every page is written as final copy, not a summary or outline. It is organized in five parts:

1. **Brand & Design Foundation**: voice, typography, color, motion, and visual system
2. **Full Sitemap**
3. **Page-by-Page Build**: 15 pages, each with Purpose, SEO, Wireframe, Full Copy, CTA Placements, Visual Recommendations, Motion Ideas
4. **Case Study System**: reusable template plus two fully written case studies
5. **Conversion Offer System**: the four core CTAs used sitewide

---

---

# PART 1: BRAND & DESIGN FOUNDATION

## 1.1 Positioning Statement

UNO Marketing is a performance marketing system, not an ad agency. We build the media, data, and AI infrastructure that turns advertising budgets into measurable, compounding revenue. We don't sell clicks or impressions. We engineer profitable growth, and we prove it in the numbers our clients actually care about: CPL, ROAS, CAC, LTV, and net new revenue.

## 1.2 Brand Personality

| Trait | What it means on the page |
|---|---|
| **Confident, not arrogant** | State results plainly. Let the numbers carry the weight. |
| **Technical, not cold** | We're built on data and AI, but every page speaks to a business outcome a human cares about. |
| **Editorial, not salesy** | Write like a McKinsey report crossed with a Series B SaaS product page, not like a marketing brochure. |
| **Precise, not vague** | Replace adjectives with numbers wherever possible. |

## 1.3 Voice & Tone Rules

- Never say "clicks" or "impressions" as a success metric: always tie back to revenue, CAC, LTV, or profit.
- Avoid clichés: "cutting-edge," "synergy," "game-changing," "next-level," "results-driven" (banned list). Replace with specifics.
- Every H2 or major claim should be falsifiable or backed by a number, a mechanism, or a named methodology.
- Short sentences carry weight. One idea per sentence. Long paragraphs are broken into scannable fragments.
- Use "we" sparingly. Favor active, declarative statements ("Every dollar is tracked to revenue." not "We believe every dollar should be tracked to revenue.").

## 1.4 Typography System: *(rebuilt around the UNO Marketing logo)*

- **Display / Headlines:** *Fraunces* (a warm, characterful variable serif) at large scale (64–140px hero), weights 400–600, with selective italics on emphasis words. This is a deliberate departure from the grotesque-sans headlines every dark performance-agency site defaults to. It signals editorial confidence instead of generic "tech company."
- **Body Copy:** *Inter*, 16–18px, 1.6 line-height, weight 400/500. Keeps long-form copy (case studies, service detail) easy to read against the serif headlines.
- **Data / Metrics / Labels:** *IBM Plex Mono*, retained for every statistic, dashboard number, KPI label, and eyebrow tag. This is the thread that still signals "built on data" even inside a warmer visual system.
- **Accent / Handwritten:** a marker-style hand-lettered display face (same family as the logo's wordmark, e.g., *Caveat* or *Permanent Marker*), used sparingly for eyebrow tags, margin annotations, and hand-drawn callouts circling key stats. This is the signature differentiator: **AI-grade data, annotated by hand.** It visualizes a human strategist directing the system, not a faceless dashboard running itself.
- **Numerals:** Tabular figures throughout.

## 1.5 Color Palette: *(built around the logo's coral)*

**Foundation**
- Cream (bright section background): `#FBF1E7`
- Warm White (cards, text-on-dark surfaces): `#FFFCF8`
- Charcoal (dark section background, warm-toned, not cold black): `#2A211D`
- Deep Charcoal (gradient stop): `#1C1613`
- Ink Text (body copy on Cream): `#241C1A`
- Muted Taupe (secondary text, baselines): `#8A7B72`

**Signal Colors (brand accent system)**
- **UNO Coral** (primary brand + every CTA button): `#FA6F61`, pulled directly from the logo.
- **UNO Teal** (positive performance data: ROAS up, CAC down, revenue up): `#1F6B5C`
- **Amber** (before-state / inefficiency callouts in comparisons): `#E8A33D`
- **Soft Blush** (tint of coral for card backgrounds, hover states, badges): `#FDE4DF`

**Gradients**
- Hero gradient: Charcoal → Deep Charcoal with a soft coral glow (12–18% opacity) behind headlines and section dividers, replacing the blue/violet "tech glow" nearly every competitor site uses.

**Data Visualization Palette**
Coral, UNO Teal, Amber, and Muted Taupe for baseline/competitor lines, always paired with a hand-drawn annotation mark (a circle, arrow, or underline) rather than a glossy neon gradient, so every chart reads as "insight," not "dashboard wallpaper."

## 1.6 Spacing & Grid

- 12-column grid, 1440px max content width, 96px outer margin on desktop, 24px on mobile.
- Section vertical rhythm: 160px padding top/bottom on desktop for Charcoal/Cream transitions, 96px mobile.
- Generous whitespace inside Cream sections; denser, data-rich layouts permitted only inside Charcoal sections (dashboards, metrics, charts), styled to feel like **a strategist's annotated whiteboard**, not a cold control room.

## 1.7 Iconography

Hand-drawn, single-stroke line icons that echo the logo's loose, slightly imperfect linework: sketched arrows, funnels, circles, and simple symbols rather than engineered geometric glyphs. This is a deliberate move away from the clinical SaaS-icon look most performance agencies use: icons should feel like they were drawn by a strategist during a working session, then cleaned up just enough to scale across the site.

## 1.8 Photography Style

- No stock photography of "people in suits shaking hands," and no cold blue-toned corporate stock.
- Preferred: warm, natural-light, documentary-style photography of real teams working (candid, not posed); real dashboard screenshots (blurred/anonymized client data) shown as warm-lit screens rather than moody blue-black UI captures.
- Where humans appear (About, Careers), grade photography warm to match the Cream/Coral palette. Never desaturated.

## 1.9 Illustration Style

- Hand-drawn line diagrams (in the logo's linework style) used for concepts, including funnels, flow diagrams, and budget-allocation sketches, layered beside or on top of clean, crisp data charts. The contrast is the point: a sketched idea next to hard data, visualizing human strategy directing an AI system.
- No 3D renders, no glossy node-network globes. UNO's visual distinctiveness comes from warmth and hand-craft, not sci-fi tech imagery. This is what separates the site from every "dark dashboard" agency competitor.

## 1.10 Motion & Animation Principles

- **Scroll-triggered reveals:** content fades up 20px with a 400ms ease-out as it enters viewport; stagger children by 80ms.
- **Animated metric counters:** numbers count up from 0 to final value in Coral or UNO Teal tabular mono over 1.2s; on completion, a **hand-drawn circle or underline draws itself around the number** (SVG stroke-dashoffset animation). This is the site's signature motion moment, tying every stat back to the logo's hand-drawn mark.
- **Chart draw-in:** line/bar charts animate from baseline to final state in Coral/Teal over 1–1.5s; once settled, a small hand-drawn arrow sketches in, pointing at the key data point.
- **Sticky scroll storytelling:** on Process and AI Optimization pages, a left-fixed panel narrates steps while the right panel's visual updates as the user scrolls.
- **Cursor-reactive warm glow:** hero background gradient subtly drifts toward cursor position in soft coral (desktop only, disabled on touch).
- **Hover micro-interactions:** service cards lift 4px with a soft warm shadow and the hand-drawn icon "draws itself" on hover (stroke-dashoffset animation reads naturally since icons are literal line art); buttons fill with Coral via a left-to-right sweep, 250ms.

## 1.11 Page Transitions

- Route transitions: 300ms crossfade + 20px vertical slide; persistent header/nav does not re-render between pages.
- Charcoal-to-Cream section transitions use a soft, irregular **torn-paper / hand-cut edge** shape instead of a hard rectangle or clinical diagonal wipe: a small, tactile detail that reinforces the handcrafted brand feel at every scroll.

## 1.12 Dashboard Mockup Concepts

Recurring visual motif across Home, AI Optimization, and Data Intelligence: a stylized "UNO Command Console," rendered on a warm Charcoal background with Coral/Teal/Amber accent charts, and **annotated with hand-drawn circles, arrows, and margin notes**, as if a strategist had just marked it up. Contents:
- Spend allocation across channels (animated treemap in Coral/Teal/Amber blocks)
- Live ROAS trendline (Teal) vs. target line (dashed Muted Taupe)
- Budget reallocation alerts, each with a hand-drawn arrow pointing to the shift ("Shifted $12,400 from Display → Search based on predicted ROAS lift")
- A cross-channel attribution funnel, annotated with a handwritten-style note at the qualified-lead stage ("this is the number that matters")

## 1.13 Graph / Chart Concepts

- Before/After ROAS bar comparison (Amber "before" vs. UNO Teal "after")
- CAC decline line chart over 6/12 months, rendered in Coral
- Budget allocation Sankey diagram (spend flowing into channels, channels flowing into revenue) in Coral/Teal/Amber
- Lead quality funnel (volume vs. qualified volume), with a hand-drawn bracket highlighting the gap traditional agencies ignore
- Forecast vs. actual performance band chart (AI prediction confidence interval), with a hand-drawn annotation marking the point of divergence

## 1.14 Interactive Elements

- **ROI Calculator** (Homepage + Contact): user inputs current monthly ad spend + industry → tool estimates potential CAC reduction / ROAS lift range, styled on a Cream background with a Coral submit button, ending in a CTA to book a Growth Assessment.
- **Channel Mix Explorer** (Services hub): a hand-drawn-style diagram. Click a channel (Search, Social, Programmatic) and a sketched line "draws" from that node to a mini case metric.
- **Live Dashboard Widget** (AI Optimization + Data Intelligence): an animated, looping mock dashboard embedded directly in the page, styled per the Command Console concept above (not a static image, not a cold blue-black UI capture).
- **Industry Selector** (Industries page): tabbed/filterable interface on Cream background. Select an industry, and content cross-fades to show relevant stats, channels, and case studies.

---

---

# PART 2: FULL SITEMAP

```
uno-marketing.com/
├── / ......................................... Home
├── /services .................................. Services (hub)
│   ├── /services/paid-search .................. Paid Search
│   ├── /services/paid-social ................... Paid Social
│   ├── /services/programmatic .................. Programmatic Media
│   ├── /services/ai-optimization ............... AI Media Optimization
│   ├── /services/data-intelligence ............. Data Intelligence
│   └── /services/content-marketing ............. Content Marketing
├── /industries .................................. Industries (hub, tabbed by vertical)
├── /case-studies ................................. Case Studies (index)
│   └── /case-studies/[client-slug] ............. Individual case study (template)
├── /process ....................................... Our Process
├── /about ......................................... About
├── /insights ...................................... Insights (blog/resources hub)
│   └── /insights/[article-slug] ................ Individual article
├── /careers ....................................... Careers
└── /contact ....................................... Contact
```

**Global navigation (header):** Services (mega-menu dropdown with 6 sub-services + featured case study) · Industries · Case Studies · Process · About · Insights · **Book a Growth Assessment** (primary CTA button, persistent).

**Footer navigation:** full sitemap links, office locations, social, privacy/terms, and a secondary email capture ("Get monthly performance benchmarks").

---

---

# PART 3: PAGE-BY-PAGE BUILD

---

## PAGE 1: HOME (`/`)

### Purpose
Establish UNO as an AI-powered performance marketing system (not an agency), prove credibility through hard metrics in the first viewport, and route every visitor toward a single conversion action: booking a Growth Assessment. This page must work for a CMO skimming for 20 seconds and for a CFO reading every line for proof.

### SEO
- **Primary keyword:** performance marketing agency
- **Secondary keywords:** AI marketing agency, ROAS agency, paid media agency, performance marketing company, growth marketing agency
- **Suggested URL:** `/`
- **Meta title:** UNO Marketing | AI-Powered Performance Marketing & Paid Media
- **Meta description:** UNO Marketing engineers profitable growth through AI-driven paid search, paid social, and programmatic media. Lower CAC, higher ROAS, measurable revenue, not vanity metrics.
- **H1:** We Don't Sell Clicks. We Engineer Profitable Growth.
- **H2 structure:** Every Dollar, Accounted For / What We Do / Why UNO / How We Work / Real Results / Industries We Grow / Built On / Frequently Asked Questions
- **Internal linking:** links to all 6 service pages, Industries, Case Studies, Process, About, Contact
- **Schema:** Organization, WebSite (with SearchAction), BreadcrumbList; FAQPage schema for the FAQ section

### Wireframe

```
[HEADER: sticky, transparent-over-hero, solidifies on scroll]
 Logo | Services ▾ | Industries | Case Studies | Process | About | Insights | [Book a Growth Assessment →]

[HERO: dark section, full viewport height]
 Eyebrow label (mono font): "PERFORMANCE MARKETING, ENGINEERED"
 H1 (huge, 2-line)
 Supporting subhead (1-2 lines, lighter weight)
 [Primary CTA button] [Secondary CTA - ghost button]
 Below fold: animated live-metric ticker strip (4 stats, counting up)

[SECTION: PROOF BAR / LOGOS]
 "Trusted by growth-stage and enterprise brands across 10 industries"
 Client logo row (grayscale, brighten on hover), placeholder logos

[SECTION: METRICS, dark]
 Eyebrow: "THE NUMBERS THAT MATTER"
 4-column animated counter grid: Avg. CAC Reduction / Avg. ROAS Lift / Ad Spend Managed / Client Retention Rate

[SECTION: SERVICE OVERVIEW, light]
 Eyebrow + H2: "What We Do"
 6-card grid (Paid Search, Paid Social, Programmatic, AI Optimization, Data Intelligence, Content Marketing)
 Each card: icon, title, 2-line description, "Learn more →"

[SECTION: WHY UNO, dark, split layout]
 Left: H2 "We Optimize for Business Outcomes, Not Platform Metrics"
 Right: 3 stacked before/after comparison rows (Leads → Qualified Leads, Traffic → Revenue, Clicks → Profit)

[SECTION: PROCESS, light]
 Eyebrow + H2: "How We Work"
 Horizontal 7-step process rail (Discover, Research, Strategy, Launch, Measure, Optimize, Scale), sticky scroll on desktop
 CTA under: "See our full methodology →"

[SECTION: RESULTS / CASE STUDY HIGHLIGHTS, dark]
 Eyebrow + H2: "Real Campaigns. Real Revenue."
 3-card case study carousel with client industry tag, headline metric, mini-chart thumbnail
 [View all case studies →]

[SECTION: INDUSTRIES, light]
 Eyebrow + H2: "Built for Complex, High-Stakes Industries"
 10-tile grid (Healthcare, Finance, Home Services, Legal, Ecommerce, B2B SaaS, Automotive, Retail, Professional Services, Enterprise)

[SECTION: TESTIMONIALS, dark]
 Eyebrow + H2: "What Growth Leaders Say"
 3-slide testimonial carousel (placeholder quotes + name/title/company + headshot placeholder)

[SECTION: TECHNOLOGY STACK, light]
 Eyebrow + H2: "Built On the Platforms That Move Revenue"
 Logo grid: Google Ads, Microsoft Ads, Meta, TikTok, LinkedIn, The Trade Desk, GA4, HubSpot, Salesforce, Looker/Tableau

[SECTION: FAQ, light]
 Eyebrow + H2: "Common Questions"
 Accordion, 6 questions

[SECTION: FINAL CTA, dark, full-bleed gradient]
 H2: "Your Budget Is Already Being Spent. Let's Make Sure It's Working."
 [Primary CTA] [Secondary CTA]

[FOOTER: dark]
 4-column sitemap + office info + newsletter signup + social + legal row
```

### Full Copy

**Header nav labels:** Services · Industries · Case Studies · Process · About · Insights. CTA button: **Book a Growth Assessment**

**HERO**

Eyebrow: `PERFORMANCE MARKETING, ENGINEERED`

H1: **We Don't Sell Clicks. We Engineer Profitable Growth.**

Supporting subhead: UNO Marketing builds AI-driven paid media systems that lower acquisition costs, raise ROAS, and turn advertising budgets into predictable revenue, across search, social, and programmatic.

Primary CTA: **Book a Growth Assessment →**
Secondary CTA: **See Our Results**

Live-metric ticker (animated counters, looping):
`38% avg. CAC reduction` · `3.4x avg. ROAS lift` · `$210M+ ad spend managed` · `91% client retention`

**PROOF BAR**

"Trusted by growth-stage and enterprise brands across healthcare, finance, ecommerce, and B2B SaaS."
*(Client logo strip: UCI Health, Amazon, Fabletics, VMware, Robbins Bros, Levin Law)*

**METRICS SECTION**

Eyebrow: `THE NUMBERS THAT MATTER`
H2: **Every Dollar, Accounted For**

- **38%** average reduction in Cost Per Lead within the first 90 days
- **3.4x** average ROAS lift across managed accounts
- **$210M+** in annual ad spend managed across paid channels
- **91%** client retention rate, year over year

Sub-copy: These aren't projections. They're trailing 12-month averages across our active client portfolio, recalculated quarterly.

**SERVICE OVERVIEW**

Eyebrow: `WHAT WE DO`
H2: **One Team. Every Channel. One Number That Matters: Return.**

1. **Paid Search**: Google Ads, Microsoft Ads, YouTube, and Performance Max campaigns built around search intent, not just keyword volume. *Learn more →*
2. **Paid Social**: Meta, TikTok, LinkedIn, Pinterest, and X campaigns engineered for qualified conversions, not cheap engagement. *Learn more →*
3. **Programmatic Media**: Display, native, CTV, OTT, audio, and DOOH, bought programmatically and optimized against real business outcomes. *Learn more →*
4. **AI Media Optimization**: Machine learning models that predict performance, reallocate budget, and surface wasted spend before it happens. *Learn more →*
5. **Data Intelligence**: Attribution, GA4, server-side tracking, and executive dashboards that show the truth behind every channel. *Learn more →*
6. **Content Marketing**: Landing pages, conversion copy, SEO content, and ad creative built to convert, not just to look good. *Learn more →*

**WHY UNO**

Eyebrow: `WHY UNO`
H2: **We Optimize for Business Outcomes. Not Platform Metrics.**

Body: Most agencies report what the ad platform tells them to report. We go further, connecting every impression to a lead, every lead to a sale, and every sale to lifetime value. That's the difference between managing a budget and growing a business.

Comparison rows:
- Instead of optimizing for **leads**, we optimize for **qualified leads.**
- Instead of optimizing for **traffic**, we optimize for **revenue.**
- Instead of maximizing **clicks**, we maximize **profit.**

Closing line: Platform dashboards stop at the conversion event. We keep going, through your CRM, your sales cycle, and your P&L, because that's where the real answer lives.

**PROCESS**

Eyebrow: `HOW WE WORK`
H2: **A Methodology Built to Never Stop Optimizing**

Discover → Research → Strategy → Launch → Measure → Optimize → Scale

One-line summary: Optimization isn't a phase. It's the operating system underneath everything we build. *See our full methodology →*

**RESULTS / CASE STUDY HIGHLIGHTS**

Eyebrow: `REAL CAMPAIGNS. REAL REVENUE.`
H2: **Proof, Not Promises**

Card 1, Healthcare (multi-location provider): **CPL down 41%**, lead volume up 62% in 6 months. *Read the case study →*
Card 2, Ecommerce (DTC retail brand): **ROAS up from 1.9x to 5.2x** in 9 months while scaling spend 3x. *Read the case study →*
Card 3, B2B SaaS: **CAC down 35%**, pipeline-qualified leads up 78%. *Read the case study →*

CTA: **View All Case Studies →**

**INDUSTRIES**

Eyebrow: `WHO WE GROW`
H2: **Built for Complex, High-Stakes Industries**

Body: Regulated, high-consideration, and high-competition categories require more than platform defaults. We build compliant, conversion-accountable systems for:

Healthcare · Finance · Home Services · Legal · Ecommerce · B2B SaaS · Automotive · Retail · Professional Services · Enterprise

CTA: **See Industry-Specific Results →**

**TESTIMONIALS** *(placeholder, replace with client quotes at launch)*

> "UNO found $180K a year in wasted spend inside the first quarter, money our previous agency called 'normal platform variance.'"
> **VP of Marketing, National Home Services Brand** *(placeholder)*

> "They report on revenue, not reach. That single shift changed how our whole executive team thinks about our marketing budget."
> **CMO, Series C SaaS Company** *(placeholder)*

> "Our CAC dropped for the first time in three years, and it stayed down."
> **Director of Growth, DTC Ecommerce Brand** *(placeholder)*

**TECHNOLOGY STACK**

Eyebrow: `BUILT ON`
H2: **The Platforms We Build On, and Build Beyond**

Google Ads · Microsoft Advertising · Meta Ads Manager · TikTok Ads · LinkedIn Campaign Manager · The Trade Desk · GA4 · Google Tag Manager (server-side) · HubSpot · Salesforce · Looker Studio / Tableau · CallRail

Sub-copy: Platforms give us the levers. Our AI layer and data infrastructure decide how to pull them.

**FAQ**

1. **How is UNO different from a traditional media buying agency?**
   We build the AI and data infrastructure that most agencies rent from a platform's default settings. Our optimization decisions are based on your revenue data, not just platform-reported conversions.

2. **What size of ad budget do you work with?**
   We typically work with brands spending $30K+ per month across paid channels. Our systems are built to scale with you, not lock you into a fixed retainer structure.

3. **Do you require long-term contracts?**
   We don't require long-term contracts. We ask new clients to commit to an initial 90-day engagement, which gives us the time needed to build, optimize, and gather enough performance data to deliver meaningful results.

4. **How quickly will we see results?**
   Most clients see measurable CPL or ROAS movement within 60–90 days, with compounding gains as our AI models accumulate more of your first-party data.

5. **Can you work alongside our in-house marketing team?**
   Yes. Most of our client relationships are hybrid, with UNO managing paid media execution and data infrastructure while in-house teams own brand and product marketing.

6. **What does a Growth Assessment actually involve?**
   A working session (typically 45 minutes) where we audit your current account structure, spend allocation, and tracking setup, then show you, in numbers, where budget is likely being wasted.

**FINAL CTA**

H2: **Your Budget Is Already Being Spent. Let's Make Sure It's Working.**
Subhead: A Growth Assessment takes 45 minutes and tells you exactly where your marketing budget is underperforming.

Primary CTA: **Book a Growth Assessment →**
Secondary CTA: none, single strong primary CTA

**FOOTER**

Column 1 (Services): Paid Search · Paid Social · Programmatic · AI Optimization · Data Intelligence · Content Marketing
Column 2 (Company): About · Process · Careers · Insights · Contact
Column 3 (Resources): Case Studies · Industries · ROI Calculator · Performance Review
Column 4 (Newsletter): "Monthly performance benchmarks, no fluff." [Email input] [Subscribe]

Legal row: © UNO Marketing. Privacy Policy · Terms of Service · Accessibility
Social icons: LinkedIn · X · Instagram · YouTube

### CTA Placements
1. Header (persistent): Book a Growth Assessment
2. Hero: Primary, Book a Growth Assessment; Secondary, See Our Results (anchor scroll to Results section)
3. End of Process section: See our full methodology (links to `/process`)
4. End of Results section: View All Case Studies (links to `/case-studies`)
5. End of Industries section: See Industry-Specific Results (links to `/industries`)
6. Final CTA block: Book a Growth Assessment (primary only)
7. Footer: Newsletter signup capture

### Visual Recommendations
- Hero background: warm Charcoal → Deep Charcoal gradient with a soft coral glow, overlaid with a slow-drifting hand-drawn line animation (connected sketch-marks, not a cold 3D node network) suggesting a living system a human is steering.
- Metrics section: large tabular-mono numerals in UNO Teal, each with a hand-drawn coral circle that draws itself around the number as it finishes counting up.
- Service cards: line-icon that "draws" on hover, subtle 4px lift with shadow.
- Why UNO section: split screen. Left text on Ink background, right side shows 3 horizontal bars per comparison (short amber bar labeled "Leads," long green bar labeled "Qualified Leads," etc.) animating on scroll.
- Case study cards: real (blurred/placeholder) dashboard screenshot thumbnails with a colored metric badge overlay.

### Motion Ideas
- Ticker strip counts up once on initial hero load, then subtly loops/pulses every 30s.
- Process rail: horizontal sticky-scroll where the active step highlights and a connecting line "fills in" as the user scrolls.
- Testimonial carousel: auto-advances every 6s, pauses on hover, swipe-enabled on mobile.
- Final CTA gradient background subtly animates (slow hue drift between blue/violet) to create urgency without being distracting.

---

## PAGE 2: SERVICES HUB (`/services`)

### Purpose
Serve as the mega-menu landing destination and channel-agnostic proof point: no matter which channel a prospect is researching, this page reframes the conversation around unified strategy and outcomes, then routes to the specific service page relevant to their need.

### SEO
- **Primary keyword:** performance marketing services
- **Secondary keywords:** paid media services, digital advertising agency services, full-funnel marketing agency
- **Suggested URL:** `/services`
- **Meta title:** Performance Marketing Services | Paid Search, Social, Programmatic & AI | UNO Marketing
- **Meta description:** Explore UNO Marketing's full-funnel performance services, including paid search, paid social, programmatic, AI optimization, data intelligence, and content, all built around ROI.
- **H1:** Every Channel. One System. One Number That Matters.
- **H2 structure:** How the System Works / Explore Our Services / Why a System (Not a Silo) / Talk to a Strategist
- **Internal linking:** all 6 service pages, Process, Case Studies, Industries
- **Schema:** Service (ItemList of 6 services), BreadcrumbList

### Wireframe
```
[HERO: dark]
 Eyebrow, H1, subhead, interactive "Channel Mix Explorer" diagram
[SECTION: 6-card grid, light]
 Full description card per service with stat + CTA
[SECTION: WHY A SYSTEM, dark]
 Explains cross-channel data feedback loop
[CTA BAND]
```

### Full Copy

Eyebrow: `WHAT WE DO`
H1: **Every Channel. One System. One Number That Matters.**
Subhead: Paid search, paid social, and programmatic media don't operate in silos at UNO. They share one data layer, one AI optimization engine, and one goal: profitable growth.

*[Interactive Channel Mix Explorer: click Search / Social / Programmatic / AI / Data / Content to preview a mini-metric and jump to that service page]*

**Service Cards:**

1. **Paid Search**: Google Ads, Microsoft Ads, YouTube, Performance Max, Shopping, and local campaigns built around search intent. *Avg. CPL reduction: 34%.* → `/services/paid-search`
2. **Paid Social**: Meta, Instagram, TikTok, LinkedIn, Pinterest, and X campaigns optimized for qualified conversions. *Avg. CAC reduction: 29%.* → `/services/paid-social`
3. **Programmatic Media**: Display, native, CTV, OTT, audio, and DOOH bought against real audiences and real outcomes. *Avg. reach efficiency gain: 44%.* → `/services/programmatic`
4. **AI Media Optimization**: Predictive bidding, budget allocation, and creative testing models that compound over time. *Avg. wasted spend recovered: $18K/mo.* → `/services/ai-optimization`
5. **Data Intelligence**: Attribution, GA4, server-side tracking, and executive dashboards built on your revenue data. *100% of channels tied to CRM revenue.* → `/services/data-intelligence`
6. **Content Marketing**: Landing pages, conversion copy, SEO content, and ad creative engineered to convert. *Avg. landing page CVR lift: 22%.* → `/services/content-marketing`

**WHY A SYSTEM, NOT A SILO**

H2: **Channels Don't Grow Revenue in Isolation. Systems Do.**
Body: A Meta campaign that drives cheap leads is worthless if Google Ads can't tell which leads closed. A programmatic display campaign that builds awareness is invisible if your attribution model only credits last-click search. UNO connects every channel to one data layer, so budget moves toward whatever is actually producing revenue, not whatever platform is easiest to report on.

CTA Band: H2 "Not Sure Which Channel Mix Is Right for You?" → **Book a Growth Assessment →**

### CTA Placements
Header persistent CTA; mid-page Channel Mix Explorer (soft engagement, not a form); each service card links to its page; closing CTA band → Growth Assessment.

### Visual Recommendations
Interactive hand-drawn-style diagram hero showing channels as sketched nodes/arrows feeding into one central "Revenue" node, rendered in the logo's loose linework over a warm Charcoal background. Cards use the hand-drawn icon set with a small animated stat counter in UNO Teal.

### Motion Ideas
Connecting lines animate as if being hand-drawn in real time (stroke draws on), with a small coral dot traveling along each completed line to suggest live data flow between channels.

---

## PAGE 3: PAID SEARCH (`/services/paid-search`)

### Purpose
Convert high-intent prospects researching search advertising by demonstrating technical command of Google/Microsoft Ads ecosystems and proving intent-based optimization beats keyword-volume-based management.

### SEO
- **Primary keyword:** Google Ads agency
- **Secondary keywords:** paid search agency, PPC management agency, Performance Max management, Microsoft Ads agency, search intent optimization
- **Suggested URL:** `/services/paid-search`
- **Meta title:** Google Ads & Paid Search Agency | Performance Max, YouTube, Shopping | UNO Marketing
- **Meta description:** UNO Marketing manages Google Ads, Microsoft Ads, YouTube, Performance Max, and Shopping campaigns built around search intent, not keyword volume. Lower CPL, higher qualified lead volume.
- **H1:** Paid Search Built Around Intent, Not Just Keywords
- **H2 structure:** What We Manage / How We Optimize Beyond the Platform / Search Intent Optimization / Our Process for Search / Results in Search / FAQ
- **Internal linking:** AI Optimization, Data Intelligence, relevant case study, Contact
- **Schema:** Service, FAQPage, BreadcrumbList

### Wireframe
```
[HERO: dark] Eyebrow / H1 / subhead / CTA / stat strip
[WHAT WE MANAGE: light] icon grid: Google Ads, Microsoft Ads, YouTube, PMax, Shopping, Local
[SEARCH INTENT: dark, split] explanation + diagram of intent tiers
[PROCESS: light] 4-step search-specific workflow
[CASE STUDY CALLOUT: dark]
[FAQ: light]
[CTA]
```

### Full Copy

Eyebrow: `PAID SEARCH`
H1: **Paid Search Built Around Intent, Not Just Keywords**
Subhead: Google Ads, Microsoft Ads, YouTube, Performance Max, and Shopping, structured around what a searcher actually wants, not just what they typed.
Primary CTA: **Book a Growth Assessment →**  Secondary CTA: **See a Paid Search Case Study**

Stat strip: `34% avg. CPL reduction` · `2.8x avg. search ROAS` · `61% avg. qualified lead increase`

**WHAT WE MANAGE**

- **Google Ads**: Search, Display, Shopping, App, and Local campaigns, structured for both immediate conversion and long-term account health (Quality Score, impression share, auction insights).
- **Microsoft Ads**: Often overlooked, frequently 15–30% cheaper CPCs with comparable intent, built as a core channel, not an afterthought.
- **YouTube**: In-stream and Shorts campaigns for upper-funnel intent capture and remarketing sequences tied to search behavior.
- **Performance Max**: Structured with first-party data feeds, negative audience signals, and asset-group segmentation to prevent PMax from cannibalizing brand search or wasting spend on low-intent placements.
- **Shopping**: Feed optimization, product-level bidding, and margin-aware bid strategies for ecommerce and retail clients.
- **Local Campaigns**: Location-based bidding and call-tracking integration for home services, healthcare, legal, and automotive clients with physical service areas.

**SEARCH INTENT OPTIMIZATION**

H2: **We Optimize Beyond the Platform's Definition of "Conversion"**
Body: Google and Microsoft optimize toward the conversion event you tell them to optimize toward, usually a form fill or a call. That's the platform's finish line. It's not yours.

We layer in:
- **Search intent tiers**: classifying queries by commercial intent (transactional, comparison, informational) so budget concentrates where buyers are closest to a decision.
- **Offline conversion imports**: feeding closed-won revenue and lead quality data back into Google/Microsoft so their bidding algorithms optimize toward *sales*, not just submissions.
- **Negative keyword and audience layering**: continuously trimming spend on queries that generate volume without qualification.
- **Query-level margin awareness** (ecommerce): bidding more aggressively on products with better unit economics, not just better conversion rate.

**OUR PROCESS FOR SEARCH**

1. **Account Audit**: full structural, Quality Score, and wasted-spend audit within the first 2 weeks.
2. **Intent Mapping**: keyword and audience segmentation by commercial intent tier.
3. **Build & Launch**: campaign architecture rebuilt or restructured around intent tiers and conversion data quality.
4. **Continuous Optimization**: weekly bid, budget, and query-level refinement, backed by the AI Optimization layer (see AI Media Optimization).

**CASE STUDY CALLOUT**

"A regional healthcare provider cut Cost Per Lead by 41% in 90 days by restructuring Performance Max around verified appointment bookings instead of form submissions." → **Read the full case study →**

**FAQ**

1. **Do you manage Microsoft Ads even if our budget is small?** Yes. For most clients it's a 10–15% budget allocation that often outperforms Google on cost efficiency.
2. **How do you handle Performance Max's lack of transparency?** Through first-party data feeds, asset-group segmentation, and placement exclusions layered on top of PMax's automation, plus search-term insights reporting.
3. **Will you rebuild our entire account?** Only if the existing structure is actively limiting performance. We rebuild with intent, not out of habit.

**CTA:** H2 "See Where Your Search Budget Is Leaking" → **Book a Growth Assessment →**

### CTA Placements
Hero primary/secondary; case study callout; closing CTA band; sticky "Book a Growth Assessment" in header.

### Visual Recommendations
Search intent tier diagram (funnel-style: Informational → Comparison → Transactional, with budget-weight visualization). Dashboard mockup showing Quality Score and impression share trending upward.

### Motion Ideas
Intent funnel animates budget "flowing" more heavily toward the transactional tier as the diagram loads. Stat strip counts up on scroll into view.

---

## PAGE 4: PAID SOCIAL (`/services/paid-social`)

### Purpose
Position UNO as a paid social partner focused on conversion quality across Meta, TikTok, LinkedIn, Pinterest, and X, countering the perception that social ads only drive cheap, low-quality volume.

### SEO
- **Primary keyword:** paid social agency
- **Secondary keywords:** Meta ads agency, TikTok ads agency, LinkedIn ads agency, Facebook advertising agency, social media advertising management
- **Suggested URL:** `/services/paid-social`
- **Meta title:** Paid Social Advertising Agency | Meta, TikTok, LinkedIn | UNO Marketing
- **Meta description:** UNO Marketing manages Meta, Instagram, TikTok, LinkedIn, Pinterest, and X advertising built for qualified conversions and revenue, not cheap engagement.
- **H1:** Social Advertising That Converts, Not Just Engages
- **H2 structure:** Platforms We Manage / Beyond Engagement Metrics / Creative Testing at Scale / Our Process for Social / Results in Social / FAQ
- **Internal linking:** Content Marketing (creative), AI Optimization, Data Intelligence, relevant case study
- **Schema:** Service, FAQPage, BreadcrumbList

### Wireframe
```
[HERO: dark]
[PLATFORMS: light, 6-tile grid]
[BEYOND ENGAGEMENT: dark, split with before/after chart]
[CREATIVE TESTING: light]
[PROCESS: light]
[CASE STUDY: dark]
[FAQ]
[CTA]
```

### Full Copy

Eyebrow: `PAID SOCIAL`
H1: **Social Advertising That Converts, Not Just Engages**
Subhead: Meta, Instagram, TikTok, LinkedIn, Pinterest, and X campaigns built around one question: does this lead close?
Primary CTA: **Book a Growth Assessment →**  Secondary CTA: **See a Paid Social Case Study**

Stat strip: `29% avg. CAC reduction` · `3.1x avg. social ROAS` · `47% avg. lead quality improvement`

**PLATFORMS WE MANAGE**

- **Meta (Facebook & Instagram)**: Advantage+ campaign structuring, creative rotation testing, and CAPI (Conversions API) server-side tracking for iOS-resilient measurement.
- **TikTok**: Native-feeling creative built for the platform's format, paired with Spark Ads to leverage organic-style performance.
- **LinkedIn**: B2B lead generation and ABM campaigns targeting by job function, seniority, and company list, built for pipeline, not just form fills.
- **Pinterest**: High-intent discovery campaigns for ecommerce and home services, capturing users in active planning mode.
- **X (Twitter)**: Selective use for real-time and B2B thought-leadership amplification where audience match justifies spend.

**BEYOND ENGAGEMENT METRICS**

H2: **A Cheap Lead Isn't a Good Lead**
Body: Social platforms are exceptionally good at generating volume, including likes, shares, and form fills, because their algorithms are trained to optimize for the actions people take most easily. Left unmanaged, that means an abundance of low-intent leads that make a dashboard look good and a sales team's job harder.

We counter this with:
- **Lead-quality feedback loops**: piping CRM disposition data (qualified vs. junk) back into Meta and LinkedIn's optimization events.
- **Value-based bidding**: bidding toward customer value tiers instead of a flat conversion goal, so platforms chase your best customers, not just any customer.
- **Audience suppression**: actively excluding low-value segments (existing customers, disqualified leads, competitors) to concentrate spend.

*[Before/After chart: "Leads Generated" (high, amber) vs. "Qualified Leads Generated" (lower but green), illustrating the gap traditional social management ignores.]*

**CREATIVE TESTING AT SCALE**

H2: **Creative Is a Performance Lever, Not Just a Design Exercise**
Body: On paid social, creative fatigue is the single largest driver of rising CAC. We run structured creative testing, covering hooks, formats, angles, and offers, using AI-assisted variant generation and statistically rigorous testing cadences to keep cost curves flat as campaigns scale.

**OUR PROCESS FOR SOCIAL**

1. **Audience & Offer Audit**: reviewing existing targeting, creative, and conversion event setup.
2. **Tracking Hardening**: implementing CAPI/server-side tracking to protect measurement from platform signal loss.
3. **Creative Sprint**: building an initial testing matrix of hooks, formats, and angles.
4. **Scale & Suppress**: scaling winning combinations while continuously suppressing low-value audiences.

**CASE STUDY CALLOUT**

"A DTC ecommerce brand grew paid social ROAS from 1.9x to 5.2x in nine months, while tripling monthly spend, by shifting Meta's optimization event from 'Purchase' to a value-weighted LTV signal." → **Read the full case study →**

**FAQ**

1. **How do you handle iOS 14.5+ tracking limitations?** Server-side CAPI implementation plus modeled conversions and first-party data matching to preserve measurement accuracy.
2. **Do you build the creative, or do we?** We can do either. Our Content Marketing team builds ad creative in-house, or we can optimize creative your internal team provides.
3. **How often do you refresh creative?** Typically every 2–3 weeks per active ad set, guided by frequency and CPA fatigue signals, not a fixed calendar.

**CTA:** H2 "Find Out What Your Social Spend Is Really Producing" → **Book a Growth Assessment →**

### CTA Placements
Hero primary/secondary; case study callout; closing CTA band; header persistent CTA.

### Visual Recommendations
Hand-drawn platform tile icons with a coral accent underline on hover. Before/after chart in UNO Teal/Amber. Creative testing section shows a mock grid of ad variants with performance heat-mapping (teal = winner, muted taupe = paused).

### Motion Ideas
Creative variant grid animates a "testing in progress" shuffle before settling on the winning variant, which gets a hand-drawn coral circle around it.

---

## PAGE 5: PROGRAMMATIC MEDIA (`/services/programmatic`)

### Purpose
Demystify programmatic buying for prospects who associate it with wasted spend and low transparency; position UNO's programmatic desk as data-disciplined and outcome-accountable.

### SEO
- **Primary keyword:** programmatic advertising agency
- **Secondary keywords:** CTV advertising agency, DOOH advertising, programmatic display agency, OTT advertising, retargeting agency
- **Suggested URL:** `/services/programmatic`
- **Meta title:** Programmatic Advertising Agency | CTV, OTT, Display, DOOH | UNO Marketing
- **Meta description:** UNO Marketing runs programmatic display, native, CTV, OTT, audio, and DOOH campaigns with full transparency into where every impression is bought and what it produces.
- **H1:** Programmatic Media, Without the Black Box
- **H2 structure:** Channels We Buy / Full-Funnel Reach, Full Transparency / Behavioral Audiences & Retargeting / Our Process for Programmatic / Results in Programmatic / FAQ
- **Internal linking:** AI Optimization, Data Intelligence, relevant case study
- **Schema:** Service, FAQPage, BreadcrumbList

### Wireframe
```
[HERO: dark]
[CHANNELS: light, icon grid]
[TRANSPARENCY: dark, split with supply-path diagram]
[BEHAVIORAL AUDIENCES: light]
[PROCESS: light]
[CASE STUDY: dark]
[FAQ]
[CTA]
```

### Full Copy

Eyebrow: `PROGRAMMATIC MEDIA`
H1: **Programmatic Media, Without the Black Box**
Subhead: Display, native, CTV, OTT, digital audio, and DOOH, bought with full visibility into supply path, placement quality, and outcome attribution.
Primary CTA: **Book a Growth Assessment →**  Secondary CTA: **See a Programmatic Case Study**

Stat strip: `44% avg. reach-efficiency gain` · `31% avg. reduction in wasted impressions` · `2.4x avg. incremental lift on branded search`

**CHANNELS WE BUY**

- **Display**: contextual and behavioral targeting across premium exchanges, with viewability and fraud filtering enforced at the buy.
- **Native**: content-matched placements for upper- and mid-funnel storytelling.
- **CTV (Connected TV)**: streaming-service ad placements for brand-scale reach with performance-grade measurement.
- **OTT**: over-the-top video inventory for cost-efficient video reach beyond traditional CTV.
- **Digital Audio**: podcast and streaming audio placements for passive-attention channels with strong recall.
- **DOOH (Digital Out-of-Home)**: geo-targeted digital billboard and place-based media, synced with mobile retargeting.
- **Retargeting**: cross-device sequential retargeting tied to funnel stage, not a blanket "everyone who visited" pool.
- **Behavioral Audiences**: first- and third-party behavioral segments built from intent signals, not just demographics.

**FULL-FUNNEL REACH, FULL TRANSPARENCY**

H2: **Programmatic Has a Trust Problem. We Solve It With Data.**
Body: Programmatic media's reputation for waste comes from opaque supply paths, bot traffic, and made-for-advertising (MFA) inventory. We buy through vetted supply-path-optimized (SPO) inventory, enforce viewability and brand-safety thresholds, and report placement-level performance, not just channel-level averages.

*[Supply-path diagram: Exchange → SSP → Publisher → Placement, with quality-filter checkpoints highlighted]*

**BEHAVIORAL AUDIENCES & RETARGETING**

H2: **Sequenced by Intent, Not Blasted by Volume**
Body: Retargeting pools are built by funnel stage. Someone who viewed a product page gets a different message and bid strategy than someone who abandoned a cart. Behavioral audiences are refreshed continuously as new first-party signals arrive from your CRM and site analytics.

**OUR PROCESS FOR PROGRAMMATIC**

1. **Supply Audit**: reviewing current or proposed inventory sources for viewability, fraud risk, and brand safety.
2. **Audience Architecture**: building funnel-stage-specific behavioral and retargeting segments.
3. **Channel Mix Design**: allocating budget across CTV, display, native, audio, and DOOH based on incremental lift potential, not historical habit.
4. **Incrementality Measurement**: geo-holdout or brand-lift testing to prove programmatic's contribution beyond last-click.

**CASE STUDY CALLOUT**

"A national home services brand used CTV + DOOH sequencing to lift branded search volume 2.4x in target markets, validated through a geo-holdout test." → **Read the full case study →**

**FAQ**

1. **How do you prevent ad fraud and MFA inventory?** Through supply-path optimization, pre-bid brand safety filtering, and post-campaign placement audits that flag and blacklist low-quality domains.
2. **Can you prove programmatic's impact if it doesn't get last-click credit?** Yes, through geo-holdout tests and multi-touch attribution modeling covered in our Data Intelligence practice.
3. **Is CTV worth it for a mid-size budget?** Often yes, in geo-targeted, frequency-capped campaigns. We'll show you the incremental math before you commit spend.

**CTA:** H2 "See What Your Programmatic Spend Is Actually Buying" → **Book a Growth Assessment →**

### CTA Placements
Hero primary/secondary; case study callout; closing CTA band; header persistent CTA.

### Visual Recommendations
Supply-path diagram rendered as a clean horizontal flow with quality checkpoints marked in UNO Teal; a channel-mix donut chart in Coral/Teal/Amber showing allocation across CTV/Display/Native/Audio/DOOH.

### Motion Ideas
Supply-path diagram animates a particle traveling from Exchange to Placement, pausing briefly at each quality-filter checkpoint to visualize the vetting process.

---

## PAGE 6: AI MEDIA OPTIMIZATION (`/services/ai-optimization`)

### Purpose
This is the flagship differentiator page. It must make UNO's AI capability feel concrete and mechanistic, not a buzzword, by explaining specific model applications and showing a live-feeling dashboard.

### SEO
- **Primary keyword:** AI marketing optimization
- **Secondary keywords:** AI media buying, predictive bidding, AI ad optimization, machine learning marketing agency, AI budget allocation
- **Suggested URL:** `/services/ai-optimization`
- **Meta title:** AI Media Optimization | Predictive Bidding & Budget Allocation | UNO Marketing
- **Meta description:** UNO Marketing's AI optimization layer predicts performance, reallocates budget in real time, and surfaces wasted spend across search, social, and programmatic.
- **H1:** The AI Layer Behind Every Media Dollar We Spend
- **H2 structure:** What Our AI Actually Does / Predictive Bidding / Budget Allocation / Creative Testing / Audience Expansion / Performance Forecasting / Finding Wasted Spend / How It Compounds Over Time / FAQ
- **Internal linking:** Data Intelligence, all channel service pages, relevant case study
- **Schema:** Service, FAQPage, BreadcrumbList

### Wireframe
```
[HERO: dark, animated dashboard widget]
[WHAT OUR AI DOES: light, sticky-scroll 8-item breakdown]
[LIVE DASHBOARD MODULE: dark]
[HOW IT COMPOUNDS: light]
[CASE STUDY: dark]
[FAQ]
[CTA]
```

### Full Copy

Eyebrow: `AI MEDIA OPTIMIZATION`
H1: **The AI Layer Behind Every Media Dollar We Spend**
Subhead: Our models analyze search behavior, predict performance, and reallocate budget in real time, across every channel we manage, every day, without waiting for a monthly review.
Primary CTA: **Book a Growth Assessment →**  Secondary CTA: **See How the AI Layer Works**

Stat strip: `$18K avg. monthly wasted spend recovered` · `2.1x faster optimization cycle vs. manual management` · `+22% avg. forecast accuracy improvement`

**WHAT OUR AI ACTUALLY DOES**

*(Sticky-scroll section: left panel narrates, right panel shows a corresponding dashboard visualization for each item)*

1. **Analyze Search Behavior**: Query-level and audience-level intent classification models identify which search patterns correlate with actual customer conversion, not just click-through rate.
2. **Predict Performance**: Forecasting models project CPL, ROAS, and CAC trajectories 2–4 weeks out, flagging accounts drifting off target before it shows up in a monthly report.
3. **Improve Bidding**: Custom bid-adjustment logic layered on top of platform automation (Target ROAS, Max Conversions) informed by margin data and lead-quality scoring, not just platform-reported conversion value.
4. **Budget Allocation**: A continuously updating allocation model shifts spend across channels and campaigns toward whichever is producing the best marginal return, rebalancing weekly (or daily, for high-velocity accounts).
5. **Creative Testing**: Statistical testing models identify winning creative variants faster than manual A/B review, accounting for frequency decay and audience fatigue.
6. **Audience Expansion**: Lookalike and behavioral expansion models built from your highest-LTV customers, not just anyone who converted once.
7. **Performance Forecasting**: Confidence-interval forecasting for board and CFO reporting, showing a range, not a false-precision single number.
8. **Identify Wasted Spend & Hidden Opportunities**: Anomaly-detection models flag underperforming placements, audience overlap, and budget cannibalization automatically, and surface underinvested channels showing early signs of efficient scale.

**LIVE DASHBOARD MODULE**

*(Embedded animated mock dashboard: "UNO Command Console")*
Live captions rotating through: "Shifted $12,400 from Display → Search based on predicted ROAS lift." / "Flagged 3 ad sets for creative fatigue. CTR down 18% week-over-week." / "Identified $6,200/mo in overlapping retargeting spend across Meta and The Trade Desk."

**HOW IT COMPOUNDS OVER TIME**

H2: **The Longer We Work Together, the Smarter the System Gets**
Body: Every campaign, every conversion, and every piece of CRM feedback becomes training data for your account's models. That's why clients typically see accelerating (not just steady) performance gains in months 4–12. The system isn't just running campaigns, it's learning your specific customers, sales cycle, and margin structure.

**CASE STUDY CALLOUT**

"For a B2B SaaS client, our forecasting model predicted a demand-gen budget shortfall 3 weeks before it would have shown up in pipeline reporting. Reallocating spend early preserved a full quarter's pipeline target." → **Read the full case study →**

**FAQ**

1. **Is this just Google's or Meta's built-in automation?** No. We layer proprietary bid, allocation, and forecasting logic on top of platform automation, informed by your CRM and margin data, which platform automation alone cannot see.
2. **How much data do you need before the AI is useful?** Meaningful signal typically emerges within 4–6 weeks of live spend and CRM integration; forecasting confidence improves substantially by month 3.
3. **Do you use any generative AI in this process?** Yes, for creative variant generation and initial audience hypothesis testing, always with human strategist review before anything goes live.

**CTA:** H2 "See the AI Layer Applied to Your Account" → **Book a Growth Assessment →**

### CTA Placements
Hero primary/secondary; case study callout; closing CTA band; header persistent CTA; each sticky-scroll item has a subtle inline link to the relevant channel page.

### Visual Recommendations
Central visual motif: the "UNO Command Console," a dark dashboard UI mockup with live-feeling animated charts (spend allocation treemap, ROAS trendline vs. target, anomaly alert feed). Sticky-scroll right panel swaps between 8 corresponding mini-visualizations as the user scrolls the left narrative.

### Motion Ideas
Dashboard alert feed types out new "insight" lines every few seconds (typewriter effect) to feel alive; treemap animates reallocation by resizing blocks smoothly; forecast chart shows a shaded confidence band that narrows as more "data" animates in.

---

## PAGE 7: DATA INTELLIGENCE (`/services/data-intelligence`)

### Purpose
Establish technical credibility around measurement, the foundation that makes every other claim on the site provable. This page needs to reassure technical stakeholders (marketing ops, analytics leads) that tracking will be done correctly and comprehensively.

### SEO
- **Primary keyword:** marketing attribution agency
- **Secondary keywords:** GA4 agency, server-side tracking agency, marketing analytics agency, marketing dashboard reporting, cross-channel attribution
- **Suggested URL:** `/services/data-intelligence`
- **Meta title:** Marketing Attribution & Data Intelligence | GA4, Server-Side Tracking | UNO Marketing
- **Meta description:** UNO Marketing builds attribution models, GA4 implementations, server-side tracking, and executive dashboards that connect every ad dollar to real revenue.
- **H1:** If You Can't Measure It Accurately, You Can't Optimize It
- **H2 structure:** What We Build / Attribution / GA4 & Server-Side Tracking / Dashboards & Executive Reporting / Call Tracking & CRM Integration / Cross-Channel Analytics / FAQ
- **Internal linking:** AI Optimization, all channel pages, relevant case study
- **Schema:** Service, FAQPage, BreadcrumbList

### Wireframe
```
[HERO: dark]
[WHAT WE BUILD: light, 6-item icon grid]
[ATTRIBUTION: dark, funnel diagram]
[TRACKING INFRASTRUCTURE: light]
[DASHBOARDS: dark, embedded mock dashboard]
[CASE STUDY]
[FAQ]
[CTA]
```

### Full Copy

Eyebrow: `DATA INTELLIGENCE`
H1: **If You Can't Measure It Accurately, You Can't Optimize It**
Subhead: Attribution, GA4, server-side tracking, and executive dashboards: the infrastructure that connects every ad dollar to real revenue, not just a platform's conversion count.
Primary CTA: **Book a Growth Assessment →**  Secondary CTA: **See a Data Intelligence Case Study**

Stat strip: `100% of channels tied to CRM revenue` · `<48hr avg. dashboard refresh implementation` · `0 data-loss incidents on server-side migrations to date`

**WHAT WE BUILD**

- **Attribution Modeling**: multi-touch and data-driven attribution models that reflect how your customers actually move through a multi-channel journey, replacing default last-click bias.
- **GA4 Implementation & Auditing**: clean, business-specific event architecture (not the default template), including ecommerce and lead-gen conversion mapping.
- **Server-Side Tracking**: first-party server-side tagging (via Google Tag Manager server containers or equivalent) to protect measurement accuracy against browser tracking restrictions and ad blockers.
- **Executive Dashboarding**: Looker Studio / Tableau dashboards built for how executives actually read data: revenue first, channel detail second.
- **Call Tracking & CRM Integration**: dynamic number insertion and CRM-synced lead scoring so phone and form leads are measured with equal rigor.
- **Cross-Channel Analytics**: unified reporting layer that reconciles Google, Meta, TikTok, LinkedIn, and programmatic data against one shared revenue definition.

**ATTRIBUTION**

H2: **Last-Click Attribution Is Lying to You**
Body: Last-click models systematically overcredit bottom-funnel channels (branded search, retargeting) and undercredit the channels that build initial demand (programmatic, social, content). We implement data-driven attribution models, validated where possible with incrementality testing, so budget decisions reflect true contribution, not just proximity to the sale.

*[Diagram: customer journey touchpoints across Display → Social → Search → Direct, showing attribution credit under last-click vs. data-driven models]*

**GA4 & SERVER-SIDE TRACKING**

H2: **Tracking Infrastructure That Survives Browser Changes**
Body: Third-party cookie deprecation, ITP, and ad blockers have made client-side-only tracking unreliable. We build server-side tracking layers that preserve first-party measurement accuracy, paired with GA4 implementations custom-mapped to your actual conversion events, not the default ecommerce template.

**DASHBOARDS & EXECUTIVE REPORTING**

H2: **One Dashboard. Every Channel. One Definition of Success.**
Body: Executives don't need fifteen platform logins. They need one view that answers: how much did we spend, how much revenue did it produce, and is that trend improving. Our dashboards are built around that hierarchy, with drill-down detail available, but never required.

*[Embedded dashboard mock: Revenue trendline, spend-to-revenue ratio, channel breakdown table, lead-quality score]*

**CALL TRACKING & CRM INTEGRATION**

H2: **Phone Leads Deserve the Same Rigor as Form Fills**
Body: For industries like home services, healthcare, legal, and automotive, calls often outweigh form submissions as a conversion path. We implement dynamic number insertion and CRM-synced call scoring so every phone lead is tracked back to its originating campaign, keyword, and even ad creative.

**CROSS-CHANNEL ANALYTICS**

H2: **One Shared Definition of "Qualified"**
Body: We reconcile lead and revenue definitions across every platform so a "qualified lead" means the same thing in Google Ads, Meta, your CRM, and your board deck, eliminating the reporting discrepancies that erode trust in marketing data.

**CASE STUDY CALLOUT**

"An enterprise financial services client discovered, through a full attribution rebuild, that programmatic display was responsible for 28% of closed revenue despite receiving 3% of last-click credit." → **Read the full case study →**

**FAQ**

1. **Do you work with our existing analytics stack, or replace it?** Typically we audit and rebuild within your existing stack (GA4, CRM, data warehouse) rather than replacing it. The goal is better data, not more tools.
2. **How long does a server-side tracking migration take?** Most implementations complete in 2–4 weeks depending on tech-stack complexity, with parallel tracking validation before cutover.
3. **Can you integrate with our CRM (Salesforce, HubSpot, etc.)?** Yes. CRM integration is core to how our AI optimization layer receives lead-quality and revenue feedback.

**CTA:** H2 "See Where Your Tracking Setup Is Leaking Data" → **Book a Growth Assessment →**

### CTA Placements
Hero primary (Growth Assessment) and secondary; case study callout; closing CTA band; header persistent CTA.

### Visual Recommendations
Attribution comparison diagram (last-click vs. data-driven credit distribution); embedded dashboard mockup with revenue-first hierarchy; call-tracking flow diagram (Ad → Call → CRM → Revenue).

### Motion Ideas
Attribution diagram animates credit "reshuffling" from last-click distribution to data-driven distribution on scroll, visually demonstrating the shift in channel credit.

---

## PAGE 8: CONTENT MARKETING (`/services/content-marketing`)

### Purpose
Present content, creative, and copy as a performance lever with measurable conversion impact, not a brand/awareness-only function, closing the loop between media buying and what the ad/page actually says.

### SEO
- **Primary keyword:** conversion copywriting agency
- **Secondary keywords:** landing page agency, SEO content agency, ad creative agency, performance content marketing
- **Suggested URL:** `/services/content-marketing`
- **Meta title:** Conversion Copywriting & Content Marketing Agency | UNO Marketing
- **Meta description:** UNO Marketing builds landing pages, conversion copy, SEO content, and ad creative engineered to convert, backed by the same performance data as our media buying.
- **H1:** Content That's Judged the Same Way Media Spend Is: By Results
- **H2 structure:** What We Build / Landing Pages & Conversion Copy / SEO Content / AI-Assisted Content / Creative Strategy & Ad Creative / Video Concepts / Email Marketing / FAQ
- **Internal linking:** Paid Social (creative), Paid Search (landing pages), AI Optimization, relevant case study
- **Schema:** Service, FAQPage, BreadcrumbList

### Wireframe
```
[HERO: dark]
[WHAT WE BUILD: light, 6-item grid]
[LANDING PAGES: dark, before/after CVR chart]
[SEO CONTENT: light]
[AI-ASSISTED CONTENT: light]
[CREATIVE & VIDEO: dark]
[EMAIL: light]
[CASE STUDY]
[FAQ]
[CTA]
```

### Full Copy

Eyebrow: `CONTENT MARKETING`
H1: **Content That's Judged the Same Way Media Spend Is: By Results**
Subhead: Landing pages, conversion copy, SEO content, ad creative, video concepts, and email, built and tested with the same rigor as our media buying, because a great campaign can still fail on a weak page.
Primary CTA: **Book a Growth Assessment →**  Secondary CTA: **See a Content Case Study**

Stat strip: `22% avg. landing page CVR lift` · `2–4 week avg. SEO content velocity cycle` · `18% avg. email-attributed revenue lift`

**WHAT WE BUILD**

- **Landing Pages**: built and A/B tested specifically against the traffic source and offer, not repurposed from your main site.
- **Conversion Copywriting**: headlines, CTAs, and page structure engineered around a single conversion action, informed by what messaging is actually closing deals in your CRM.
- **SEO Content**: organic content built to compound paid performance, targeting the same commercial-intent queries your paid search campaigns are bidding on.
- **AI-Assisted Content**: AI-accelerated drafting and research, always finished with human strategic and editorial review, speed without losing voice or accuracy.
- **Creative Strategy & Ad Creative**: hooks, angles, and formats for paid social and display, informed by what's actually converting, not just what's trending.
- **Video Concepts**: short-form and mid-length video concepts built for paid social and YouTube placements, scripted around proven direct-response structures.
- **Email Marketing**: lifecycle and promotional email built to extend paid media's reach into owned channels and recover otherwise-lost conversions.

**LANDING PAGES & CONVERSION COPY**

H2: **A Landing Page Is Part of the Media Buy, Not an Afterthought**
Body: We build landing pages matched to specific campaigns, audiences, and offers, then test structure, headline, and CTA placement with the same statistical discipline we apply to ad creative. A campaign with excellent targeting and a generic landing page is still a losing campaign.

*[Before/after chart: baseline page CVR vs. UNO-optimized page CVR]*

**SEO CONTENT**

H2: **Organic Content That Reinforces Paid, Instead of Competing With It**
Body: We prioritize content targeting the same commercial-intent queries already proving valuable in paid search, building long-term organic equity in exactly the terms that are currently costing you the most per click.

**AI-ASSISTED CONTENT**

H2: **AI Accelerates the Draft. Strategists Own the Result.**
Body: We use AI tools to speed up research, outlining, and first-draft generation, but every piece is edited, fact-checked, and aligned to brand voice by a human strategist before publication. AI is a velocity tool here, not a replacement for judgment.

**CREATIVE STRATEGY & AD CREATIVE**

H2: **Creative Informed by Performance Data, Not Just Trends**
Body: Our creative team works directly from paid social and search performance data, building new hooks and formats based on what's already resonating, then testing systematically rather than guessing.

**VIDEO CONCEPTS**

H2: **Scripted for Attention in the First Three Seconds**
Body: Short-form video concepts for TikTok, Instagram, and YouTube Shorts, built around direct-response scripting structures (hook, problem, proof, offer) rather than traditional brand-film pacing.

**EMAIL MARKETING**

H2: **Recovering Revenue Paid Media Already Paid to Generate**
Body: Lifecycle email, including abandoned cart, lead nurture, and post-purchase, recovers conversions from traffic your paid budget already earned, extending ROAS without added media spend.

**CASE STUDY CALLOUT**

"A legal services client increased landing page conversion rate 34% by rebuilding page structure around the top-performing ad angle rather than generic firm messaging." → **Read the full case study →**

**FAQ**

1. **Do you require us to switch CMS/website platforms?** No. We build landing pages compatible with most common platforms (WordPress, Webflow, HubSpot CMS, custom stacks) or headless if your infrastructure requires it.
2. **How is AI used responsibly in your content process?** For drafting speed and research only. Every piece goes through human strategic review, fact-checking, and brand-voice editing before publishing.
3. **Can you write for regulated industries (healthcare, legal, finance)?** Yes. Our content team has established compliance-review workflows for regulated verticals (see Industries).

**CTA:** H2 "See What Better Content Could Do for Your Conversion Rate" → **Book a Growth Assessment →**

### CTA Placements
Hero primary/secondary; case study callout; closing CTA band; header persistent CTA.

### Visual Recommendations
Before/after CVR bar chart; creative variant grid similar to Paid Social page but focused on ad hooks/angles; email flow diagram (Trigger → Email 1 → Email 2 → Conversion).

### Motion Ideas
Landing page before/after chart animates a "flip" transition between the two versions; video concept section shows a subtle animated storyboard (hook frame → proof frame → offer frame) cycling automatically.

---

## PAGE 9: INDUSTRIES (`/industries`)

### Purpose
Demonstrate vertical fluency across 10 target categories so prospects in regulated or high-consideration industries trust UNO understands their compliance, sales-cycle, and measurement realities, not just generic "we do ads" positioning.

### SEO
- **Primary keyword:** industries we serve performance marketing
- **Secondary keywords:** healthcare marketing agency, ecommerce marketing agency, B2B SaaS marketing agency, home services marketing agency, legal marketing agency, finance marketing agency
- **Suggested URL:** `/industries`
- **Meta title:** Industries We Serve | Performance Marketing for Healthcare, Finance, Ecommerce & More | UNO Marketing
- **Meta description:** UNO Marketing builds performance systems for healthcare, finance, home services, legal, ecommerce, B2B SaaS, automotive, retail, professional services, and enterprise brands.
- **H1:** Vertical Expertise, Not Generic Playbooks
- **H2 structure:** Why Industry Fluency Matters / [10 industry sections] / Don't See Your Industry?
- **Internal linking:** relevant case studies per industry, relevant service pages per industry, Contact
- **Schema:** BreadcrumbList; consider individual Service+areaServed markup if built out as full sub-pages later

### Wireframe
```
[HERO: dark] H1, subhead, industry quick-jump tab bar
[WHY INDUSTRY FLUENCY MATTERS: light]
[10x INDUSTRY MODULES: alternating dark/light, tabbed/filterable interface]
 each module: stat callout, compliance/consideration note, primary channels, mini-CTA to case study
[CTA BAND]
```

### Full Copy

Eyebrow: `INDUSTRIES`
H1: **Vertical Expertise, Not Generic Playbooks**
Subhead: Regulated categories, long sales cycles, and high-competition markets all require a different media and measurement approach than a one-size-fits-all playbook. Here's how we adapt by industry.

*[Interactive tab bar: Healthcare · Finance · Home Services · Legal · Ecommerce · B2B SaaS · Automotive · Retail · Professional Services · Enterprise]*

**WHY INDUSTRY FLUENCY MATTERS**

H2: **The Same Channel Mix Doesn't Work Everywhere**
Body: A CTV campaign that builds a national ecommerce brand would be a poor allocation for a single-location legal practice. A Google Ads structure built for immediate-purchase retail intent will underperform for a B2B SaaS sales cycle measured in quarters. Industry context changes everything: channel mix, compliance requirements, sales-cycle length, and what "qualified" even means.

**INDUSTRY MODULES**

**Healthcare**
Multi-location providers and specialty practices need HIPAA-conscious tracking, appointment-verified lead quality, and local-intent search dominance. *Primary channels: Paid Search (local + PMax), Paid Social, Call Tracking.* *Avg. result: 41% CPL reduction.* → **Read the Healthcare Case Study →**

**Finance**
Financial services face strict compliance review (FINRA, state-level regulation) alongside long consideration cycles. We build compliant ad copy workflows and attribution models tuned to high-value, low-volume conversions. *Primary channels: Paid Search, LinkedIn, Programmatic Display.* *Avg. result: 28% of closed revenue traced to previously under-credited programmatic spend.*

**Home Services**
High local competition, call-heavy conversion paths, and seasonal demand swings define this category. We prioritize call tracking, local campaign structuring, and CTV/DOOH for market-level share-of-voice. *Primary channels: Local Search, CTV, DOOH, Paid Social.* *Avg. result: 2.4x incremental lift on branded search.*

**Legal**
High-value, high-CPC categories where lead quality (case-worthy vs. unqualified) matters more than lead volume. We integrate CRM-based case-qualification scoring directly into bidding signals. *Primary channels: Paid Search, Paid Social, Landing Page CRO.* *Avg. result: 34% landing page conversion lift.*

**Ecommerce**
Margin-aware bidding, Shopping feed optimization, and creative velocity to fight rising CAC are the core challenges. We connect product-level margin data directly into bid strategy. *Primary channels: Shopping, Meta, Performance Max, Email.* *Avg. result: ROAS improved from 1.9x to 5.2x.*

**B2B SaaS**
Long sales cycles and pipeline-stage attribution (not just MQLs) define success. We integrate CRM opportunity data so campaigns optimize toward pipeline-qualified leads, not raw form fills. *Primary channels: LinkedIn, Paid Search, Programmatic ABM.* *Avg. result: 35% CAC reduction, 78% increase in pipeline-qualified leads.*

**Automotive**
Hyper-local inventory-based advertising with fast-moving offers and high seasonal variance. We sync dynamic inventory feeds directly into Search and Social campaigns. *Primary channels: Local Search, Paid Social, Programmatic Display, CTV.*

**Retail**
National reach with local relevance, balancing brand-scale programmatic and CTV with location-aware paid social and search. *Primary channels: Programmatic, Paid Social, Shopping, DOOH.*

**Professional Services**
Trust-driven, consideration-heavy purchase decisions (accounting, consulting, B2B services) where content and retargeting sequencing matter as much as initial reach. *Primary channels: LinkedIn, Paid Search, Content Marketing, Retargeting.*

**Enterprise**
Multi-brand, multi-market complexity requiring centralized data infrastructure and decentralized campaign execution. We build the attribution and dashboard layer that lets enterprise marketing teams see one truth across dozens of campaigns and agencies. *Primary channels: Full-channel, Data Intelligence-led engagement.*

**DON'T SEE YOUR INDUSTRY?**

H2: **We've Likely Solved a Version of Your Problem Before**
Body: These 10 categories represent our deepest experience, but the underlying discipline, connecting media to revenue, applies to any business with a measurable conversion path.

CTA Band: **Book a Growth Assessment →**

### CTA Placements
Hero tab-bar (soft navigation, not a form); per-industry mini-CTA to relevant case study; closing CTA band to Growth Assessment; header persistent CTA.

### Visual Recommendations
Each industry module gets a distinct hand-drawn icon (medical cross, legal column, storefront, etc., kept in the same loose linework system as the logo for consistency). Stat callouts in UNO Teal tabular numerals with a hand-drawn coral underline.

### Motion Ideas
Tab bar filters content with a smooth cross-fade rather than a full page reload; industry modules stagger-reveal on scroll.

---

## PAGE 10: CASE STUDIES (`/case-studies` index + `/case-studies/[client-slug]` template)

### Purpose
Prove every claim made elsewhere on the site with specific, numbers-first narratives. The index page must let visitors filter by industry and channel to find a relevant proof point fast; individual case studies must satisfy both a skimming exec and a technical stakeholder who wants the methodology.

### SEO (Index Page)
- **Primary keyword:** marketing agency case studies
- **Secondary keywords:** performance marketing results, ROAS case study, CAC reduction case study
- **Suggested URL:** `/case-studies`
- **Meta title:** Case Studies | Real Performance Marketing Results | UNO Marketing
- **Meta description:** Browse UNO Marketing case studies by industry and channel: real CPL, ROAS, and CAC results across healthcare, ecommerce, B2B SaaS, and more.
- **H1:** Proof, Filtered by Industry and Channel
- **H2 structure:** Filter results / Featured Case Studies
- **Internal linking:** all industries, all service pages
- **Schema:** BreadcrumbList, ItemList

### SEO (Individual Case Study Template)
- **Primary keyword pattern:** [industry] + [channel] case study (e.g., "healthcare Google Ads case study")
- **Suggested URL pattern:** `/case-studies/[client-industry-descriptor]` (e.g., `/case-studies/regional-healthcare-provider`)
- **Meta title pattern:** [Client/Industry] Case Study: [Headline Metric] | UNO Marketing
- **Meta description pattern:** How UNO Marketing helped a [industry] client achieve [headline metric] through [primary channel/strategy].
- **H1 pattern:** [Headline metric] for a [Industry Descriptor]
- **H2 structure:** The Challenge / The Strategy / Execution / Optimization / Results / Lessons Learned
- **Internal linking:** relevant service page(s), relevant industry section, Contact
- **Schema:** Article, BreadcrumbList; consider Review/AggregateRating only if genuine third-party reviews exist

### Index Page Wireframe
```
[HERO: dark] H1, subhead
[FILTER BAR: light, sticky] Industry dropdown / Channel dropdown / Sort
[CASE STUDY GRID: light] cards with industry tag, channel tag, headline metric, thumbnail chart
[CTA BAND]
```

### Index Page Copy

Eyebrow: `CASE STUDIES`
H1: **Proof, Filtered by Industry and Channel**
Subhead: Every case study includes the strategy, the execution, and the number that resulted. No vanity metrics.

*[Filter bar: Industry: All / Healthcare / Finance / Home Services / Legal / Ecommerce / B2B SaaS / Automotive / Retail / Professional Services / Enterprise, and Channel: All / Paid Search / Paid Social / Programmatic / AI Optimization / Data Intelligence / Content]*

CTA Band: H2 "Want Results Like These?" → **Book a Growth Assessment →**

### Individual Case Study Wireframe (Template)
```
[HERO: dark] Client industry tag, H1 (headline metric), 3-stat summary row
[CHALLENGE: light]
[STRATEGY: dark]
[EXECUTION: light]
[OPTIMIZATION: dark, chart-heavy]
[RESULTS: light, animated metric grid + full chart]
[LESSONS LEARNED: dark]
[NEXT CASE STUDY / CTA: light]
```

### Individual Case Study CTA Placements
Hero stat row functions as the primary proof-CTA; end-of-page CTA to Growth Assessment; mid-page contextual link to the relevant service page discussed in Strategy section.

### Visual Recommendations
Hero: client logo (or industry icon if anonymized) + 3 large tabular-mono stats. Optimization section: line/bar chart animating baseline → optimized performance. Results section: full metric grid matching the homepage counter style, plus one hero chart (e.g., ROAS over time).

### Motion Ideas
Hero stats count up on load; Optimization chart draws in on scroll; Results section chart includes a hover tooltip showing month-by-month data.

---

---

---

# PART 4: TWO FULLY WRITTEN CASE STUDIES (using the template above)

## Case Study A: Regional Healthcare Provider

**URL:** `/case-studies/regional-healthcare-provider`
**Meta title:** Healthcare Case Study: 41% Lower Cost Per Lead | UNO Marketing
**Meta description:** How UNO Marketing helped a multi-location healthcare provider cut Cost Per Lead 41% by optimizing Google Ads and Performance Max around verified appointments instead of form submissions.
**H1:** 41% Lower Cost Per Lead for a Multi-Location Healthcare Provider

**Hero stat row:** `41% CPL reduction` · `62% increase in qualified appointment volume` · `90 days to first measurable shift`

### The Challenge
A 14-location healthcare provider was spending $85,000/month across Google Ads and Meta, generating a high volume of form-fill leads, but its front-desk teams reported that fewer than half were actually booking appointments. The account's prior agency reported on cost-per-form-fill, which looked healthy, while the business's true metric, cost per booked, verified appointment, was quietly getting worse each quarter. There was no server-side tracking connecting ad clicks to the practice management system, so no one could see the gap.

### The Strategy
UNO proposed re-anchoring every campaign around a single downstream event: a verified, kept appointment, not a form submission. That required three parallel workstreams: rebuilding tracking to connect ad platforms to the practice management system, restructuring Performance Max and Search campaigns around appointment-verified conversion data, and layering in call tracking, since a majority of actual bookings originated from phone calls the prior setup didn't measure at all.

### Execution
- Implemented server-side tracking and a call-tracking layer (dynamic number insertion) connected to the practice management system, closing the loop between ad click and kept appointment.
- Rebuilt Performance Max asset groups around location-specific, intent-tiered messaging instead of one generic account-wide structure.
- Imported verified-appointment data as an offline conversion signal into Google Ads, shifting the platform's own bidding algorithm to optimize toward the metric that mattered.
- Restructured local Search campaigns by location and service line, eliminating budget cannibalization between nearby locations.

### Optimization
Within the first 6 weeks, the AI Media Optimization layer flagged that roughly 22% of the existing budget was concentrated on broad, low-intent queries generating form fills that rarely converted to kept appointments. That budget was reallocated toward higher-intent local and branded terms and call-driven ad formats. Bid strategies were adjusted weekly based on location-level appointment-verification rates rather than platform-reported conversions alone.

*[Chart: CPL trendline, month-over-month, showing a declining line from $92 to $54 over the 90-day engagement, with a hand-drawn annotation marking the week tracking went live.]*

### Results
- **41%** reduction in Cost Per (verified) Lead over 90 days
- **62%** increase in qualified appointment volume, with flat total spend
- **22%** of prior monthly budget identified as misallocated to low-intent queries and reallocated
- **100%** of phone and form leads now tracked to a verified appointment outcome

### Lessons Learned
The form-fill metric the prior agency optimized toward wasn't wrong. It was just incomplete. The real lesson: in industries where the sales cycle includes a human verification step (booking, underwriting, qualification), platform-reported conversions will always overstate performance unless that downstream data is fed back into the ad platforms themselves.

**Related services:** Paid Search · AI Media Optimization · Data Intelligence
**CTA:** H2 "Want Results Like This for Your Practice?" → **Book a Growth Assessment →**

---

## Case Study B: Direct-to-Consumer Ecommerce Brand

**URL:** `/case-studies/dtc-ecommerce-brand`
**Meta title:** Ecommerce Case Study: ROAS Grew From 1.9x to 5.2x | UNO Marketing
**Meta description:** How UNO Marketing helped a DTC ecommerce brand grow ROAS from 1.9x to 5.2x in nine months while tripling monthly ad spend, through value-based bidding and margin-aware Shopping optimization.
**H1:** ROAS Grew From 1.9x to 5.2x While Tripling Ad Spend

**Hero stat row:** `5.2x ROAS (from 1.9x)` · `3x spend scaled` · `9-month engagement`

### The Challenge
A DTC ecommerce brand was profitable at a small scale but hit a wall trying to grow: every attempt to increase Meta and Google Shopping spend caused ROAS to collapse. The brand's previous approach optimized every product uniformly toward "Purchase" as a flat conversion event, ignoring the fact that different products carried dramatically different margins and different customers carried dramatically different lifetime value.

### The Strategy
UNO's approach reframed the account around two ideas the client hadn't previously measured: product-level margin and customer-level lifetime value. Rather than bidding the same way on every purchase, campaigns were restructured to bid more aggressively on high-margin products and high-LTV customer segments, and to actively suppress low-margin, low-LTV traffic that had been inflating volume without building the business.

### Execution
- Connected product-level margin data from the client's inventory system into Shopping campaign bid strategies, shifting spend toward higher-margin SKUs.
- Rebuilt Meta's optimization event from a flat "Purchase" signal to a value-weighted conversion signal reflecting predicted 12-month customer value.
- Layered lookalike audience expansion off the top 20% of customers by LTV, rather than off all past purchasers.
- Introduced systematic creative testing (hooks, formats, offers) to keep CPMs and CTR stable as spend scaled, preventing the creative fatigue that typically caps ecommerce scaling.

### Optimization
The AI Media Optimization layer continuously reallocated budget across Shopping, Meta, and Performance Max on a weekly cycle, shifting spend toward whichever channel/product combination showed the best marginal return as scale increased, rather than holding a fixed channel-mix percentage.

*[Chart: ROAS trendline over 9 months, climbing from 1.9x to 5.2x, overlaid with a spend-scale line tripling over the same period, with a hand-drawn arrow marking the value-based-bidding launch point.]*

### Results
- **ROAS grew from 1.9x to 5.2x** over nine months
- **Monthly ad spend scaled 3x** without ROAS decline, the original failure mode
- **Creative fatigue-driven CPA spikes reduced** through systematic testing cadence
- **Customer LTV-weighted targeting** became the account's primary growth lever going forward

### Lessons Learned
"Scale kills ROAS" is only true when every dollar is bid the same way. Once margin and lifetime value entered the bidding logic, scale became the thing that improved ROAS, because the algorithm could finally tell the difference between a $40 one-time purchase and a $400 repeat customer.

**Related services:** Paid Social · Programmatic Media · AI Media Optimization
**CTA:** H2 "Want to Scale Spend Without Losing ROAS?" → **Book a Growth Assessment →**

---

## PAGE 11: OUR PROCESS (`/process`)

### Purpose
Make the agency's methodology tangible and repeatable-feeling, reassuring prospects evaluating a large budget commitment that there's a disciplined system behind the work, and that optimization is continuous, not a one-time launch event.

### SEO
- **Primary keyword:** performance marketing process
- **Secondary keywords:** paid media methodology, marketing agency process, how performance marketing agencies work
- **Suggested URL:** `/process`
- **Meta title:** Our Process | A 7-Step Performance Marketing Methodology | UNO Marketing
- **Meta description:** Discover, Research, Strategy, Launch, Measure, Optimize, Scale: UNO Marketing's methodology for building performance marketing systems that never stop improving.
- **H1:** Optimization Isn't a Phase. It's the Whole System.
- **H2 structure:** The 7-Step Methodology / Discover / Research / Strategy / Launch / Measure / Optimize / Scale / Why This Never Really "Ends"
- **Internal linking:** AI Optimization, Data Intelligence, Case Studies, Contact
- **Schema:** BreadcrumbList; HowTo schema optional for the 7-step sequence

### Wireframe
```
[HERO: dark] H1, subhead
[STICKY-SCROLL 7-STEP SECTION: alternating]
 left: narrative text per step / right: corresponding visual
[WHY THIS NEVER ENDS: dark]
[CTA]
```

### Full Copy

Eyebrow: `OUR PROCESS`
H1: **Optimization Isn't a Phase. It's the Whole System.**
Subhead: Most agencies treat "optimization" as step six of a linear process. We treat it as the operating principle underneath all seven.
Primary CTA: **Book a Growth Assessment →**

**1. Discover**
We start by understanding the business, not just the ad accounts: margin structure, sales cycle, customer lifetime value, and what "qualified" actually means for your team. This shapes every decision that follows.

**2. Research**
Account audit, competitive landscape, search intent mapping, and audience research, establishing a factual baseline instead of assumptions carried over from the last agency.

**3. Strategy**
A channel mix and measurement plan built around your specific business outcomes, not a templated media plan. This is where we decide what "winning" looks like, in numbers, before a single dollar moves.

**4. Launch**
Campaign build and tracking implementation happen together, not sequentially, because a campaign launched without accurate measurement is a campaign you can't actually optimize.

**5. Measure**
Attribution, dashboards, and reporting go live alongside campaigns, not weeks after. From day one, performance is visible against the baseline established in Research.

**6. Optimize**
Continuous bid, budget, audience, and creative refinement, powered by the AI Media Optimization layer and reviewed by human strategists weekly, not quarterly.

**7. Scale**
Once a channel or campaign proves consistent marginal return, we scale it deliberately, testing incrementality along the way to make sure growth in spend keeps producing growth in profit, not just growth in volume.

**WHY THIS NEVER REALLY "ENDS"**

H2: **Step 6 Never Actually Stops**
Body: Scale isn't the finish line. It's a return to Measure with a bigger dataset. Every dollar spent generates new data that feeds back into Discover, Research, and Optimize. That loop is the product. It's why performance tends to compound the longer we work together, rather than plateau after the first 90 days.

**CTA:** H2 "See This Process Applied to Your Account" → **Book a Growth Assessment →**

### CTA Placements
Hero primary CTA; closing CTA band; header persistent CTA.

### Visual Recommendations
Sticky-scroll right panel shows a different hand-drawn-annotated visual per step: Discover (a sketched business-model diagram), Research (an audit checklist with checkmarks drawing in), Strategy (a channel-mix sketch), Launch (a tracking diagram lighting up), Measure (a dashboard populating with real numbers), Optimize (a bid-adjustment chart), Scale (a spend line climbing with a hand-drawn arrow).

### Motion Ideas
As the user scrolls, a connecting thread (styled as a hand-drawn line) draws itself from step to step down the left rail, visually reinforcing "this is one continuous loop, not seven separate stages."

---

## PAGE 12: ABOUT (`/about`)

### Purpose
Build trust in the people and philosophy behind the numbers, critical for a site that leans so heavily on data and AI messaging elsewhere. This page should feel human and warm, reinforcing the brand's differentiated coral/hand-drawn identity most directly.

### SEO
- **Primary keyword:** UNO Marketing agency
- **Secondary keywords:** performance marketing agency about us, AI marketing agency team, who is UNO Marketing
- **Suggested URL:** `/about`
- **Meta title:** About UNO Marketing | The Team Behind the Performance
- **Meta description:** UNO Marketing is a performance marketing system built by strategists, data engineers, and creatives who believe every ad dollar should have a measurable purpose. Meet the team.
- **H1:** We Built the Agency We Wished Existed
- **H2 structure:** Our Philosophy / How We Started / What Makes Us Different / Leadership / Our Values / Join Us
- **Internal linking:** Careers, Process, Case Studies, Contact
- **Schema:** AboutPage, Organization, BreadcrumbList

### Wireframe
```
[HERO: dark] H1, subhead, warm team photography
[PHILOSOPHY: light]
[ORIGIN STORY: dark]
[WHAT MAKES US DIFFERENT: light, 3-column]
[LEADERSHIP: light, team grid]
[VALUES: dark]
[CTA]
```

### Full Copy

Eyebrow: `ABOUT UNO`
H1: **We Built the Agency We Wished Existed**
Subhead: A performance marketing partner that treats your ad budget like it's ours: measured, accountable, and never allowed to plateau.

**OUR PHILOSOPHY**

H2: **Every Marketing Dollar Should Have a Measurable Purpose**
Body: We don't sell clicks. We don't sell impressions. We build systems, media, data, and AI working together, that turn advertising budgets into profitable, compounding growth. Success, to us, looks like lower cost per lead, higher ROAS, lower customer acquisition cost, better lead quality, higher lifetime value, and smarter allocation of every dollar you give us. Nothing else on this page matters if we can't prove that.

**HOW WE STARTED**

H2: **Built by People Tired of Reporting on the Wrong Numbers**
Body: UNO was founded on a simple frustration: too many capable marketers were stuck reporting on metrics that made a dashboard look good while the business underneath struggled to grow. We built UNO around the opposite instinct: start with the number the CFO actually cares about, and work backward into the media plan, not the other way around.

**WHAT MAKES US DIFFERENT**

1. **We optimize for outcomes, not platforms.** Every recommendation is judged by its effect on revenue, CAC, and LTV, not on how it looks in a platform's native dashboard.
2. **Our AI layer learns your business, not just your ad account.** Every model we run is trained on your CRM, margin, and lifetime-value data, not a generic industry benchmark.
3. **We show our work.** Every client gets a dashboard built on their own revenue data, updated continuously, not a monthly PDF built to look good in a meeting.

**LEADERSHIP** *(placeholder, populate at launch)*

Team grid: Name, Title, 1-line bio, headshot (warm-toned photography), LinkedIn link. *(e.g., Founder & CEO, VP of Media, Head of Data Intelligence, Head of Creative Strategy)*

**OUR VALUES**

- **Accountability over optics.** We'd rather tell you a channel underperformed than hide it behind a vanity metric.
- **Curiosity over habit.** Platform defaults are a starting point, not a strategy.
- **Craft over shortcuts.** AI accelerates our work. It doesn't replace strategic judgment.

**CTA:** H2 "Want to See How We'd Approach Your Business?" → **Book a Growth Assessment →**
Secondary: **See Open Roles →** (links to Careers)

### CTA Placements
Hero implied CTA via header; closing CTA band (Growth Assessment); secondary link to Careers.

### Visual Recommendations
Warm, candid team photography (Cream/Coral color grading); hand-drawn underline beneath the H1; leadership grid with Polaroid-style warm-toned headshots framed in a slightly imperfect, hand-set layout (subtle rotation per photo) to reinforce the handcrafted brand feel.

### Motion Ideas
Leadership photos gently "settle" into place with a slight rotation-correcting animation on scroll (as if being placed on a corkboard); H1 underline hand-draws itself in on page load.

---

## PAGE 13: INSIGHTS (`/insights`)

### Purpose
House thought leadership and SEO content that reinforces expertise across every service and industry, feeding organic traffic and internal links back to service/industry pages: a resource hub for prospects and clients doing research.

### SEO
- **Primary keyword:** performance marketing insights
- **Secondary keywords:** paid media blog, marketing attribution blog, AI marketing blog, performance marketing resources
- **Suggested URL:** `/insights`
- **Meta title:** Insights | Performance Marketing Resources & Benchmarks | UNO Marketing
- **Meta description:** Data-driven articles, benchmarks, and guides on paid search, paid social, programmatic, AI optimization, and marketing attribution from UNO Marketing.
- **H1:** Straight Answers on What's Actually Working in Paid Media
- **H2 structure:** Filter by Topic / Featured Articles / Subscribe for Monthly Benchmarks
- **Internal linking:** all service pages, all individual articles cross-link to relevant service/industry pages
- **Schema:** Blog, BreadcrumbList; Article schema on each post

### Wireframe
```
[HERO: dark] H1, subhead, topic filter bar
[FEATURED ARTICLE: light, large card]
[ARTICLE GRID: light]
[NEWSLETTER CTA: dark]
```

### Full Copy

Eyebrow: `INSIGHTS`
H1: **Straight Answers on What's Actually Working in Paid Media**
Subhead: No recycled listicles. Original analysis, benchmarks, and breakdowns from the team managing the accounts.

*[Topic filter: All · Paid Search · Paid Social · Programmatic · AI Optimization · Data Intelligence · Content Marketing · Industry Benchmarks]*

**Sample Featured Article Titles** *(placeholder, populate with real articles at launch)*
- "What Performance Max Actually Does With Your Budget (And How to Audit It)"
- "Why Last-Click Attribution Undercounts Your Best Channels"
- "The Real Cost of Creative Fatigue on Meta, and How to Test Around It"
- "CTV Is Not Just Brand Awareness: A Framework for Measuring Incrementality"
- "2026 Benchmark Report: CPL and ROAS by Industry"

**NEWSLETTER CTA**

H2: **Monthly Benchmarks. No Fluff.**
Subhead: CPL, ROAS, and CAC benchmarks by industry, delivered once a month. No drip campaign, no daily noise.
[Email input] **Subscribe →**

### CTA Placements
Newsletter capture at bottom; each article links contextually to a relevant service/industry page and closes with a Growth Assessment CTA.

### Visual Recommendations
Article cards use a warm Cream background with a small hand-drawn topic icon and a Coral topic tag. Featured article gets a larger hero-style card with a pull-quote in the hand-lettered accent font.

### Motion Ideas
Topic filter cross-fades the grid; hovering a card reveals a hand-drawn arrow "Read more →" that draws itself in.

---

## PAGE 14: CAREERS (`/careers`)

### Purpose
Attract performance-minded marketers, data engineers, and creatives by reinforcing the same accountability-driven culture described in About, translated into what it's like to work at UNO.

### SEO
- **Primary keyword:** UNO Marketing careers
- **Secondary keywords:** performance marketing jobs, paid media jobs, marketing agency careers
- **Suggested URL:** `/careers`
- **Meta title:** Careers at UNO Marketing | Join a Performance-Driven Team
- **Meta description:** UNO Marketing is hiring performance marketers, data engineers, and creative strategists who believe every ad dollar should have a measurable purpose. See open roles.
- **H1:** Work Where Your Impact Is Never Ambiguous
- **H2 structure:** Why UNO / How We Work / Benefits / Open Roles
- **Internal linking:** About, Process, Contact
- **Schema:** JobPosting (per open role), BreadcrumbList

### Wireframe
```
[HERO: dark] H1, subhead, team photography
[WHY UNO: light, 3-column]
[HOW WE WORK: dark]
[BENEFITS: light, icon grid]
[OPEN ROLES: light, list with filter by department]
[CTA]
```

### Full Copy

Eyebrow: `CAREERS`
H1: **Work Where Your Impact Is Never Ambiguous**
Subhead: Every role at UNO is measured against the same standard we hold ourselves to with clients: does this make the work better, faster, or more profitable?

**WHY UNO**

1. **Ownership, not oversight.** You'll own accounts and outcomes directly, not shepherd a campaign through five layers of approval.
2. **Built around craft, not busywork.** AI handles the repetitive analysis so your time goes to strategy, not spreadsheet maintenance.
3. **Growth that's actually measured.** Career growth here follows the same principle as client growth: clear metrics, regular review, no guessing where you stand.

**HOW WE WORK**

H2: **Small Teams, Real Accounts, Real Accountability**
Body: We staff lean, senior-heavy teams per account rather than large junior-staffed pods. That means less hierarchy, faster decisions, and direct client and data access from day one.

**BENEFITS** *(placeholder, populate with real policy at launch)*
Competitive base + performance bonus structure · Remote-friendly / hybrid options · Health coverage · Professional development budget · Flexible PTO

**OPEN ROLES** *(placeholder, populate at launch)*
*[Filterable list by department: Media & Paid Channels / Data & Analytics / Creative & Content / Client Strategy / Operations]*
Example placeholders: Senior Paid Search Strategist · Data Intelligence Analyst · Creative Strategist, Paid Social · Growth Account Director

**CTA:** H2 "Don't See the Right Role?" → **Send Us Your Resume →** (mailto or form link)

### CTA Placements
Open Roles list (primary conversion path, apply); closing CTA to submit resume for future roles.

### Visual Recommendations
Warm, candid team photography; open roles list styled as a simple, scannable table with a Coral "Apply" button per row; department filter tags in Soft Blush pill badges.

### Motion Ideas
Role list rows lift slightly on hover with a coral left-border accent sliding in.

---

## PAGE 15: CONTACT (`/contact`)

### Purpose
Convert warmed-up visitors into a booked conversation, offering two distinct entry points (Growth Assessment, Performance Review) so visitors self-select based on where they are in their evaluation process.

### SEO
- **Primary keyword:** contact UNO Marketing
- **Secondary keywords:** book a growth assessment, book a performance review, performance marketing consultation
- **Suggested URL:** `/contact`
- **Meta title:** Contact UNO Marketing | Book a Free Growth Assessment
- **Meta description:** Book a Growth Assessment or Performance Review with UNO Marketing to see exactly where your ad budget is underperforming.
- **H1:** Let's Find Out What Your Budget Is Actually Doing
- **H2 structure:** Choose Your Starting Point / ROI Calculator / What Happens Next / FAQ
- **Internal linking:** all service pages, Process
- **Schema:** ContactPage, BreadcrumbList

### Wireframe
```
[HERO: dark] H1, subhead
[OFFER SELECTOR: light, 4-card grid]
[FORM: light, split layout: form left / ROI calculator or expectations right]
[WHAT HAPPENS NEXT: dark, 3-step]
[FAQ: light]
```

### Full Copy

Eyebrow: `CONTACT`
H1: **Let's Find Out What Your Budget Is Actually Doing**
Subhead: Pick the starting point that fits where you are. Every option ends in a real conversation with a strategist, not a sales script.

**CHOOSE YOUR STARTING POINT**

1. **Growth Assessment** *(most popular)*: A 45-minute working session where we review your account live and show you, in numbers, where budget is likely underperforming.
2. **Performance Review**: For existing advertisers with an established program: a deep-dive benchmark of your current performance against industry and account-history baselines.

**FORM**
Fields: Name · Work Email · Company · Monthly Ad Spend (dropdown ranges) · Which best describes you? (dropdown: Healthcare / Finance / Home Services / Legal / Ecommerce / B2B SaaS / Automotive / Retail / Professional Services / Enterprise / Other) · Which option above? (radio: Growth Assessment / Performance Review) · Message (optional)
Submit button: **Book My Session →**

**ROI CALCULATOR** *(inline, beside or below form)*
H2: **See What's Possible Before You Even Talk to Us**
Interactive: input current monthly ad spend + select industry → tool returns an estimated CAC-reduction and ROAS-lift range based on UNO's benchmark data, ending in the same CTA.

**WHAT HAPPENS NEXT**

1. **We review your info**: within 1 business day, matched to a strategist with relevant industry experience.
2. **We meet**: a focused session (30–45 minutes) built around the option you chose, not a generic sales pitch.
3. **We show you the numbers**: leaving with a clear picture of where your budget stands today and what's realistically possible.

**FAQ**

1. **Is there any cost or obligation?** No. All four options are free and carry no obligation to engage further.
2. **What information should I bring?** Recent ad account access (view-only is fine) and, if possible, a rough sense of your current CAC or cost per lead. The more real data, the more useful the session.
3. **How fast can we start if we decide to move forward?** Most engagements can begin account access and tracking audit within 1–2 weeks of signing.

### CTA Placements
Primary form submission (all four offers route to the same form, differentiated by radio selection); ROI calculator as a secondary, lower-commitment engagement path; header persistent CTA remains visible for reinforcement.

### Visual Recommendations
Offer cards on Cream background with a Coral top border and a hand-drawn icon per offer type; form on a clean Warm White card floated over Cream; "What Happens Next" section on Charcoal with a hand-drawn 3-step connecting line.

### Motion Ideas
Selecting an offer card highlights the corresponding radio option in the form below with a smooth scroll-and-glow; ROI calculator output numbers count up in Coral/Teal when calculated.

---

---

---

# PART 5: CONVERSION OFFER SYSTEM (sitewide)

Every page on the site routes to one of four offers, always reinforcing measurable business growth rather than a generic "contact us."

| Offer | Best for | Commitment | Where it's used |
|---|---|---|---|
| **Growth Assessment** | Prospects ready for a live account audit | 45 min working session, live account review | Sitewide primary CTA: Home, all Service pages, Industries, Case Studies, Process, About |
| **Performance Review** | Existing advertisers benchmarking current spend | Deep-dive benchmark vs. industry/history | Contact, referenced in Insights benchmark content |

**Standing rule:** No CTA copy ever says only "Contact Us" or "Learn More" in isolation. Every button states the specific action and, where possible, the specific outcome ("Book a Growth Assessment," "See a Case Study," "Book a Performance Review").

---

# PART 6: GLOBAL TECHNICAL & SEO NOTES

- **Global schema:** Organization schema (with logo, sameAs social links) and WebSite schema on every page via site-wide layout; BreadcrumbList on every page below Home; FAQPage schema on any page with an FAQ accordion (Home, all 6 service pages, Industries).
- **Internal linking rule:** every service page links to (a) the Services hub, (b) at least one Industry it serves, (c) at least one relevant case study, and (d) the Contact page. Every Industry module links to its best-fit case study and relevant service page(s).
- **URL structure:** flat, descriptive, hyphenated, no trailing parameters. Matches the sitemap in Part 2 exactly.
- **Core Web Vitals consideration:** hand-drawn SVG animations and mock dashboard widgets should be lazy-loaded below the fold and served as optimized SVG/Lottie rather than video where possible, to protect LCP/CLS scores despite the motion-heavy design direction.
- **Accessibility:** Coral (#FA6F61) on Cream (#FBF1E7) and Charcoal (#2A211D) backgrounds should be contrast-checked for WCAG AA at all text sizes used; hand-drawn annotation marks are decorative and must not be the sole carrier of information (pair with text/number, never color/annotation alone).

---

*End of blueprint. Every page above is written as final production copy per the brief, not a summary, with SEO, wireframe, CTA, visual, and motion direction included for build-out.*

