---
name: saas-seo-geo-optimizer
description: Full-lifecycle SEO, GEO (Generative Engine Optimization), and AEO growth system for AI tool sites, SaaS products, and indie web apps. Synthesizes the 23-chapter SaaS SEO Playbook (JeffLi1993/saas-seo-playbook), 5D Low-Competition Keyword Opportunity Scoring, SAAS_SEO_AI_KNOWLEDGE_BASE (SEO-001 to SEO-019), and Deep SEO/GEO Audit Protocols. Use whenever the user asks to plan site architecture, research keywords, build Topic Maps or Page Owner tables, design or optimize Tool/Feature/Solution/Blog/Comparison/Alternatives pages, implement Technical SEO or Core Web Vitals, build backlinks or AI directory launch plans, scale programmatic SEO (pSEO) or multi-language i18n SEO, optimize for AI search engines (ChatGPT Search, Perplexity, Google AI Overviews, Claude, Doubao) via llms.txt and Schema entity alignment, or run a code-level SEO/GEO audit and fix workflow.
---

# SaaS SEO and GEO Optimizer

## Summary

A full-stack engineering and growth system that transforms SEO and GEO (Generative Engine Optimization) from scattered ranking tricks into a closed-loop architecture: **Product fulfills search tasks, Content delivers verifiable Information Gain, Technology guarantees crawlability and AI extractability, and Backlinks establish off-site entity trust**.

## When to Use

- Planning a new SaaS, AI tool site, or content-driven web app from day one (ICP definition, Topic Map, Keyword-to-Page mapping, and URL directory design)
- Mining and prioritizing low-competition, high-conversion keywords using the 5-dimensional Heuristic Opportunity Score (`Quick Wins`, `Strategic`, `Avoid for Now`)
- Analyzing SEO competitors (especially fast-growing DR 30-50 sites) or deconstructing Google SERPs (`Type`, `Format`, `Angle`, and `SERP Overlap`) to generate an 11-field Content Brief
- Designing, writing, or refactoring Landing Pages, Interactive Tool Pages (10-module layout), Tutorials, Listicles (`Best X`), Alternatives (`X Alternatives`), Comparisons (`A vs B`), or programmatic SEO (pSEO) pages
- Implementing or auditing Technical SEO, On-Page SEO (`SEO-001` to `SEO-019`), Schema.org JSON-LD, internal link graphs (`Hub -> Cluster -> Leaf`), multi-language `hreflang`/`canonical` rules, or Core Web Vitals (`LCP`, `CLS`, `INP`, and Agentic Browsing)
- Executing off-site trust building (AI directories 0-to-1 launch, Product Hunt secondary wave, Guest Post pipelines, and partner links) or bi-weekly GSC/GA4 conversion reviews
- Optimizing for AI search engines and LLMs (ChatGPT, Perplexity, Google AI Overviews, Claude, Doubao) via Answer-First DOM structure, deterministic data tables, `llms.txt`, `site-index.json`, `/facts/` entity pages, `sameAs` entity reconciliation, and Query Fan-out coverage
- Running a deep SEO/GEO diagnosis and code-level remediation with `[CHANGE] / [EVIDENCE] / [RESULT] / [NEXT]` verification receipts

## Steps

### Step 1: Classify Evidence and Establish System Baseline (Playbook 0.1-1 & Audit Protocol)

Before making recommendations or editing code, classify all findings by evidence tier so you never fabricate third-party metrics or unverified claims:

- **`CONFIRMED`**: Verified directly from source code, HTTP response headers, live SERP inspection, Google Search Console (GSC) / Bing exports, or official Google Search Central documentation.
- **`SYNTHESIS`**: Derived by cross-referencing multiple SERP competitors, structural patterns, or multi-page audits.
- **`HEURISTIC`**: Internal opportunity scoring or directional estimates when paid keyword datasets (Ahrefs/Semrush) are unavailable. Mark missing third-party search volume or KD explicitly as `N/A - no verified keyword dataset`.

Apply the 4-layer collaborative system diagnostic triage:

- **Indexing issues**: Audit Technical SEO, `robots.txt`, `sitemap.xml`, `canonical`, and status codes first.
- **Impressions but no clicks**: Audit search intent alignment, `<title>` hook, and page container type.
- **Clicks but no conversions**: Audit whether the above-the-fold product/tool actually completes the user's task (Last-Click fulfillment).
- **Many pages but stagnant rankings**: Audit Information Gain, internal link weight flow, and off-site referring domains.

