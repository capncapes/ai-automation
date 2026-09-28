# Resume Format

## Purpose
Update, refine, and regenerate resume content while strictly preserving visual style and formatting rules for PDF export.

## Primary Rules
1. **Preserve all style values exactly.** Do not normalize spacing, colors, font sizes, or heading levels.
2. **Keep career history accurate.** Do not invent, remove, or change employers, dates, or titles, *except where alternates are provided ("Alternate" or "Also")*.
3. **Use consistent date formatting** across all experience entries.
4. **Output Markdown only.** The Markdown must map cleanly to PDF styles without reformatting.
5. **Do not alter style contract values** during content generation.
6. **Left-justify all text**. Never center text.
7. **Limit** to two pages. No more than two (2) pages long.
8. **Use only a single-column layout.** No headers, footers, tables, or columns in the final exported file.

## Style Contract

### Typography

All measurements are in points (pt). Line height is a multiplier. All text is `Georgia`. Employer names should be **bolded**. Date ranges should be *italicized*.

| Style     | Color     | Font size | Font weight | Line height | Spacing before | Spacing after |
|-----------|-----------|-----------|-------------|-------------|----------------|---------------|
| Title     | `#0072B1` | 16pt      | 700         | 1.0         | 0pt            | 6pt           |
| Heading 1 | `#0072B1` | 12pt      | 700         | 1.0         | 0pt            | 12pt          |
| Heading 2 | `#0072B1` | 16pt      | 700         | 1.0         | 16pt           | 8pt           |
| Heading 3 | `#121212` | 12pt      | 400         | 1.0         | 0pt            | 8pt           |
| Heading 4 | `#121212` | 10pt      | 400         | 1.15        | 4pt            | 6pt           |
| Normal    | `#121212` | 10pt      | 400         | 1.3         | 0pt            | 0pt           |

- `#0072B1` = LinkedIn blue (used for Title, Heading 1, Heading 2).
- `#121212` = Near-black dark gray (used for Heading 3, Heading 4, Normal text).

### Heading Hierarchy

- **Title**: Resume document title (e.g., "Full Name").
- **Heading 1**: Document headline (e.g., "Marketing Automation Specialist" or "Marketing & Communications").
- **Heading 2**: Section headers (e.g., "Experience", "Skills", "Education").
- **Heading 3**: Employer names or company-level groupings.
- **Heading 4**:
  - Job titles within an employer.
  - Sub-sections or specialized role descriptors (optional).
- **Normal**: All body text, bullet points, and descriptive paragraphs.

### Date Formatting

- Use `MMM YYYY-MMM YYYY` or `MMM YYYY-Present` consistently.
- Examples:
  - `Jun 2023-Present`
  - `Mar 2021-Dec 2022`
- **Do not insert spaces** around the dash in date ranges.
- Use the same date style for every experience entry.
- Do not use slashes (`/`) or numeric-only formats like `01/2023`.
- Date ranges should be *italicized*.

### Employment Structure

For most employers:
- One employer name (**bolded**) and location, separated by a pipe (Heading 3).
- One job title and date range, separated by a pipe (Heading 4).
- One date range on the same line as the job title, separated by a pipe (e.g., `Marketing Director | Aug 2013-Jan 2016`).

For employers with multiple roles (e.g., promotions):
- One employer name (Heading 3).
- Separate job title entries (Heading 4) for each role.
- Each job title has its own date range on the same line, separated by a pipe.
- Each job title has its own bullet list of responsibilities/accomplishments.
- Job roles should be in descending order.

Example for multiple roles at one employer:

```markdown
### **Employer Name** | City, ST

#### Senior Email Developer | *Jun 20XX–Apr 20XX*

- Built AMPScript automation workflows
- Managed Salesforce Marketing Cloud and ActiveCampaign automations

#### Digital Media & Web Developer | *Dec 20XX–Jun 20XX*

- Led email metrics analysis and campaign reporting
- Extracted data from Salesforce Marketing Cloud
```

