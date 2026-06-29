# Psychology Careers Hub — Project Brief for AI Editing Sessions

Paste this document at the start of any ChatGPT session before uploading HTML files to edit.

---

## What this project is

A web resource for psychology students at Liverpool Hope University, School of Psychology. It covers 11 career pathway areas, helping students understand what careers are available with a psychology degree, why they are well suited to them, and what they can do now to prepare.

The site is hosted on GitHub Pages. Ask your administrator for the current live URL.

---

## The files

The site is 15 HTML files, one PNG logo file, and three documentation files. All files must be kept in the same folder for navigation links and the logo to work correctly.

| File | What it is |
|------|------------|
| index.html | Homepage — the main hub page students land on first |
| employer-trends.html | Graduate Outcomes — pipeline data, aspiration gap, employer skills |
| roadmap.html | Build Your Employability — experience, careers support, LinkedIn/CV, skills table |
| alumni.html | Alumni profiles |
| poc.html | People, Organisations and Consultancy |
| research-data-evaluation.html | Research, Data and Evaluation |
| education.html | Education |
| marketing-consumer-behavioural.html | Marketing, Consumer and Behavioural Insight |
| behavioural-science.html | Behavioural Science and Behaviour Change |
| public-services-policy-justice.html | Public Services, Policy and Justice |
| charity-third-sector.html | Charity and Third Sector |
| sport-exercise.html | Sport and Exercise |
| forensic-legal.html | Forensic and Legal Psychology |
| digital-technology-hcd.html | Digital, Technology and Human-Centred Design |
| mental-health.html | Mental Health |
| logo.png | University logo — must always be in the same folder as HTML files |

---

## The navigation bar

Every HTML file contains an identical sticky navigation bar. The order is:

**Psychology Careers Hub — Graduate Outcomes — Career Pathways ▾ — Build Your Employability — Alumni**

The Career Pathways dropdown contains links to all 11 career theme pages.

CRITICAL RULE: If a new page is added, the nav bar in ALL other HTML files must be updated. Always flag this if a new page is being created.

---

## University header

Every page has a university header above the nav bar containing:
- The logo: `<img src="logo.png" alt="Psychology at Liverpool Hope University" style="height:120px;width:auto;">`
- "Liverpool Hope University" (18px bold white)
- "School of Psychology" (15px white)
- Background colour: `#1a3a5c`

The logo.png file must always be uploaded to GitHub alongside the HTML files.

---

## Footer

Every page has this slim footer at the bottom:

```
This resource was developed as part of a psychology employability internship project at Liverpool Hope University, School of Psychology. Last updated: [DATE]. © Liverpool Hope University 2026. Built by David Perkins, Aimee Dutton and Jackson Gray.
```

**Always update the Last updated date whenever making changes to any page.**

---

## Professional body links

Every org-name div must contain a hyperlink to the organisation's website, opening in a new tab. Format:

```html
<div class="org-name"><a href="https://www.cipd.org.uk" target="_blank" rel="noopener">CIPD</a></div>
```

Never leave an org-name as plain text.

Key organisation URLs:
- CIPD → https://www.cipd.org.uk
- British Psychological Society (BPS) → https://www.bps.org.uk
- BPS Division of Occupational Psychology → https://www.bps.org.uk/member-networks/division-occupational-psychology
- BPS Division of Forensic Psychology → https://www.bps.org.uk/member-networks/division-forensic-psychology
- BPS Division of Sport and Exercise Psychology → https://www.bps.org.uk/member-networks/division-sport-exercise-psychology
- BPS Division of Clinical Psychology → https://www.bps.org.uk/member-networks/division-clinical-psychology
- HCPC → https://www.hcpc-uk.org
- Market Research Society → https://www.mrs.org.uk
- Behavioural Insights Team → https://www.bi.team
- BASES → https://www.bases.org.uk
- UK Coaching → https://www.ukcoaching.org
- NCVO → https://www.ncvo.org.uk
- CharityJob → https://www.charityjob.co.uk
- Get Into Teaching → https://getintoteaching.education.gov.uk
- CIEHF → https://www.ciehf.ac.uk
- Civil Service Fast Stream → https://www.faststream.gov.uk
- Probation Institute → https://www.probation-institute.org
- College of Policing → https://www.college.police.uk
- NHS Health Careers → https://www.healthcareers.nhs.uk
- BACP → https://www.bacp.co.uk

---

## Liverpool Hope University links

When linking to Liverpool Hope's careers pages, use these URLs and open in a new tab:

