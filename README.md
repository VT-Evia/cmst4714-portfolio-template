# Welcome to Your CMST 4714 Portfolio

This is your professional portfolio for **CMST 4714: The Human Communicator in an Era
of AI** at Virginia Tech. By the end of the semester, this site will document your
intellectual work, your professional presence, and your developing argument about what
human communicators bring to an AI-shaped world.

---

## Before you do anything else: read this

This template comes pre-filled with a fictional student named **Robin Hokie**. Robin's
content is there to show you what a finished portfolio looks like — the structure, the
voice, the level of detail. Note that Robin's portfolio isn't just CMST 4714 work: it
spans all four years of the Communication major, from a freshman public speaking class
through this semester's capstone course. **Your own portfolio should do the same** —
include work from other courses, not only CMST 4714 — and you **must replace all of
Robin's content with your own.**

Do not edit around Robin's text. Delete it and start fresh. 

---

## Getting your site live (20–30 minutes)

### 1. Create your repo — name it `yourusername.github.io`

This portfolio will be your **main GitHub Pages website**, so it has to live in a repo
named exactly after your GitHub username:

```
yourusername.github.io
```

If your GitHub username is `hokiebird22`, your repo must be named
`hokiebird22.github.io`, and your site will live at `https://hokiebird22.github.io`.
Any other name (for example `cmst4714-portfolio`) puts your site at a longer
sub-address instead of your main one.

1. At the top of this template's page on GitHub, click **Use this template** →
   **Create a new repository**.
2. **Owner:** your personal account.
3. **Repository name:** `yourusername.github.io` — all lowercase, spelled exactly like
   your username.
4. **Visibility:** Public.
5. Click **Create repository**.

### 2. Point the site at your new address

Open `_config.yml` in your new repo (see "Working in Codespaces" below, or click the
file and then the pencil icon). At the top of the **EDIT THIS BLOCK** section, change
these three lines:

```yaml
url                      : "https://yourusername.github.io"
baseurl                  : ""
repository               : "yourusername/yourusername.github.io"
```

`baseurl` must be empty quotes (`""`). If you skip this step, your site will load
without its styling and images.

### 3. Enable GitHub Pages

1. Go to your repo → **Settings** → **Pages** (left sidebar)
2. Under "Build and deployment," set Source to **GitHub Actions**

That's it — GitHub saves the setting automatically. The first build takes 2–5 minutes.

### 4. Check your build status

Go to the **Actions** tab in your repo. You should see a workflow run. Green checkmark
= your site is live. Yellow circle = still building. Red X = something went wrong.

**If you see a red X:** Click the failed run, copy the error message, and paste it into
Copilot Chat (see below) or HokieAI with the prompt: *"I'm building a Jekyll GitHub
Pages site using the academicpages theme and got this error: [paste error]. What's
wrong and how do I fix it?"* Most errors are a single character off in a YAML file.

### 5. Visit your site

Go to `https://yourusername.github.io`. You should see Robin Hokie's portfolio. Now
start replacing it.

---

## Working in Codespaces

You already used **Codespaces** for your primer website, so this will feel familiar: a
full VS Code editor running in your browser, connected to your repo.

### Opening a codespace

1. Go to your repo on github.com and make sure you're signed in.
2. Click the green **Code** button → **Codespaces** tab → **Create codespace on main**.
3. The editor opens in a new tab. The first launch takes a minute or two.

Next time, reopen the **same** codespace from the **Code** → **Codespaces** list instead
of creating a new one. Every new codespace uses up more of your free allowance.

### Finding your way around

- **Explorer** (top icon in the left bar) — your files and folders. Click a file to
  open it.
- **Markdown preview** — with a `.md` file open, press `Ctrl+Shift+V`
  (Mac: `Cmd+Shift+V`) to see roughly how it will look. Formatting only — the full site
  look only appears after you commit and the site rebuilds.
- **Uploading files** (photos, PDFs) — drag them from your computer onto a folder in
  the Explorer, e.g. `images/` or `files/`.
- **Search** — `Ctrl+Shift+F` (Mac: `Cmd+Shift+F`) searches every file. Search for
  "Robin" to find content you still need to replace.

### Saving your work (committing)

Codespaces saves your files inside the codespace, but your edits are **not on GitHub —
and not on your live site — until you commit and push.**

1. Click the **Source Control** icon in the left bar (the branching-lines icon; a
   number shows how many files you changed).
2. Review your changes — click any file to see before/after.
3. Type a clear message in the box at the top, e.g. *"Replace Robin's About page with
   my bio."*
4. Click **Commit**, then **Sync Changes** (or use the arrow next to **Commit** and
   choose **Commit & Push**).
5. Wait 2–5 minutes, check the **Actions** tab, then refresh your site.

