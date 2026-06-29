# How to Edit This Website Using an AI Assistant

**Psychology Careers Hub — Liverpool Hope University**

This guide explains how to use an AI assistant (Claude, ChatGPT, or similar) to make changes to this website. No coding knowledge is required. The AI does the technical work — you describe what you want and review the result.

---

## Overview

This website is a set of HTML files stored in a GitHub repository. To edit the site:

1. Download the file(s) you want to change from GitHub
2. Open an AI chat session (Claude or ChatGPT)
3. Paste the project brief (see below) as your first message
4. Upload the file(s) to the AI chat
5. Describe the change you want
6. Download the updated file from the AI
7. Upload it back to GitHub
8. The live site updates automatically within about 60 seconds

That is it. The AI handles all the HTML — you just describe what you want in plain English.

**Important: Always update the "Last updated" date in the footer** whenever you make any changes and upload new files. The footer appears at the bottom of every HTML file and contains the text "Last updated: June 2026." Change the month and year to reflect when you made the update.

---

## Step 1 — Download files from GitHub

Go to the repository (ask your administrator for the URL).

**To download a single file:**
- Click the file name (e.g. `alumni.html`)
- Click the download icon in the top right, or click **Raw** then save the page (Ctrl+S / Cmd+S)

**To download everything at once:**
- Click the green **Code** button
- Click **Download ZIP**
- Unzip the folder on your computer

Always work from the latest version — download fresh from GitHub before starting any editing session.

---

## Step 2 — Start an AI session and paste the project brief

Open Claude (claude.ai) or ChatGPT (chat.openai.com).

**Paste the following as your very first message** before uploading any files:

---

*Copy everything between the dashed lines and paste it as your first message:*

---
You are helping to edit a website called the Psychology Careers Hub, built for Liverpool Hope University's School of Psychology. Here is everything you need to know about the project:

**What it is:** A web resource for psychology students covering 11 career pathway areas. The site argues that a psychology degree opens more career doors than most students realise.

**The files:** 19 files total — index.html (homepage), alumni.html, employer-trends.html (Graduate Outcomes), roadmap.html (Build Your Employability), logo.png, and one file per career pathway: poc.html, research-data-evaluation.html, education.html, marketing-consumer-behavioural.html, behavioural-science.html, public-services-policy-justice.html, charity-third-sector.html, sport-exercise.html, forensic-legal.html, digital-technology-hcd.html, mental-health.html.

**Nav bar order (identical across all pages):** Psychology Careers Hub — Graduate Outcomes — Career Pathways ▾ (dropdown with 11 theme pages) — Build Your Employability — Alumni

**Critical nav bar rule:** Every file contains an identical navigation bar linking to all other files. If a new page is ever added, the nav bar in ALL other HTML files must also be updated. Always flag this if a new page is being created.

**University header:** Every page has a university header above the nav bar with the Liverpool Hope University logo (logo.png) and "Liverpool Hope University / School of Psychology" text. The logo file must always be in the same folder as the HTML files.

**Footer:** Every page has a slim footer at the bottom: "This resource was developed as part of a psychology employability internship project at Liverpool Hope University, School of Psychology. Last updated: [DATE]. © Liverpool Hope University 2026. Built by David Perkins, Aimee Dutton and Jackson Gray." Always update the Last updated date when making changes.

**Professional body links:** All org-name divs must contain a hyperlink to the organisation's website, opening in a new tab (target="_blank" rel="noopener"). Never leave an org-name as plain text.

**No emojis:** Do not add emoji characters to any file.

**Colours:** Primary navy #1a3a5c, accent teal #0891B2, gradient hero: linear-gradient(135deg, #1a3a5c 0%, #1a4a6a 100%). All pages use system fonts.

**Alumni photo placeholders:** Cards have circular photo placeholders positioned at the top-right of the card header. To add a real photo, replace the placeholder div with: `<img src="filename.jpg" alt="Person Name">` inside the `.alumni-avatar` div. Upload the photo file to GitHub in the same folder as the HTML files.

**Contacts:**
- Gideon Salter (salterg@hope.ac.uk) — Academic Employability Lead
- Ali Wood (wooda@hope.ac.uk) — Careers Adviser
- Melissa Grindon (grinm@hope.ac.uk) — Employer Engagement Officer

I will now upload the file(s) I want to edit.
---

---

## Step 3 — Upload the file and describe your change

After pasting the brief, upload the HTML file you want to edit and describe what you want changed in plain English. Examples:

- *"Update the alumni profile for Joshua Walker — his job title is now Marketing Manager at Unilever. Here is his profile text: [paste text]"*
- *"Add a new role card to the Education page for 'Educational Welfare Officer' — graduate entry, description is [paste description]"*
- *"Change the contact email for Ali Wood to [new email]"*
- *"Add a 'Last updated: July 2026' date to the footer — replacing June 2026"*

---

## Step 4 — Review the change

Before uploading to GitHub, open the downloaded HTML file in your browser (double-click it) and check:

- Does the change look right?
- Does the navigation bar still work?
- Is the Last updated date correct?

If something looks wrong, go back to the AI and describe what needs fixing.

---

## Step 5 — Upload back to GitHub

1. Go to the GitHub repository
2. Click **Add file → Upload files**
3. Drag in the updated file(s) — including `logo.png` if it is not already there
4. Click **Commit changes**
5. Wait about 60 seconds, then check the live site

---

## Common tasks

### Updating an alumni profile
Upload `alumni.html`. Ask the AI to update the name, role, degree, graduation year, profile text, or advice section for the relevant person.

### Adding an alumni photo
1. Rename the photo file to something simple (e.g. `alex-smith.jpg`)
2. Upload the photo to the GitHub repository (same folder as HTML files)
3. Upload `alumni.html` to the AI and ask it to replace the placeholder for that person with `<img src="alex-smith.jpg" alt="Name">`
4. Upload the updated `alumni.html` to GitHub

### Adding a new role to a career pathway page
Upload the relevant theme file. Tell the AI the role name, description, whether it is graduate entry or requires further training, and any other details.

### Adding an external link
Upload the relevant file. Tell the AI which text should be linked and what the URL is.

### Updating the Last updated date
Upload any file that needs updating. Ask the AI to change "Last updated: [old date]" to "Last updated: [new date]" in the footer. Do this for all files you have changed.

### Updating contact details
Upload any file where the contact details appear. The contacts (Gideon Salter, Ali Wood, Melissa Grindon) appear in the footer of every page and in the contact section of index.html.

### Adding a new professional organisation
Upload the relevant theme file. Tell the AI the organisation name and website URL. It will add it as a linked org card.

### Adding a new page
This is the most complex task. Tell the AI:
- What the new page is called
- What filename to use (e.g. `new-topic.html`)
- What content it should have

The AI will create the new HTML file AND provide updated versions of all other files with the new page added to their navigation bars. All updated files need to be uploaded to GitHub.

---

## What the AI can do

- Edit any text on any page
- Add, remove or modify cards, sections, links and lists
- Create new pages in the same style as existing ones
- Update the Last updated date in footers
- Add or remove hyperlinks
- Update professional organisation links
- Swap photo placeholders for real images
- Fix broken layouts or formatting issues

## What the AI cannot do

- Access GitHub directly — you need to upload and download files manually
- See the live site — it works from the files you upload
- Automatically update all files when one changes — you must do this yourself for nav bar changes

---

## Tips for working with AI assistants

**Be specific.** "Update the alumni profile for Joshua Walker" is better than "update an alumni profile." Include the exact text you want where relevant.

**One file at a time.** Upload and edit one file per session where possible. This reduces the chance of errors.

**Always review before uploading.** Open the HTML file in your browser before pushing to GitHub. It takes 30 seconds and catches most problems.

**Always update the Last updated date.** Any time you make changes and upload files, update the date in the footer of those files.

**Use the project brief every time.** Always paste the project brief at the start of a new AI session. Without it, the AI does not know the project structure and may make inconsistent changes.

**Keep a backup.** GitHub keeps the history of all changes — you can always revert to an older version if something goes wrong. Click the file, then **History** to see previous versions.

---

## File naming conventions

- Use lowercase letters and hyphens only (e.g. `new-page.html`)
- No spaces, capitals, or special characters in filenames
- Photos: use the person's name in lowercase with hyphens (e.g. `alex-smith.jpg`, `caroline-knowles.jpg`)

---

## Getting help

If you are unsure about a change or something does not look right, contact whoever maintains this project or raise it with the team before uploading to the live site.

---

*Psychology Careers Hub — Liverpool Hope University, School of Psychology*
*Built as part of a psychology employability internship, May–June 2026*
*Supervised by Professor Caroline Wakefield*
*Built by David Perkins, Aimee Dutton and Jackson Gray*
