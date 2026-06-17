# How to Edit This Website Using an AI Assistant

**Psychology Careers Hub — Liverpool Hope University**

This guide explains how to use an AI assistant (Claude, ChatGPT, or similar) to make changes to this website. No coding knowledge is required. The AI does the technical work — you describe what you want and review the result.

---

## Overview

This website is a set of HTML files stored in this GitHub repository. To edit the site:

1. Download the file(s) you want to change from GitHub
2. Open an AI chat session (Claude or ChatGPT)
3. Paste the project brief (see below) as your first message
4. Upload the file(s) to the AI chat
5. Describe the change you want
6. Download the updated file from the AI
7. Upload it back to GitHub
8. The live site updates automatically within about 60 seconds

That's it. The AI handles all the HTML — you just describe what you want in plain English.

---

## Step 1 — Download files from GitHub

Go to the repository:
**https://github.com/25000774-lab/psychology-careers-hub**

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

**Paste the following as your very first message** before uploading any files. This gives the AI the context it needs to work correctly:

---

*Copy everything between the dashed lines and paste it as your first message:*

---
You are helping to edit a website called the Psychology Careers Hub, built for Liverpool Hope University's School of Psychology. Here is everything you need to know about the project:

**What it is:** A web resource for psychology students covering 11 career theme areas. Hosted at https://25000774-lab.github.io/psychology-careers-hub/

**The files:** 16 HTML files — index.html (homepage), alumni.html, employer-trends.html, roadmap.html, and one file per career theme: poc.html, research-data-evaluation.html, education.html, marketing-consumer-behavioural.html, behavioural-science.html, public-services-policy-justice.html, charity-third-sector.html, sport-exercise.html, forensic-legal.html, digital-technology-hcd.html, mental-health.html.

**Critical nav bar rule:** Every file contains an identical navigation bar linking to all other files. If a new page is ever added, the nav bar in ALL other HTML files must also be updated. Always flag this if a new page is being created.

**Professional body links:** All org-name divs must contain a hyperlink to the organisation's website, opening in a new tab (target="_blank" rel="noopener"). Never leave an org-name as plain text.

**No emojis:** Do not add emoji characters to any file.

**Colours:** Primary navy #1E3A5F, accent teal #0891B2, light periwinkle #EEF2FF. The homepage (index.html) uses CSS custom properties (--navy, --teal etc). Theme pages use hex values directly.

**Fonts:** Plus Jakarta Sans (display) and Inter (body) on the homepage. Theme pages use system fonts.

**Alumni photo placeholders:** Cards have circular photo placeholders positioned half above the card header. To add a real photo, replace the placeholder div with: `<img src="filename.jpg" alt="Person Name">` inside the `.alumni-avatar` div. Upload the photo file to GitHub in the same folder as the HTML files.

**Contacts:** Ali Wood (wooda@hope.ac.uk) — Careers Adviser. Melissa Grindon (grinm@hope.ac.uk) — Employer Engagement Officer.

I will now upload the file(s) I want to edit.
---

---

## Step 3 — Upload the file and describe your change

After pasting the brief, upload the HTML file you want to edit and describe what you want changed in plain English. Examples:

- *"Update the alumni profile for Joshua Walker — his job title is now Marketing Manager at Unilever. Here is his profile text: [paste text]"*
- *"Add a new role card to the Education page for 'Educational Welfare Officer' — graduate entry, description is [paste description], employers are local authorities and schools"*
- *"Add a link to the British Association for Counselling and Psychotherapy (https://www.bacp.co.uk) to the org-name div that says BACP on the mental health page"*
- *"Change the contact email for Ali Wood to [new email]"*
- *"Add a new section to the employer trends page about [topic]"*

Be as specific as possible. The AI will make the change and give you an updated HTML file to download.

---

## Step 4 — Review the change

Before uploading to GitHub, open the downloaded HTML file in your browser (double-click it) and check:

- Does the change look right?
- Does the navigation bar still work?
- Are there any obvious errors or broken layouts?

If something looks wrong, go back to the AI and describe what needs fixing. The AI can keep refining the file until it is correct.

---

## Step 5 — Upload back to GitHub

1. Go to **https://github.com/25000774-lab/psychology-careers-hub**
2. Click **Add file → Upload files**
3. Drag in the updated file(s)
4. Click **Commit changes**
5. Wait about 60 seconds, then check the live site

If you updated multiple files, upload them all at once in the same commit.

---

## Common tasks

### Updating an alumni profile
Upload `alumni.html`. Ask the AI to update the name, role, degree, graduation year, profile text, or advice section for the relevant person.

### Adding an alumni photo
1. Rename the photo file to something simple (e.g. `alex-smith.jpg`)
2. Upload the photo to the GitHub repository (same folder as HTML files)
3. Upload `alumni.html` to the AI and ask it to replace the placeholder for that person with `<img src="alex-smith.jpg" alt="Name">`
4. Upload the updated `alumni.html` to GitHub

### Adding a new role to a theme page
Upload the relevant theme file. Tell the AI the role name, description, whether it is graduate entry or requires further training, and any other details. The AI will add a new role card in the correct format.

### Adding an external link
Upload the relevant file. Tell the AI which text should be linked and what the URL is.

### Updating contact details
Upload `index.html` and describe the change. Contact details also appear in the footer of `index.html`.

### Adding a new professional organisation
Upload the relevant theme file. Tell the AI the organisation name and website URL. It will add it as a linked org card.

### Adding a new page
This is the most complex task. Tell the AI:
- What the new page is called
- What filename to use (e.g. `new-topic.html`)
- What content it should have

The AI will create the new HTML file AND provide updated versions of all 15 other files with the new page added to their navigation bars. All updated files need to be uploaded to GitHub.

### Updating the employer trends chart placeholder
Upload `employer-trends.html`. Once you have confirmed employment trend data, describe the data to the AI and ask it to build a proper chart to replace the placeholder.

---

## What the AI can do

- Edit any text on any page
- Add, remove or modify cards, sections, links and lists
- Create new pages in the same style as existing ones
- Add or remove hyperlinks
- Update professional organisation links
- Swap photo placeholders for real images
- Maintain consistent formatting, colours and nav bars across all files
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

**If something breaks**, ask the AI what went wrong and to fix it. Paste the broken section back if needed.

**Keep a backup.** GitHub keeps the history of all changes — you can always revert to an older version if something goes wrong. Click the file, then **History** to see previous versions.

**Use the project brief every time.** Always paste the project brief at the start of a new AI session. Without it, the AI does not know the project structure and may make inconsistent changes.

---

## File naming conventions

- Use lowercase letters and hyphens only (e.g. `new-page.html`)
- No spaces, capitals, or special characters in filenames
- Photos: use the person's name in lowercase with hyphens (e.g. `alex-smith.jpg`, `jasmine-perceval.jpg`)

---

## Getting help

If you are unsure about a change or something does not look right, contact whoever maintains this project or raise it in the team before uploading to the live site.

---

*Psychology Careers Hub — Liverpool Hope University, School of Psychology*
*Built as part of a psychology employability internship, May–June 2026*
*Supervised by Professor Caroline Wakefield*