### Step 2: Define SEO ICP, Benchmark Competitors, and Score Keywords (Playbook Ch.2-5, 12 & 5D Model)

1. **Map the 3 Search Personas (SEO ICP 6D Canvas)**:
   - **Users (Practitioners)**: Search immediate tasks, tools, or prompts (e.g., `AI batch background remover`, `natal chart calculator`). Convert via immediate interactive tool usage.
   - **Buyers (Decision Makers / Devs)**: Search commercial comparisons, pricing, and API limits (e.g., `A vs B`, `X alternatives`, `X pricing`). Convert via comparison tables, transparent pricing, and trials.
   - **Learners**: Search concepts and how-to workflows (e.g., `how to calculate true solar time`). Convert via embedded free tool hooks and step-by-step guides.
   - Document 6 ICP dimensions: `Basic Profile (Role/Industry/Geo)`, `Behavioral Task`, `Intent Stage`, `Keyword Cluster`, `Evidence Preference (Price/Privacy/Accuracy -> dictates Content Angle)`, and `Conversion Path (Demo -> Signup -> Trial -> Paid)`. Validate unproven clusters quickly via small-budget SEM search ads before committing long-term SEO production.

2. **Benchmark Real SEO Competitors (Not Industry Giants)**:
   - Filter for fast-growing domain peers (**DR 30 to 50**, monthly visits over 100K, search traffic share over 40%, high non-brand traffic ratio) rather than 10-year DR 80+ incumbents.
   - Discover competitors via 4 query roots: Core category terms, `Best` listicles, `Alternatives` terms, and Use-Case/Feature terms.
   - Align their **Top Pages growth months** with **Referring Domains acceleration months** (`First Seen` sorted descending, filtered by `Dofollow` and `Best Links`) to reverse-engineer 90-day page and backlink targets. Walk through their #1 ranking page's conversion flow as a real user.

3. **Mine and Score Keywords (Rural-Surrounds-City Strategy)**:
   - Progress sequentially from **Blue-Ocean Specific Terms** -> **Mid-Tier Terms** -> **Head Terms**.
   - Prioritize Tier 1 Mandatory Product Pages (`Homepage`, `Feature`, `Solution`, `Pricing/API/Docs`) first for positioning, then allocate weekly capacity to Tier 2 Traffic Pages (`Tool`, `Blog`, long-tail) using the **5D New Site Opportunity Score** (25-point quick scale or 100-point weighted `HEURISTIC` scale):

| Dimension | Weight (100-pt) | Range (25-pt) | Scoring Criteria (0 = Lowest, 5 = Highest) |
| :--- | :--- | :--- | :--- |
| **1. Business Relevance** | **30%** | `0 - 5` | `5`: Product directly completes the exact search task. `3`: Adjacent step with natural bridge. `0`: Unrelated traffic (discard immediately). |
| **2. Intent Clarity & Intensity** | **25%** | `0 - 5` | `5`: Transactional/tool action or urgent edge-case troubleshooting. `4`: Commercial (`vs`, `alternatives`, `best for X`). `2`: Broad `what is` definition. |
| **3. SERP Vulnerability** | **20%** | `0 - 5` | `5`: Top 10 has DR < 35 sites, Reddit/Quora threads, or thin/outdated tool shells. `3`: Mid-tier blogs. `1`: Dominated by DR 80+ interactive tools. |
| **4. Information Gain Space** | **15%** | `0 - 5` | `5`: Can deliver unique deterministic calculators, lookup matrices, verified benchmarks, or multi-system reconciliation absent from Top 10. |
| **5. Site Fit & Conversion Path** | **10%** | `0 - 5` | `5`: Direct 1-click transition from tool/content hook into signup or paid workflow. `3`: 2-step nurture via internal link to Money Page. |

   - Bucket clusters into **`Quick Wins`** (20-25 pts / >= 80: build immediately), **`Strategic`** (15-19 pts / 60-79: build via Hub-and-Spoke), and **`Avoid for Now`** (< 15 pts / < 60: broad head terms; use only as homepage semantic support).

### Step 3: Architect Topic Map, Page Owners, and Book-Style URLs (Playbook Ch.6-7 & `SEO-005`/`SEO-006`)

Treat the website like a book: **Entity** = book subject, **Topic Map** = table of contents, **Page Owner** = chapter, **Internal Links** = reading map.

