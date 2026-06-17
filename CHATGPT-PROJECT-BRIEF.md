# Psychology Careers Hub — Project Brief for AI Editing Sessions

Paste this document at the start of any ChatGPT session before uploading HTML files to edit.

---

## What this project is

A web resource for psychology students at Liverpool Hope University, School of Psychology. It covers 11 career theme areas, helping students understand what careers are available with a psychology degree, why they are well suited to them, and what they can do now to prepare.

The site is hosted on GitHub Pages at:
https://25000774-lab.github.io/psychology-careers-hub/

The GitHub repository is at:
https://github.com/25000774-lab/psychology-careers-hub

---

## The files

The site is 16 HTML files and a README. All files must be kept in the same folder for navigation links to work.

| File | What it is |
|------|------------|
| index.html | Homepage — the main hub page students land on first |
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
| alumni.html | Alumni profiles |
| employer-trends.html | Employer trends and practical support (LinkedIn, CV, Volunteering) |
| roadmap.html | Employability roadmap — skills mapping table |
| README.md | Documentation for maintainers |

---

## The navigation bar

Every HTML file contains an identical sticky navigation bar at the top. It looks like this:

```html
<div class="site-nav">
  <div class="site-nav-inner">
    <a class="site-nav-home" href="index.html">Psychology <span>Careers Hub</span></a>
    <a class="site-nav-link" href="roadmap.html">Roadmap</a>
    <a class="site-nav-link" href="employer-trends.html">Employer Trends</a>
    <a class="site-nav-link" href="alumni.html">Alumni</a>
    <div class="site-nav-dropdown">
      <span class="site-nav-link">Themes &#9660;</span>
      <div class="site-nav-menu">
        <a href="poc.html">People, Organisations &amp; Consultancy</a>
        <a href="research-data-evaluation.html">Research, Data &amp; Evaluation</a>
        <a href="education.html">Education</a>
        <a href="marketing-consumer-behavioural.html">Marketing, Consumer &amp; Behavioural Insight</a>
        <a href="behavioural-science.html">Behavioural Science &amp; Behaviour Change</a>
        <a href="public-services-policy-justice.html">Public Services, Policy &amp; Justice</a>
        <a href="charity-third-sector.html">Charity &amp; Third Sector</a>
        <a href="sport-exercise.html">Sport &amp; Exercise</a>
        <a href="forensic-legal.html">Forensic &amp; Legal Psychology</a>
        <a href="digital-technology-hcd.html">Digital, Technology &amp; HCD</a>
        <a href="mental-health.html">Mental Health</a>
      </div>
    </div>
  </div>
</div>
```

CRITICAL RULE: If a new page is added to the site, the nav bar in ALL 15 other HTML files must be updated to include it. Failing to do this creates broken navigation. Always update all files when adding a page.

---

## Professional body links

Every professional organisation mentioned in an org-name div is linked to its official website. The format is:

```html
<div class="org-name"><a href="https://www.cipd.org.uk" target="_blank" rel="noopener">CIPD</a></div>
```

All org links open in a new tab (target="_blank" rel="noopener"). When adding a new professional body, always include a link. Do not leave org-name divs as plain text.

Key organisation URLs for reference:
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
- BABCP → https://www.babcp.com

---

## Liverpool Hope University links

When linking to Liverpool Hope's careers pages, always use these exact URLs and open in a new tab:

- Main careers page → https://www.hope.ac.uk/careers/
- Part-time work → https://www.hope.ac.uk/careers/part-timework/
- Campus events → https://www.hope.ac.uk/careers/campusevents/
- Careers advice → https://www.hope.ac.uk/careers/careersadvice/
- Get into teaching → https://www.hope.ac.uk/careers/getintoteaching/
- Graduates and alumni → https://www.hope.ac.uk/careers/graduatesandalumni/
- Placement year → https://www.hope.ac.uk/careers/placementyear/
- Reach your full potential → https://www.hope.ac.uk/careers/reachyourfullpotential/
- Service and Leadership Award → https://www.hope.ac.uk/careers/serviceandleadershipaward/
- Student Futures Internship → https://www.hope.ac.uk/careers/studentfuturesinternship/
- Student success stories → https://www.hope.ac.uk/careers/studentsuccessstories/

---

## Alumni photo placeholders

Alumni cards on alumni.html and the homepage (index.html) have circular photo placeholders that sit half above the card header. The placeholder HTML looks like this:

```html
<div class="alumni-avatar-wrap">
  <div class="alumni-avatar">
    <div class="alumni-avatar-placeholder">
      <svg ...person icon...></svg>
      <span style="font-size:9px;color:#1a5fa8;font-weight:600;letter-spacing:0.05em;">PHOTO</span>
    </div>
  </div>
</div>
```

To replace a placeholder with a real photo, swap the inner div for an img tag:

```html
<div class="alumni-avatar-wrap">
  <div class="alumni-avatar">
    <img src="firstname-lastname.jpg" alt="Full Name">
  </div>
</div>
```

Photo files should be uploaded to the GitHub repository root alongside the HTML files. The src value is just the filename (e.g. "alex-smith.jpg").

---

## Design system

The homepage (index.html) uses a design system with CSS custom properties. Key colours:

- --navy: #1E3A5F (primary brand, used for headers and nav)
- --navy-deep: #142845 (nav bar background)
- --teal: #0891B2 (primary accent, buttons and highlights)
- --teal-mid: #38BDF8 (lighter teal for labels on dark backgrounds)
- --periwinkle: #EEF2FF (light section backgrounds)
- --indigo: #4F46E5 (badges)
- --border: #E2E8F0

Fonts: Plus Jakarta Sans (display/headings) and Inter (body) — both loaded from Google Fonts.

The theme pages (poc.html, education.html etc.) use a simpler flat CSS system with the same navy colour but without the custom properties. Do not add CSS custom properties to theme pages — use hex values directly.

---

## No emojis

Emojis have been removed from all files. Do not add emoji characters to any HTML file. Use plain text labels instead.

---

## Contacts

- Careers Adviser: Ali Wood — wooda@hope.ac.uk
- Employer Engagement Officer: Melissa Grindon — grinm@hope.ac.uk

---

## How to make edits and update the live site

1. Download the relevant HTML file(s) from GitHub or from whoever holds the latest version
2. Upload to ChatGPT and describe the change needed
3. Download the updated file(s)
4. Go to https://github.com/25000774-lab/psychology-careers-hub
5. Click Add file → Upload files
6. Drag in the updated file(s) — GitHub will overwrite the old versions automatically
7. Click Commit changes
8. The live site updates within about 60 seconds

If adding a brand new page: also update the nav bar in all other HTML files and upload those too.

---

*Psychology Careers Hub — Liverpool Hope University, School of Psychology*
*Built as part of a psychology employability internship, May–June 2026*
*Supervised by Professor Caroline Wakefield*