If you delete a codespace without pushing, those changes are gone for good.

### Managing your codespaces (and your free hours)

Codespaces is free up to a monthly limit of usage hours and storage. A codespace counts
against that limit while it is **running**, even if you have closed the browser tab,
until it times out on its own. Two habits keep you well under the limit:

**1. Set a short idle timeout.** Go to
[github.com/settings/codespaces](https://github.com/settings/codespaces):

- **Default idle timeout** — how many minutes of inactivity before a codespace stops
  itself. Set it to **30 minutes** or less.
- **Default retention period** — how many days a *stopped* codespace is kept before
  GitHub deletes it. A few days to a week is plenty, as long as you always push your
  work.

These settings apply to codespaces you create after changing them.

**2. Stop codespaces when you're done.** See every codespace you have, and whether it's
running, at [github.com/codespaces](https://github.com/codespaces). Click the **⋯** next
to any codespace and choose **Stop codespace** to stop it, or **Delete** to remove one
you no longer need (push first!).

**If GitHub warns you about usage:** go to
[github.com/codespaces](https://github.com/codespaces), stop anything that's running,
and delete extra codespaces so you keep just one for this repo. You can check how much
you've used at [github.com/settings/billing](https://github.com/settings/billing).

---

## Using the GitHub Copilot agent in Codespaces

Your GitHub Education student benefits include **GitHub Copilot**, which works inside
Codespaces. In **Agent** mode, Copilot can explain files, fix broken YAML, and make
edits to your files for you.

### Opening Copilot Chat

1. In your codespace, click the **Copilot / chat icon** in the top bar,
   or press `Ctrl+Alt+I` (Mac: `Cmd+Ctrl+I`).
2. If you don't see it: open **Extensions** (the four-squares icon), search
   **GitHub Copilot Chat**, and click **Install**. Sign in with your GitHub account if
   asked.
3. At the bottom of the chat panel, use the **mode picker** to choose how Copilot works:
   - **Ask** — answers questions, does not touch your files. Use this to learn.
   - **Agent** — Copilot edits files for you. Use this to make changes.

### Asking Copilot to make a change

1. **Give it the right file.** Open the file first, or type `#` in the chat box and
   pick the file (e.g. `#about.md`), so Copilot knows what you mean.
2. **Be specific.** Say what to change and what to leave alone:
   - *"In `_config.yml`, change the author name to Jordan Lee and the email to
     jlee@vt.edu. Don't change anything else."*
   - *"Create a new file in `_portfolio/` for my COMM 2034 research paper, using an
     existing `_portfolio/` file as a model. Term Spring 2025. Leave the
     body text as placeholder headings I'll fill in."*
   - *"The sidebar isn't showing my LinkedIn link. Look at `_config.yml` and tell me
     why."*
   - *"My Actions build failed with this error: [paste]. Fix it."*
3. **Review every change.** Copilot shows its edits highlighted in the file. Read them,
   then click **Keep** (accept) or **Undo** (reject) for each one.
4. **Commit.** Copilot's edits are just like yours — they aren't on GitHub until you
   commit and push from **Source Control**. Write the commit message yourself so it
   honestly describes what changed.

### Rules for using Copilot in this course

- **Copilot handles the code; you write the words.** Use it for YAML, Markdown
  formatting, layout, and fixing errors. Your bio, project reflections, and arguments
  must be your own writing, consistent with the course AI policy.
- **Check its work.** Copilot can be wrong or confidently change things you didn't ask
  about. If a change looks unfamiliar, choose **Undo** and ask it to explain first.
- **Keep commits small.** One change, one commit. If Copilot breaks something, you
  can see exactly which commit did it in your history.

---

## Editing your content

### Files you will edit

| File | What it controls |
|------|-----------------|
| `_pages/about.md` | Your About/Bio page (the homepage) |
| `_pages/cv.md` | Your CV/Resume page |
| `_portfolio/*.md` | One file per portfolio work sample (see below) |
| `_config.yml` | Your web address, name, email, bio, social links |
| `images/bio-photo.jpg` | Your sidebar photo |

### About the `_portfolio/` files

Robin's example portfolio has eight files in `_portfolio/`, one per work sample,
spanning freshman year through this semester's CMST 4714 projects. Each file's front
matter includes:

```yaml
course: "CMST 1016: Introduction to Public Speaking"
term: "Fall 2023"
date: 2023-10-12
```

The Portfolio page lists every entry in one list, **newest first**, based on `date`. You
do not need to keep exactly eight files or exactly Robin's courses — add, remove, or
rename files to match your own coursework, but keep at least one sample from CMST 4714
and, if you have them, samples from earlier courses so your portfolio reflects your
whole time at Virginia Tech, not just this semester.

### Adding images to a portfolio entry

Four of Robin's entries include a stock photo, each showing a different way to add an
image. Open these files to see the code (each one has a comment explaining it):

| File | Shows how to |
|------|--------------|
| `_portfolio/speech-attention-economy.md` | Add a basic image |
| `_portfolio/pr-campaign-plan.md` | Add an image with a caption |
| `_portfolio/organizational-comm-audit.md` | Add an image with a styled caption (HTML) |
| `_portfolio/intentio-algorithmi-presentation.md` | Make an image smaller and centered |

The basic format is:

```markdown
![Description of the image](address-of-the-image)
```

- **Your own image** (a screenshot, a slide, a photo): upload it to the `images/`
  folder, then use `/images/your-file-name.jpg` as the address.
- **An image from the web:** use its full address, starting with `https://`. Only use
  images you have the right to use, such as free stock photos from
  [Unsplash](https://unsplash.com) or [Pexels](https://www.pexels.com), and credit the
  source in a caption.
- **Always fill in the description** in the square brackets. Screen readers read it
  aloud to people who can't see the image.

### Editing `_config.yml`

This file controls your site-wide identity, **including everything that appears in the
sidebar** next to your bio (name, photo, location, email, and social links). Find the
block that looks like this and fill in your own information:

```yaml
# ============================================================
# EDIT THIS BLOCK — your web address, name, site title, bio, and contact info
# ============================================================
url                      : "https://yourusername.github.io"
baseurl                  : ""
repository               : "yourusername/yourusername.github.io"
title                    : "Your Name's Portfolio" # shown in the header bar and browser tab
author:
  name     : "Your Full Name"
  avatar   : "/images/bio-photo.jpg"
  bio      : "Senior, School of Communication, Virginia Tech."
  location : "Blacksburg, VA"
  email    : "youremail@vt.edu"
  github   : "yourusername"    # username only, no URL — set blank to hide
  instagram: "yourusername"    # username only, no URL — set blank to hide
  linkedin : "yourusername"    # username only, no URL — set blank to hide
# ============================================================
# END EDIT ZONE
# ============================================================
```

**Important:** YAML is whitespace-sensitive. Do not change the indentation. Only edit
the values inside the quotation marks.

#### Adding, updating, or removing sidebar links

Each social link is a single line: `key: "yourusername"`. The template turns each key
into an icon + link in the sidebar automatically — you never type a full URL.

- **To update a link:** change the username in quotes, e.g. `github: "newusername"`.
- **To remove a link:** either delete the line entirely, or leave the value blank
  (`instagram: ""`). A blank or missing value means the icon simply won't appear.
- **To add a link the template already supports:** add a new line in the same
  `key: "username"` format. Beyond `github`, `instagram`, and `linkedin`, other
  supported keys include `twitter`, `youtube`, `bluesky`, `mastodon`, `orcid`, and
  more — the full list lives in `_includes/author-profile.html` if you want to see
  every option (search that file for `author.` followed by a key name, e.g. `author.twitter`).
- Keep every line indented exactly two spaces under `author:`, matching the lines
  already there. Broken indentation breaks the whole site.

### Adding a photo

Replace the file at `images/bio-photo.jpg` with your own photo. Keep the filename
exactly the same, or update the `avatar` line in `_config.yml` to match your filename.

---

## Markdown basics

All content files use Markdown. You do not need to know HTML. However, mixing HTML and Markdown is ok (as some of you did for your primer website).

```markdown
# Heading 1
## Heading 2

Regular paragraph text.

**Bold text**   *Italic text*

- Bullet item
- Another item

[Link text](https://example.com)
```

Don't forget the [Markdown Tutorial](http://markdowntutorial.com) that we have used earlier this semester.

---

## Keeping a real revision history

The GitHub revision history of your repository is part of your grade. Make commits as
you work — not one large upload at the end of each milestone. A commit after every
meaningful editing session is the right pace. Your commit messages should be honest
about what you changed: *"Add about page draft"* is better than *"update."* This
applies to changes Copilot makes, too.

---

## Getting help

- **Copilot Chat:** Ask it to explain a file or an error (use **Ask** mode).
- **HokieAI:** Paste your error message or your Markdown draft and ask for help.
  HokieAI is available to all VT students at [hokieai.vt.edu](http://hokieai.vt.edu).
- **GitHub Docs:** [docs.github.com](https://docs.github.com) has clear walkthroughs
  for everything this template uses, including
  [Codespaces](https://docs.github.com/en/codespaces)
  and [GitHub Copilot](https://docs.github.com/en/copilot).
- **In class:** All the stuff we have already covered about working in GitHub.
- **Office hours:** LAHSB 013. Come with your laptop and your specific question.

---

Thanks to your uncle Claude for helping with this template. 