1. **Enforce the One-Cluster-One-Page Rule (`SEO-005`)**:
   - Formula: `1 Page = 1 Keyword Cluster + 1 Top Keyword + 1 Primary Search Intent = 1 Unique Page Owner`.
   - Test **SERP Overlap** before merging or splitting keywords: search two candidate queries in target-market Google. If Top 10 URLs overlap heavily (>= 4-5 shared URLs with the same page container), merge them into one Page Owner (highest-volume representative term = `Top Keyword`, variants = `Secondary Keywords`). If Top 10 URLs differ significantly (e.g., `AI PPT generator` vs `AI slide generator`), split them into separate pages with genuinely distinct product experiences.
   - Split a sub-page from a head term (e.g., `/instagram-hashtag-generator` from `/hashtag-generator`) only when: (1) sub-keyword volume/value justifies investment, (2) SERP treats it as an independent demand, and (3) you provide tailored product UX and data rather than just swapping `<title>`.
   - Maintain a 11-field **Page Owner Table** (`Topic`, `Keyword Cluster`, `Top Keyword`, `Secondary Keywords`, `Search Intent`, `Page Type`, `Page Owner`, `Proposed URL`, `Primary CTA`, `Status [Existing/Update/Merge/New]`, `Priority`) and a machine-readable `seo-intent-map.json` locking the root brand query to `/`.

2. **Standardize Subdirectory & Slug Architecture (`SEO-006`)**:
   - Always use subdirectories (`/features/`, `/solutions/`, `/tools/`, `/templates/`, `/blog/`, `/integrations/`, `/docs/`, `/facts/`) rather than splitting weight across subdomains.
   - Create a dedicated top-level directory only when it aligns with your Entity, represents a durable independent demand, supports multiple pages (keep 2-3 comparison posts in `/blog/` rather than creating an empty `/compare/`), and shares a consistent template.
   - Organize growing directories into 3 tiers: **Hub** (channel root) -> **Cluster** (category collection) -> **Leaf** (specific execution page), keeping click depth from homepage <= 3 clicks.
   - Enforce clean URL slugs: lowercase ASCII letters, hyphens (`-`), naturally containing the Top Keyword, stripped of filler adjectives (`free-best-online`) and years (`2026`), and locked in CMS so editing an H1 never mutates a published URL.

### Step 4: Execute SERP Research and Answer-First Content Production (Playbook Ch.13-16 & `SEO-010` to `SEO-012`)

1. **Compile the 11-Field SERP Content Brief (Ch.13)**:
   - Inspect target-market Google Top 10 (or Top 20 if mixed) and study **Low-DR Outlier Pages** (ranking on page 1 with few backlinks).
   - Record: `Keyword Cluster`, `Top Keyword`, `Secondary Keywords`, `SERP Overlap`, `Search Intent`, `Page Type (Tool/Feature/Solution/Blog)`, `Content Format (Tutorial/Listicle/Review/Comparison/Alternatives)`, `Content Angle (Free/No Sign Up/Batch/Deterministic)`, `Common Modules (Parity)`, `Content Gap (Superiority/Exclusivity)`, and `Low DR Reference`.

2. **Apply the 4-Layer Answer-First Architecture (SEO + GEO Unified Standard)**:
   - **Layer 1 - Answer-First Hero (`SEO-001`, `SEO-011`)**: `<h1>` and opening summary (< 120 words) must explicitly define **What** the product/page is, **Who** it serves, **How** its deterministic mechanism works, and the direct conclusion, followed by an anchor reading guide (`<nav class="reading-guide">`). Never use vague slogans as `<h1>`.
   - **Layer 2 - Working Tool Workspace / Free Interactive Hook (`SEO-002`)**: Place a zero-friction interactive workspace or lightweight client-side calculator above the fold.
   - **Layer 3 - High-Density Static Lookup Tables & Deterministic Evidence (`SEO-010`, `SEO-012`)**: Embed semantic HTML `<table>` matrices (parameter lookups, cross-system comparisons, boundary rules), real worked examples, and authentic UI screenshots. Explicitly separate **deterministic rule engines / verified specs** from **AI synthesis**.
   - **Layer 4 - 5-Dimension FAQ & Conversion Loop**: Select 5-8 real user questions from PAA, Reddit, Quora, and competitor gaps across 5 dimensions (Cognition, Comparison, Objections, Usage, Pricing), paired verbatim with `FAQPage` JSON-LD and contextual CTAs.