---

## Page setup

### Margins
- Standard: **1.0" on all sides** (top, bottom, left, right).
- Minimum acceptable: **0.5" on all sides** — never lower. Margins may be adjusted between 0.5" and 1.0" to fit content.
- **Left and right margins must be identical**.
- **Top and bottom margins must be identical**.

### PDF export for AI-generated resumes

- **For Google Docs with Document Tabs:** Use Print → PDF to avoid tab names in header
- **For standard Google Docs (no tabs):** File → Download → PDF is fine
- **For Microsoft Word:** File → Save As → PDF (native converter)
- **For AI Markdown tools:** Use the tool's standard PDF export
- **File size: Keep under 5 MB** (most ATS systems have size limits)
- **Verify NO content in headers/footers** before submitting
- **Check exported file** preserves margins and formatting

---

## Content Guidelines

### Bullet Points

- Use plain dash bullets: `-` (never `•`, `○`, `●`, or special symbols)
- Use 2 or 3 bullet points per job title operating within last 5 years (based on relevance to job description)
- Use 1 or 2 bullet points per job title operating more than 5 years from today (based on relevance to job description)
- When possible, each bullet should include: [past tense, action verb] + [tool / method] + [measurable outcome] (e.g. "Optimized and personalized email send times to increase average click rates by 13%")
- Each bullet is a single paragraph with no hanging indentation
- Set padding-left: 12pt for bullet position, text-indent: -12pt to align text
- Start with strong action verbs (Built, Led, Designed, Implemented)
- Include measurable outcomes when available (percentages, time saved, revenue)
- The bullet point with the strongest business impact (based on provided job description) should be ordered first
- Keep bullets concise: 1–2 lines each
- Do not use "I" or "we" pronouns

### Skills Section

- Group skills by category (e.g., "Email Platforms", "Data & Analytics", "Automation", "Web Development").
- Use Heading 4 for category names.
- Use Normal text for skill lists.

### Education Section

- Use Heading 3 for institution names.
- Use Heading 4 for degree/certification titles.
- Use Normal text for dates and additional details.

---

## Rendering Instructions

When generating Markdown for PDF export:

1. **Strictly preserve the style map:**
   - Title: `#1155CC`, 20pt, line height 1.0, 0pt before, 6pt after.
   - Heading 1: `#1155CC`, 12pt, line height 1.0, 0pt before, 12pt after.
   - Heading 2: `#1155CC`, 16pt, line height 1.0, 16pt before, 8pt after.
   - Heading 3: `#121212`, 12pt, line height 1.0, 0pt before, 8pt after.
   - Heading 4: `#121212`, 10pt, line height 1.1, 4pt before, 6pt after.
   - Normal: `#121212`, 9.5pt, line height 1.3, 0pt before, 0pt after.
2. **Use consistent date ranges** with no spaces around the dash.
3. **Do not alter any style values** during content generation.
4. **Output Markdown only.** Do not include HTML, CSS, or Python code unless explicitly requested.
5. The Markdown should be ready for PDF rendering without reformatting.

---

## Example output structure

```markdown
# Full Name

## Experience

## Employer Name

### Senior Email Developer
Jan 20XX-Present

- Built AMPScript automation workflows
- Managed Klaviyo and ActiveCampaign integrations

### Marketing Automation Specialist
Mar 20XX-Dec 20XX

- Led email metrics analysis and campaign reporting

## Skills

### Email Platforms

- Klaviyo
- Salesforce Marketing Cloud
- ActiveCampaign

### Data & Analytics

- SQL
- Python
- Google Analytics 4
- Grafana

## Education

### University Name
Bachelor of Science in Field of Study
20XX-20XX
```

---

## Usage notes

- When updating resume content, always preserve the style contract.
- If the user provides new job data, integrate it using the same structure.
- If the user asks for style changes, update the style contract section explicitly and regenerate the resume.
