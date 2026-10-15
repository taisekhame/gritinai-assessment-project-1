# Project 1: CV / Resume Page

**GritinAI Web Development Programme**
Part 1 — Full HTML Project

---

## Overview

In this project you will build a personal CV/Resume page using HTML as the primary skill, with a small amount of CSS for global and base styling. The goal is to produce a well-structured, readable web page that presents your personal information in a professional format.

By the end of this project you will have:

- A deployed, publicly accessible CV page
- A clean HTML structure using semantic elements correctly
- A styled page using CSS variables, a Google Font, and Font Awesome icons
- A project submitted and pushed to GitHub

---

## What Is Provided

The starter files in this repository are:

| File | Purpose |
|---|---|
| `index.html` | The HTML structure with comments guiding each section |
| `styles.css` | Global and reset styles only. You write all section styles. |
| `images/profile-photo.webp` | Placeholder profile photo. Replace with your own. |
| `images/reference-photo.webp` | Placeholder reference photo. Replace with your own. |

---

## Your Tasks

Work through the file top to bottom. Every section has a comment block explaining what to do.

### 1. Update `index.html`

Replace all placeholder content with your real information:

- Your name in the `<title>` tag and the navbar
- Your GitHub, LinkedIn, and email links
- Your profile photo (save your own image into the `images/` folder)
- Your bio in the Profile section
- Your real skills in the Skills section (add or remove skill cells as needed)
- Your education history in the Education section (most recent first)
- Your work or volunteer experience in the Experience section (most recent first)
- A reference name, title, and quote in the Reference section
- Your contact details in the Contact section

### 2. Add skill logos or icons

For each skill in the Skills section, choose one of the following:

- Download a logo image and save it in the `images/` folder, then use `<img>` in your `.cell`
- Use a Font Awesome icon (`<i class="fa-brands fa-...">`) instead of an image

Font Awesome brand icons: https://fontawesome.com/icons?d=gallery&s=brands

### 3. Choose your Google Font

The starter uses Poppins. You may keep it or choose a different font:

1. Go to https://fonts.google.com
2. Choose a font and click "Get font"
3. Copy the `<link>` tags and replace the existing ones in the `<head>` of `index.html`
4. Update the `font-family` value in `styles.css` to match your chosen font

### 4. Write your CSS in `styles.css`

The global styles are already written. Your job is to write styles for each section below the `YOUR STYLES START HERE` comment. Style the following:

- `nav` — navbar layout and link styles
- `.profile-section` — layout for the photo and text side by side
- `.skills-section` — layout and appearance of the skill cells
- `.education-section` — layout and spacing for education entries
- `.experience-section` — layout and spacing for experience entries
- `.reference-section` — layout for the photo and quote
- `.contact-section` — layout for the contact details and form

---

## Getting Started

### Step 1. Accept the invitation

You will receive an email or GitHub notification inviting you as a collaborator on this repository. Accept the invitation.

### Step 2. Clone the repository

Open your terminal and run:

```bash
git clone https://github.com/YOUR-REPO-URL.git
cd project1-cv
```

### Step 3. Create your own branch

Replace `yourname` with your actual first name:

```bash
git checkout -b yourname
```

### Step 4. Open the project

Open the project folder in VS Code:

```bash
code .
```

Install the **Live Server** extension in VS Code if you have not already. Right-click `index.html` and select "Open with Live Server" to preview your page in the browser as you work.

### Step 5. Work on the project

Edit `index.html` and `styles.css`. Save your changes frequently. The browser will refresh automatically with Live Server running.

### Step 6. Commit and push your work

When you are done (or at the end of each session), run:

```bash
git add .
git commit -m "Add my CV content and styles"
git push origin yourname
```

Push to your own branch, not to `main`.

---

## Project Requirements

Your submission must include all of the following:

- [ ] Your real name, bio, and contact information
- [ ] Your own profile photo (not the placeholder)
- [ ] At least 3 skills displayed with icons or logos
- [ ] At least 1 education entry with accurate details
- [ ] At least 1 experience entry (work, volunteer, or personal project)
- [ ] A reference entry or "Available on request" text
- [ ] A working contact form (fields do not need to submit — that requires a backend)
- [ ] A Google Font applied throughout the page
- [ ] Font Awesome icons used in at least the navbar and the quick-links
- [ ] CSS written for every section in `styles.css`
- [ ] All work pushed to your branch on GitHub

---

## Resources

| Resource | Link |
|---|---|
| Google Fonts | https://fonts.google.com |
| Font Awesome Icons | https://fontawesome.com |
| Font Awesome CDN | https://cdnjs.com/libraries/font-awesome |
| MDN HTML Reference | https://developer.mozilla.org/en-US/docs/Web/HTML/Element |
| MDN CSS Reference | https://developer.mozilla.org/en-US/docs/Web/CSS/Reference |
| CSS Tricks Flexbox Guide | https://css-tricks.com/snippets/css/a-guide-to-flexbox |
| VS Code Download | https://code.visualstudio.com |
| Live Server Extension | https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer |

---

## Submission

Push your completed work to your branch on this repository before the deadline given by your instructor. Your instructor will review your branch directly on GitHub.

If you have any questions, reach out on the class group or contact your instructor.