3. **Standardize High-Conversion Page Templates (Ch.14-15)**:
   - **Interactive Tool Page (10 Modules)**:
     - *Upper*: `1. Intro/Hero` (H1 + 1-2 sentence pitch + working tool UI), `2. Templates/Presets` (1-click sample inputs).
     - *Middle*: `3. Use Cases` (Verb + output H3s with persona & result visuals), `4. How-to` (`How to use {Top Keyword} in 3 steps` with real UI screenshots), `5. Key Features` (row 1: top 3 unique differentiators; row 2: baseline features; never claim unsupported features).
     - *Lower*: `6. Pricing/Free Quota`, `7. Testimonials` (omit if no real reviews yet), `8. FAQs` (5 dimensions), `9. Explore More` (sibling tools & Hub links), `10. Bottom CTA` (H2 with Top Keyword scrolling back to tool UI). Keep English copy crisp (sentences <= 20 words, paragraphs <= 3 lines).
   - **Alternatives Page (`Best X Alternatives in 2026`, timeless URL slug)**: Open with a **`Why Switch` module** diagnosing the incumbent's 3 pain points (persona mismatch, feature caps, pricing), rank your own product #1 proving how it solves those exact pain points (while disclosing honest boundaries), evaluate contenders consistently, and close with a master comparison `<table>`.
   - **Comparison Page (`A vs B`)**: Upfront side-by-side verdict table -> H2 per evaluation dimension following a strict `A -> B -> Verdict` sequence with real screenshots/prices -> conditional recommendation (`Choose A if..., Choose B if..., or try Our Product for unique need C`).

4. **Deliver 3-Tier Information Gain & E-E-A-T (Ch.16)**:
   - Progress from **Parity** (covering baseline SERP H2s) -> **Superiority** (adding tested parameters, failure recovery, and real screenshots in H3s) -> **Exclusivity** (adding proprietary capabilities or datasets as prominent H2s).
   - Prove **E-E-A-T**: first-hand execution screenshots (**Experience**), algorithm/boundary explanations (**Expertise**), complete entity pages (`About`, `Contact`, `Privacy`, `Terms`, verified author bios) (**Authoritativeness**), and verifiable citations + honest limits (**Trustworthiness**).

### Step 5: Lock In Technical SEO Foundation, i18n, and Core Web Vitals (Playbook Ch.8-11, Outline 22 & `SEO-007` to `SEO-009`, `SEO-015`)

Always remediate in **Template-First Order**: `1. Homepage -> 2. Directory Templates (/tools, /blog, /features) -> 3. Individual Exception Pages`.

1. **On-Page Pre-Publish & Post-Publish Loop (Ch.9)**:
   - Ignore `<meta name="keywords">`. Put `Top Keyword` naturally near the start of `<title>` without forcing a rigid 60-character cutoff. Write descriptive image `alt` text (`AI background remover result on curly hair`), never keyword lists.
   - Inspect GSC query performance at **Day 1, Day 7, and Day 28** post-publish to backfill missing sub-queries.

2. **Technical SEO Hygiene & 9 Pitfall Fixes (Ch.8, 10 & `SEO-007`, `SEO-008`)**:
   - Protect staging sites with HTTP auth or `noindex` (never `robots.txt Disallow` alone, which blocks Google from seeing `noindex`).
   - Unify `http/https`, `www/non-www`, and trailing slashes via single-hop `301` redirects; return real `404`/`410` when no replacement exists (avoid Soft 404 homepage redirects).
   - Keep `sitemap.xml` clean: only `200` indexable canonical URLs (<= 50,000 URLs / 50MB per file, sharded by language such as `sitemap-en.xml`, `sitemap-ja.xml`), updating `lastmod` **only** when visible content changes.

3. **Multi-Language (i18n) SEO Rules (Outline 22, Ch.7, 9, 10 & `SEO-009`)**:
   - Validate target-country search demand and payment readiness before expanding locales.
   - 301 redirect duplicate default-language paths (`/en/` -> `/` when root is English).
   - Every localized page (`/ja/`, `/ko/`, `/zh-hant/`, `/es/`) must use its own **self-canonical** (never canonicalize `/ja/page` to `/page`) and bidirectional `hreflang` tags (including self and `x-default`).
   - Map the native local `Top Keyword` and rewrite examples, currencies, cultural context, Schema JSON-LD, and internal anchors with zero source-language bleed.

