## Content Generation Workflow Checklist

---

### Step 1: Input Parsing
- [ ] Target URL is provided and readable
- [ ] SKILL.md is loaded and active
- [ ] Checklist.md is loaded
- [ ] Internal linking page URLs are provided or Musemind default internal link targets are used

---

### Step 2: Job Classification
- [ ] Job type determined from SKILL Step 1 (New Blog Post / Landing Page / Content Improvement / SEO Brief)
- [ ] If a target URL is provided -> classified as Content Improvement
- [ ] If job type is ambiguous -> ask the user before proceeding

---

### Step 3: Research and SERP Analysis
- [ ] Live target URL fetched and reviewed
- [ ] Primary keyword and search intent identified from the page
- [ ] Top SERP competitors pulled for the target keyword
- [ ] Competitors analyzed for: content type, structure, depth, entities, FAQs, CTAs, trust signals
- [ ] Musemind's current page benchmarked against SERP results
- [ ] Competitor slogans and claims verified from their current live homepages
- [ ] Competitor analysis documented with clear findings

---

### Step 4: Content Audit (Content Improvement jobs only)
- [ ] Current page audited across: intent match, keyword targeting, heading structure, entity coverage, E-E-A-T signals, internal links, CTAs, FAQ quality, schema, outdated claims, thin sections
- [ ] Gap analysis table produced: Area / Current Issue / Why It Hurts / Recommended Fix

---

### Step 5: Content Strategy
- [ ] Primary keyword defined
- [ ] Secondary keywords defined
- [ ] Search intent classified (Informational / Commercial / Transactional / Navigational / Local)
- [ ] Target audience defined
- [ ] Funnel stage identified
- [ ] Content angle and differentiator defined
- [ ] Main pain points and objections listed
- [ ] Conversion goal stated
- [ ] Internal linking opportunities mapped against provided URLs
- [ ] Schema type selected

---

### Step 6: Content Generation
- [ ] Correct structure used based on job type (Blog Post / Landing Page / Content Improvement per SKILL Steps 7, 8, 9)
- [ ] H1 is keyword-focused and used exactly once
- [ ] Introduction is strictly between 100 and 120 words
- [ ] No generic filler opening (e.g., "In today's digital landscape")
- [ ] TL;DR table added directly after the introduction
- [ ] Active voice used throughout
- [ ] No em dashes anywhere in the content
- [ ] No excessively short sentences (2 to 4 words only)
- [ ] Paragraph length: 2 to 4 sentences, one idea per paragraph
- [ ] Primary keyword appears naturally in: H1, first 100 words, at least one H2, meta title, meta description
- [ ] Semantic entities and related keywords covered naturally
- [ ] Trust signals incorporated (proof, examples, realistic claims)
- [ ] No vague claims ("stunning designs", "world-class solutions", etc.)
- [ ] No standalone promotional CTA sentences (e.g., "Ready to build X? Talk to Musemind.") - CTAs must be embedded within a dedicated CTA section block, not dropped as isolated lines
- [ ] Moderate CTA placed in the middle of the content
- [ ] Moderate CTA placed at the end of the content
- [ ] 8 to 12 FAQs included (unless topic does not justify it)
- [ ] FAQs section uses `## FAQs` (H2), each question as `### Question?` (H3), each answer as a plain paragraph
- [ ] AI Relevance and Role section included when AI meaningfully affects the topic, covering: current role, empowerment, future impact, practical application
- [ ] Content structure is consistent and logical throughout

---

### Step 7: Fact-Check Audit
- [ ] Every numeric claim (percentages, dates, rankings, pricing, survey results) has a cited source
- [ ] No statistics cited from another blog without tracing the original source
- [ ] Competitor claims verified against current live pages
- [ ] No invented data, client names, case studies, awards, or performance claims
- [ ] Source disagreements flagged explicitly using the format defined in SKILL Step 11
- [ ] Fact-check audit table produced: Claim / Source / Status

---

### Step 8: SEO Metadata
- [ ] Meta title provided
- [ ] Meta description provided
- [ ] URL slug preserved (unless user requested a new one)
- [ ] Secondary keywords listed

---

### Step 9: Internal Linking Plan
- [ ] Internal links placed using provided page URLs
- [ ] Anchor text is descriptive (no "click here", "learn more", "read this")
- [ ] Internal linking plan table produced: Link Type / Page / Anchor Text / Placement

---

### Step 10: Image SEO Suggestions
- [ ] Image suggestions provided for each major section
- [ ] File names provided for each image
- [ ] Alt text is descriptive and not keyword-stuffed
- [ ] Image suggestions table produced: Section / Image Idea / Image Generation Prompt / File Name / Alt Text

---

### Step 11: Quality Gate (Pre-Delivery)
- [ ] Helpful Content Check passed (SKILL Step 16)
- [ ] E-E-A-T Check passed
- [ ] SEO Check passed
- [ ] Conversion Check passed
- [ ] Fact-Check Check passed
- [ ] Every item in this checklist verified before output is generated

---

### Step 12: File Output
- [ ] File 1 - Full Output saved as `[slug]-full-output.md`: includes audit, gap analysis, strategy, full content, fact-check audit, internal linking plan, image suggestions, and this checklist with pass/fail status
- [ ] File 2 - Content Only saved as `[slug]-content-only.md`: contains only the final publishable content with no workflow or audit sections
- [ ] Both files saved inside `output/[slug]/`
