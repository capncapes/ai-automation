---
name: resume-update
description: "Drafts resumes, cover letters, LinkedIn content, and prospecting emails. Triggers on: 'update my resume', 'draft a cover letter', 'draft an email to the hiring manager', and requests to generate content based on the user's professional background."
---
 
## Content Creation
 
Personalized resume optimizations and generation of other professional content (cover letters, LinkedIn content, job board profiles, emails to hiring managers, etc.) for the purposes of career advancement and job searches. Resumes should be generated as PDFs only if requested by the user (see `resume-format.md`). **Until content is approved by the user and requested as a PDF, resume content should be provided as text.** Ask for the job description if not initially provided.
 
### Scope
 
LinkedIn and job board profile content, email correspondence, professional descriptions, resume content, cover letters.
 
### Channel-Specific Rules
 
Always read `candidate-profile.md` and `career-history.md` before generating any content — they contain the authoritative record of the user's roles, accomplishments, strengths, skills, certifications, education, and motivations. Also read `recommendations.md` for professional recommendations of the user written by former colleagues and supervisors. Use recommendations sparingly and intentionally; do not quote more than 20 words. Note that user has not managed anyone directly in the traditional sense but has mentored and trained multiple colleagues. See Notes.
 
#### Resumes
 
- Professional Summary: Limit to one sentence in most cases; two is fine as an exception to the rule. Mention job title of the desired position and UVA of the user (see Notes). Always lead with results, numbers, or business impact. The summary should not sound like a job description.
- Work Experience: 1-4 bullet points for each job experience, giving more weight to more relevant positions. Prioritize results and business impact when deciding what to leave out. Ensure that there are no gaps between roles. Each experience should read like a list of accomplishments rather than a job description. If a job description asks for less than 6 years of experience: Exclude everything before Mercy Multiplied, avoid mentioning a number of years of experieince, and leave off the undergrad graduation date.
- Skills: Generate a list of skills and tool proficiencies based on user's strengths and skills relevant to the job description. Refer to the Abilities section of `career-history.md` and combine the **Skills**, **Languages & Frameworks**, and **Software & Platforms** into one section of relevant keywords. (Do not include any Microsoft Office software unless the job description specifically mentions it and it's in the list.) Place this section after Work Experience unless software/tool proficiencies are a primary qualification for the job, then place it directly before Work Experience. See Notes.
- Volunteering: Check `candidate-profile.md`.
##### Salesforce Marketing Cloud
 
When a job description requires Salesforce Marketing Cloud (including alternate names), initial references to SFMC should be very specific (e.g. "SFMC Enterprise 2.0, 2 BUs, 100K active contacts, AMPscript and SQL heavy") and use Salesforce jargon to reinforce deep familiarity with the platform. Individual modules (listed below) should be prioritized by mention in the job description; they are listed in order of significance (always mention Journey Builder, leave out Intelligence Reports and Einstein unless there's extra space or the JD mentions them specifically). Always name the Salesforce modules and features listed in the job description **unless there's no documented use in `career-history.md` or `candidate-profile.md`**.
 
- Account type: Enterprise 2.0
- Business units: 2
- Active contacts: 100,000
- Modules: Journey Builder, Automation Studio, Email Studio, Web Studio, Contact Builder, Intelligence Reports, Einstein
#### Cover Letters
 
- **Important:** Focus on the organization's (or industry's) challenges and how the user can meet those needs. Prioritize this angle; ask the user if there are known challenges, then attempt to identify challenges if the user doesn't know. If no industry or organizational challenges can be identified, then move on to drafting the cover letter around the user's strengths.
- When relevant based on job description, position the user as at the center of marketing strategy, customer data, and technical execution within a marketing context.
- Identify the top 3 skills required for the job and match the user's experience and skills.
- Use `recommendations.md` to enhance cover letters with concise direct quotes when relevant and helpful.
- Tone should match the job description. If description uses puns or company nicknames for employees, repeat those where appropriate (e.g. "Googlers" for Google employees).
- Keep the writing direct; don't waste the reader's time with redundancy.
#### LinkedIn
 
- Posts: First 2-3 lines must function as a standalone hook. "See more" truncation kills LinkedIn posts — if the hook before the fold is weak, engagement drops to near zero. The first 2-3 lines must carry the entire post's weight. Target 900 characters total. The target audience for marketing and analytics posts is Non-Technical Decision Makers.
- About section: Tell a story. Theme: bridging the gaps between marketing strategy, customer data, and technical execution. Aim for approximately 1,300 characters. Just like with posts, the first 2-3 lines must function as a standalone hook.
- Position descriptions: Tone should be energetic and optimistic, focusing more on the big picture than the daily routine. Be sure to mention any hard stats and measurable business impacts, though. Aim for <700 characters.
#### Email
 
- Subject lines: 20-40 characters. Eye-catching, direct, and friendly.
- Introduce the user as a [relevant job keyword] professional. Treat emails as abridged cover letters, focusing on the top ways the user matches the job description.
- Emails are plain text unless specified otherwise.
## Notes
 
- User has not managed or supervised staff, but has cross-trained colleagues and junior associates at multiple organizations. He has led projects and senior team meetings, and he has delegated tasks, in addition to playing key roles in cross-functional collaboration with marketing, data engineering, events, product, and fundraising stakeholders. Be careful with the words "led" or "managed" in this context; do not communicate official supervisory positions.
- Unique Value Add (UVA): Focus on how the user solves problems, alleviates pain, saves money, and makes money. Credentials are features; hiring managers want benefits.
- If appropriate for the job, split the keywords into subgroups based on areas of expertise (categorized lists vs. flat list). Always optimize for applicant tracking system (ATS) scanners unless otherwise instructed by the user.
 