4. **Core Web Vitals & Agentic Browsing (Ch.11 & `SEO-015`)**:
   - **LCP (CrUX 75th percentile <= 2.5s)**: Use WebP/AVIF, **never lazy-load the above-the-fold LCP image**, and expose it in initial HTML without waiting for client JS.
   - **CLS (<= 0.1)**: Set explicit `width`, `height`, or `aspect-ratio` on media, embeds, and tool containers; use overlay banners rather than layout-pushing top bars.
   - **INP (<= 200ms)**: Measures next-frame visual feedback, not backend AI generation time. Switch buttons to `Loading` state immediately on click, debounce inputs, and remove bloated third-party scripts. Target PageSpeed >= 90 Desktop / >= 80 Mobile.
   - **Agentic Browsing**: Keep a semantic `Accessibility Tree` (`<main>`, `<article>`, `<nav>`, `<button>`, `<label>`) and low CLS so AI browser agents interact accurately.

### Step 6: Build Internal Link Maps and Sustainable Off-Site Authority (Playbook Ch.17-20 & `SEO-014`)

1. **Three-Way Internal Linking (`Hub <-> Cluster <-> Leaf`)**:
   - **Downward**: Homepage/Hubs -> Clusters -> Leaves (0 orphan pages when diffing `sitemap.xml` against site crawl).
   - **Upward**: Leaves -> Parent Hubs and primary Money Pages via breadcrumbs and contextual links.
   - **Horizontal**: Blog tutorials/comparisons <-> Interactive Tool pages (`Read -> Use` loop).
   - **Anchor Text Rules**: State the destination's exact capability (`AI video generator`) or official brand role (`{Brand}官网首页` pointing to `/`). Never use vague `click here` / `learn more` or bare `Home` when brand consolidation is needed.

2. **Off-Site Backlink System (Traffic Accuracy > Relevance > DR)**:
   - **Phase 1 (0-to-1 AI Directories / Adding - Ch.19)**: Shortlist ~20 relevant directories (monthly visits > 100K, DR > 50). Customize titles/screenshots per directory audience and track conversions via UTM parameters.
   - **Phase 2 (Major Releases & Second Wave / Earning - Ch.19)**: Launch major updates on Product Hunt, Uneed, Peerlist, and Show HN, then pitch independent bloggers, newsletters, and reviewers to earn **direct editorial links to your domain** (PH profile links alone do not count as new referring domains to your site).
   - **Phase 3 (Sustainable Weekly Guest Post & Partner Pipeline - Ch.20)**: Target **Money Pages** and **Positions 11-20 Striker Pages**. Reverse-engineer DR 30-50 competitors' newest referring domains (`First seen` descending, `DR > 50`, host organic traffic >= 5,000/mo), snowball via host sites' `Outgoing links -> Linked domains`, place brand + capability anchors in the upper half of articles, leverage upstream/downstream Partner/Customer Story pages, and review bi-weekly across a 7-field tracker.

### Step 7: Engineer GEO, Brand SERP Defense, and Programmatic SEO (Playbook Ch.21-23 & `SEO-001` to `SEO-019`)

1. **Five Pillars of GEO & Machine-Readable Discovery (`SEO-016` to `SEO-018`)**:
   - **AI Crawler Policy (`robots.txt`)**: Explicitly `Allow` AI search citation bots (`OAI-SearchBot`, `ChatGPT-User`, `PerplexityBot`, `Claude-SearchBot`, `Google-Extended`, `Applebot-Extended`) across public content paths while protecting private routes.
   - **Discovery Suite**: Maintain `/llms.txt` (brand definition, core differentiators, deterministic boundaries, canonical URLs), `/site-discovery.txt`, `/site-index.json`, and a dedicated entity fact sheet (`/facts/<brand>`).
   - **Query Fan-out Coverage**: Anticipate how LLMs expand a user prompt into conditional sub-queries (persona constraints, free quota, privacy, cross-tool discrepancies) and answer them in structured H2/H3 modules and HTML `<table>` matrices.