- Main careers page → https://www.hope.ac.uk/careers/
- Part-time work → https://www.hope.ac.uk/careers/part-timework/
- Campus events → https://www.hope.ac.uk/careers/campusevents/
- Careers advice → https://www.hope.ac.uk/careers/careersadvice/
- Graduates and alumni → https://www.hope.ac.uk/careers/graduatesandalumni/
- Placement year → https://www.hope.ac.uk/careers/placementyear/
- Reach your full potential → https://www.hope.ac.uk/careers/reachyourfullpotential/
- Service and Leadership Award → https://www.hope.ac.uk/careers/serviceandleadershipaward/
- Student Futures Internship → https://www.hope.ac.uk/careers/studentfuturesinternship/

---

## Alumni photo placeholders

Alumni cards have a circular photo placeholder positioned at the top-right of the dark card header. To replace with a real photo, swap the placeholder div for:

```html
<img src="firstname-lastname.jpg" alt="Full Name">
```

inside the `.alumni-avatar` div. Upload the photo file to GitHub in the same folder as the HTML files.

---

## Design system

- **Primary navy:** `#1a3a5c` (headers, nav, hero sections)
- **Hero gradient:** `linear-gradient(135deg, #1a3a5c 0%, #1a4a6a 100%)`
- **Footer background:** `#142845`
- **Accent teal:** `#0891B2`
- **Fonts:** System fonts (`-apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif`) on all pages except the homepage

---

## No emojis

Do not add emoji characters to any HTML file.

---

## Contacts

- Gideon Salter (salterg@hope.ac.uk) — Academic Employability Lead
- Ali Wood (wooda@hope.ac.uk) — Careers Adviser
- Melissa Grindon (grinm@hope.ac.uk) — Employer Engagement Officer

---

## How to make edits and update the live site

1. Download the relevant HTML file(s) from GitHub (green Code → Download ZIP, or click the file → download icon)
2. Open a new AI session and paste this brief as the first message
3. Upload the file(s) and describe the change
4. Download the updated file from the AI
5. **Update the Last updated date in the footer of any changed files**
6. Go to the GitHub repository
7. Click Add file → Upload files
8. Drag in the updated file(s) — including logo.png if it is not already there
9. Click Commit changes
10. The live site updates within about 60 seconds

---

*Psychology Careers Hub — Liverpool Hope University, School of Psychology*
*Built as part of a psychology employability internship, May–June 2026*
*Supervised by Professor Caroline Wakefield*
*Built by David Perkins, Aimee Dutton and Jackson Gray*

---

## Your role as an AI editor

Your role is to modify an existing website while preserving its overall structure, navigation, design language and writing style. Prefer editing existing content over rewriting pages. Do not redesign pages or change the layout unless specifically instructed to do so.

---

## Editorial philosophy

The purpose of this website is not simply to list psychology careers.

Its purpose is to help psychology students:

- Understand the breadth of careers available to psychology graduates — far beyond the clinical route
- Understand why psychology graduates are well suited to those careers, in terms of the specific knowledge and skills their degree develops
- Understand what they can do during their degree to become competitive applicants

The site's central argument is that there is a significant gap between student awareness and the actual range of psychology-relevant careers available. The evidence section on the homepage and the Graduate Outcomes page make this argument explicitly.

When making edits, preserve this educational philosophy. Every page should answer: what is this career, why is psychology relevant, and what can students do now?

---

## Editing principles

When making any edit to this website:

- Preserve the existing design — do not change colours, fonts, layouts or card structures unless asked
- Preserve the navigation — do not change the nav bar order, link text or dropdown structure
- Preserve the writing style — clear, direct, student-facing language without jargon
- Do not invent statistics — all numerical claims should come from cited sources (Nuffield Trust, Luminate/Prospects, PwC AI Jobs Barometer)
- Do not fabricate employer examples — only use real, named organisations
- Keep writing concise — students will skim read
- Maintain UK English spelling throughout (organisation not organization, behaviour not behavior)
- Always update the "Last updated" date in the footer of any file you change

---

## What NOT to do

- Do not redesign pages or change the visual layout
- Do not change the navigation bar order or link wording
- Do not add emoji characters anywhere
- Do not invent statistics, salary figures or employer examples
- Do not remove citations or verified statistics and replace them with your own
- Do not rewrite pages from scratch when only a small edit is needed
- Do not change the university header or footer structure
- Do not alter the colour scheme (primary navy #1a3a5c, hero gradient linear-gradient(135deg, #1a3a5c 0%, #1a4a6a 100%))
- Do not add external links without checking they are real, working URLs
- Do not assume a page's content is complete — always upload the existing HTML file before editing

---

*Psychology Careers Hub — Liverpool Hope University, School of Psychology*
*Built as part of a psychology employability internship, May–June 2026*
*Supervised by Professor Caroline Wakefield*
*Built by David Perkins, Aimee Dutton and Jackson Gray*
