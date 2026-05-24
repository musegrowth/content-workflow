# Content Workflow

## Step 1: URL Analysis & Initialization
- Read the first/next URL from `URL.txt`.
- Extract the **slug** (last part of the URL after the final `/`).
  - Example: `https://musemind.agency/blog/my-target-keyword` -> slug is `my-target-keyword`

## Step 2: GSC Data Integration
- Check `GSC_data/` folder for a CSV file matching the slug. Accept either:
  - Exact slug name: `my-target-keyword.csv`
  - Full URL-based name where the slug appears at the end: e.g., `musemind.agency-blog-my-target-keyword.csv`
  - In all cases, match by checking if the filename (without `.csv`) **ends with** the slug.
- **If found:** Read and analyze the CSV - extract top queries, clicks, impressions, CTR, and average position. Use these insights to:
  - Prioritize high-impression/low-CTR queries (opportunity keywords to target in headings/body)
  - Reinforce queries already driving clicks (confirm coverage)
  - Identify query intent gaps and address them in the content structure
- **If not found:** Proceed without GSC data and note this in the full output.

## Step 3: Content Generation
- Generate content following all instructions, tone, format, and rules in `SKILL.md`.
- Naturally integrate any GSC data from Step 2.

## Step 4: Quality Assurance
- Evaluate content against all criteria in `checklist.md`.
- Confirm internally: *"Did I read `GSC_data/[slug].csv`, analyze its queries, and use those insights in the content (if the file existed)?"*
- Refine content if it fails any checklist item.

## Step 5: File Output Generation
Create `output/[slug]/` and save two files inside it:

| File | Contents |
|------|----------|
| `[slug]-full-output.md` | Full content output with audit, strategy, metadata, workflow context, fact-check audit, internal linking plan, image suggestions, and checklist status |
| `[slug]-content-only.md` | Content only with no workflow logs, audit notes, or checklist |

---

## Execution
Type **"Start"** or **"Generate Content"** to begin processing all URLs in `URL.txt` sequentially.
