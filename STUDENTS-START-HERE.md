# Welcome to Your CMST 4714 Portfolio

This is your professional portfolio for **CMST 4714: The Human Communicator in an Era
of AI** at Virginia Tech. By the end of the semester, this site will document your
intellectual work, your professional presence, and your developing argument about what
human communicators bring to an AI-shaped world.

---

## Before you do anything else: read this

This template comes pre-filled with a fictional student named **Robin Hokie**. Robin's
content is there to show you what a finished portfolio looks like — the structure, the
voice, the level of detail. **You must replace all of Robin's content with your own.**

Do not edit around Robin's text. Delete it and start fresh. Submitting Robin Hokie's
About page with your name at the top is not a portfolio. It is a citation violation.

---

## Getting your site live (20–30 minutes)

### 1. Enable GitHub Pages

1. Go to your repo → **Settings** → **Pages** (left sidebar)
2. Under "Build and deployment," set Source to **GitHub Actions**
3. Save

Your site will be published at `https://yourusername.github.io/cmst4714-portfolio`
(or whatever you named your repo). It may take 2–5 minutes for the first build.

### 2. Check your build status

Go to the **Actions** tab in your repo. You should see a workflow run. Green checkmark
= your site is live. Yellow circle = still building. Red X = something went wrong.

**If you see a red X:** Copy the error message from the failed run and bring it to
class or paste it into HokieAI with the prompt: *"I'm building a Jekyll GitHub Pages
site using the academicpages theme and got this error: [paste error]. What's wrong and
how do I fix it?"* Most errors are a single character off in a YAML file.

### 3. Visit your site

Go to `https://yourusername.github.io/your-repo-name`. You should see Robin Hokie's
portfolio. Now start replacing it.

---

## Editing your content (no terminal required)

All editing can be done through the **GitHub web interface** or **GitHub Desktop**.
You do not need to run Jekyll locally.

### Files you will edit

| File | What it controls |
|------|-----------------|
| `_pages/about.md` | Your About/Bio page (the homepage) |
| `_pages/cv.md` | Your CV/Resume page |
| `_portfolio/project-1.md` | Portfolio project 1 |
| `_portfolio/project-2.md` | Portfolio project 2 |
| `_portfolio/project-3.md` | Portfolio project 3 |
| `_config.yml` | Your name, email, bio, social links |

### Editing `_config.yml`

This file controls your site-wide identity. Find the block that looks like this and
fill in your own information:

```yaml
# ============================================================
# EDIT THIS BLOCK — your name, bio, and contact info
# Do not change anything outside this block unless you know
# what you are doing. Bad YAML will break your site.
# ============================================================
author:
  name    : "Your Full Name"
  avatar  : "/images/bio-photo.jpg"
  bio     : "Senior, School of Communication, Virginia Tech."
  location: "Blacksburg, VA"
  email   : "youremail@vt.edu"
  links:
    - label: "GitHub"
      icon: "fab fa-fw fa-github"
      url: "https://github.com/yourusername"
    - label: "LinkedIn"
      icon: "fab fa-fw fa-linkedin"
      url: "https://linkedin.com/in/yourprofile"
# ============================================================
# END EDIT ZONE
# ============================================================
```

**Important:** YAML is whitespace-sensitive. Do not change the indentation. Only edit
the values inside the quotation marks.

### Adding a photo

Replace the file at `images/bio-photo.jpg` with your own photo. Keep the filename
exactly the same, or update the `avatar` line in `_config.yml` to match your filename.

---

## Markdown basics

All content files use Markdown. You do not need to know HTML.

```markdown
# Heading 1
## Heading 2

Regular paragraph text.

**Bold text**   *Italic text*

- Bullet item
- Another item

[Link text](https://example.com)
```

A short in-class Markdown tutorial runs in Week 2. Come with your repo already set up.

---

## Keeping a real revision history

The GitHub revision history of your repository is part of your grade. Make commits as
you work — not one large upload at the end of each milestone. A commit after every
meaningful editing session is the right pace. Your commit messages should be honest
about what you changed: *"Add about page draft"* is better than *"update."*

---

## Getting help

- **HokieAI:** Paste your error message or your Markdown draft and ask for help.
  HokieAI is available to all VT students at [hokieai.vt.edu] beginning August 2026.
- **GitHub Docs:** `docs.github.com` has clear walkthroughs for everything this
  template uses.
- **In class:** Weeks 1–3 include tutorial modules specifically for this setup.
- **Office hours:** LAHSB 013. Come with your laptop and your specific question.

---

*CMST 4714 — School of Communication — Virginia Tech — Fall 2026*