2. **Brand SERP #1 Defense & Entity Reconciliation (`SEO-001`, `SEO-005`, `SEO-013`, `SEO-018`)**:
   - If searching your brand name on Google does not rank `/` at #1, diagnose and fix all 5 root causes:
     1. *Knowledge Graph Pollution (`SEO-013`)*: Strip any unverified or placeholder Wikidata ID (`Q...` returning 404) or fake `aggregateRating` from all HTML pages and generator scripts.
     2. *Homepage Navigational Signal (`SEO-001`)*: Synchronize `<title>`, `og:title`, `twitter:title`, and `#webpage` JSON-LD `name` to start with `{Brand Name}官网 ({domain}) | {Core Value Prop}`.
     3. *Internal Brand Cannibalization (`SEO-005`, `SEO-014`)*: Prevent `/facts/` or `/qa/` pages from starting `<title>` with the bare brand name; lock brand terms to `/` in `seo-intent-map.json`; upgrade internal anchors pointing to `/` from generic `首页`/`Home` to `{Brand Name}官网首页`.
     4. *External Directory Interception (`SEO-018`)*: Add high-ranking third-party product profiles (e.g., Product Hunt, Watcha, Chanpinpai, industry directories) and official GitHub repos to your homepage `Organization.sameAs` array, and place direct brand-anchor backlinks on those external profiles pointing to `https://{domain}/`.
     5. *GSC Re-Indexing*: Trigger manual URL Inspection -> Request Indexing on `/` after deploying metadata fixes.

3. **Safe Programmatic SEO (`Template x Structured Verified Data x Automation` - Ch.21)**:
   - Combine `Function x Scenario x Industry x Language x Model` only where search demand is verified.
   - Populate 5 authentic data slots per page: `1. Verified Output/Case`, `2. Reproducible Steps + UI Screenshot`, `3. Runnable Prompt/Preset`, `4. Source-Backed Comparison Specs/Pricing`, and `5. Capability & Boundary FAQ`.
   - Manually validate **10 diverse sample pages** in GSC for indexing, query match, and conversion before scaling. Rely on `sitemap.xml` and internal Hub links (never abuse Google Indexing API for non-job/non-livestream pages).

### Step 8: Bi-Weekly Conversion Review and `[CHANGE] / [EVIDENCE] / [RESULT] / [NEXT]` Audit Receipt (Playbook Ch.22 & Audit Protocol)

1. **Two-Stage Data Review (Ch.22 & `SEO-019`)**:
   - **Cold Start (Directory View)**: Track weekly by directory (`/tools/`, `/blog/`) across new non-brand pages, tool completeness, non-brand keyword rankings, volume, and directory clicks.
   - **Growth Stage (Landing Page Conversion View)**: Track weekly and compare bi-weekly across `Period`, `Landing Page URL`, `Directory`, `Organic New Users`, `New Signups`, and `Paid Users`. Use proven **Money Pages** to drive adjacent `Alternatives / Vs / Review` keyword mining and backlink allocation.

2. **Four-Part Engineering Execution Receipt**:
   - **`[CHANGE]`**: Exact files, templates, `<head>` metadata, JSON-LD schemas, internal links, and discovery files (`llms.txt`, `sitemap.xml`, `seo-intent-map.json`) modified (classify each fix by `P0 / P1 / P2` and `SEO-001` to `SEO-019`).
   - **`[EVIDENCE]`**: Exact build scripts, audit commands (`curl -I`, DOM/Schema validators), and unit test suites executed.
   - **`[RESULT]`**: Quantitative `PASS / WARNING / FAIL` counts across URL reachability, zero intent conflicts, Schema validity, GEO readiness, and zero cross-locale character bleed.
   - **`[NEXT]`**: Concrete post-deployment actions in GSC, Bing Webmaster Tools, and external backlink channels.

## Gotchas

- **Never fabricate Wikidata IDs, Schema ratings, or keyword volume**: Broadcasting a non-existent Wikidata placeholder (`Q...`) or fake `aggregateRating` stars in JSON-LD destroys Knowledge Graph trust. Likewise, never invent search volume or KD numbers when external datasets are absent; use `N/A - no verified keyword dataset` and label internal scores as `HEURISTIC`.
- **Never pad word count or stuff `meta keywords`**: Google ignores `<meta name="keywords">` and does not rank a 2,200-word essay over a 2,000-word competitor simply for length. Replace fluff with interactive tools, static lookup tables, edge-case troubleshooting, and real screenshots.
- **Avoid multi-page boilerplate duplication (`SEO-010`)**: Generating dozens of pages that share identical context paragraphs with only the entity name swapped triggers thin/duplicate content demotions. Every page must contain unique deterministic data or scenario-specific guidance.
- **Do not rely on `robots.txt Disallow` to de-index staging or private pages**: `Disallow` prevents Googlebot from reading a page's `noindex` tag while still allowing the URL to appear in search results if linked. Use authentication or `noindex` (while allowing crawl) to remove pages from the index.
- **Do not confuse INP with backend AI generation time**: A 20-second video generation job does not hurt Core Web Vitals INP as long as clicking the button updates the UI to a `Loading` state within 200ms without blocking the main thread.
