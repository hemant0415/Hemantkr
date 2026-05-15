# Dr. Hemant Kumar — Personal Website Setup Guide

Welcome! Your website is ready. This guide tells you exactly what to do to make it fully yours.

---

## 📁 Files included

- `index.html` — your main website
- `404.html` — custom "page not found" page
- `README.md` — this file (don't upload it to your host)

---

## 🚀 Quick start (5 minutes)

### Step 1: Test it locally
Double-click `index.html` to open it in any browser. The site works immediately — visitor counter, animations, dark mode, everything.

### Step 2: Host it FREE forever

**Option A — GitHub Pages (recommended):**
1. Create a free account at github.com
2. Create a new repo named exactly: `YOUR-USERNAME.github.io`
3. Upload `index.html` and `404.html`
4. Site goes live at `https://YOUR-USERNAME.github.io` within a minute

**Option B — Netlify (drag-and-drop):**
1. Go to netlify.com (free signup)
2. Drag your folder onto the dashboard
3. Live instantly at `yoursite.netlify.app`

**Option C — Cloudflare Pages:**
Same as Netlify, also free forever — pages.cloudflare.com

---

## 📸 How to add photos

Create a folder called `images/` next to `index.html` and drop in these files:

| File | What it's for |
|---|---|
| `profile.jpg` | Your portrait (shown in hero circle) |
| `phd-research.jpg` | PhD lab / IIT Madras photo |
| `isro.jpg` | ISRO collaboration photo |
| `shell.jpg` | Shell / lignin work photo |
| `postdoc.jpg` | Current research / microalgae photo |
| `janus.jpg` | Janus particles photo |
| `gallery-1.jpg` to `gallery-6.jpg` | Lab / conference / general photos |
| `og-preview.jpg` | 1200×630px social media preview image |
| `CV-Hemant-Kumar.pdf` | Your CV (for the Download button) |

**Any photo missing? No problem.** A beautiful illustration appears in its place. Nothing breaks.

---

## 🔗 Replace placeholder links

Open `index.html` and search for `aaaaa` — replace each with your real URL:

| Find | Replace with |
|---|---|
| `scholar.google.com/citations?user=aaaaa` | Your Google Scholar profile URL |
| `orcid.org/aaaa-aaaa-aaaa-aaaa` | Your ORCID ID |
| `researchgate.net/profile/aaaaa` | Your ResearchGate URL |
| `linkedin.com/in/aaaaa` | Your LinkedIn URL |
| `github.com/aaaaa` | Your GitHub URL (or delete this icon) |
| `twitter.com/aaaaa` | Your X/Twitter handle (or delete) |
| `https://aaaaa.com/` (in meta tags) | Your actual final website URL |
| `formspree.io/f/aaaaa` | Your Formspree form ID (see below) |

There are about 8 places with `aaaaa` — use Ctrl+F to find them quickly.

---

## ✉️ Activate the contact form (1 minute)

1. Go to **formspree.io** and sign up (free, no credit card)
2. Create a new form, copy your form ID (looks like `xyzabcde`)
3. In `index.html`, find `https://formspree.io/f/aaaaa`
4. Replace `aaaaa` with your form ID
5. Done — messages now arrive in your email

Free plan: **50 messages per month**, plenty for an academic site.

---

## 🌐 Optional: Add a custom domain ($10/year)

Once your site is on GitHub Pages or Netlify:
1. Buy a domain at namecheap.com or porkbun.com (about $10/year)
2. In your hosting dashboard, add the domain
3. Done — your site now lives at `hemantkumar.com` (or whatever you choose)

The hosting stays **free forever** — only the domain costs $10/year.

---

## ✨ Features built into your site

- ✅ Animated hero with floating colloidal particles
- ✅ Custom illustration for every research area
- ✅ Dark mode toggle (remembered between visits)
- ✅ Smooth scroll animations
- ✅ Animated number counters
- ✅ Animated publication bar chart
- ✅ Lightbox photo gallery (click to enlarge)
- ✅ Loading screen with your monogram
- ✅ Scroll progress bar at the top
- ✅ "Now" status bar (what you're up to)
- ✅ Manifesto / "Why I do this" quote
- ✅ 5 detailed research stories with impact cards
- ✅ Keywords expertise cloud
- ✅ Awards & honors section
- ✅ Talks & conferences (all 6 listed)
- ✅ Teaching & mentoring section
- ✅ News & updates feed
- ✅ Press kit downloads
- ✅ Contact form (Formspree)
- ✅ Visitor counter (live)
- ✅ Open Graph tags (LinkedIn/WhatsApp previews)
- ✅ JSON-LD structured data (Google understanding)
- ✅ Favicon (custom H monogram)
- ✅ Custom 404 page
- ✅ Print-friendly stylesheet (Ctrl+P prints as clean CV)
- ✅ Fully mobile responsive
- ✅ Loads in under 1 second (no heavy frameworks)

---

## 🛠 How to edit content later

Open `index.html` in any text editor (Notepad, VS Code, even on your phone).
Everything is in plain readable HTML — find the section you want and edit the text.

To add a new publication, find the `<ul class="pub-list">` block and copy one `<li class="pub reveal">` entry.

To update the "Now" status, search for `class="now-text"` and edit the message.

---

## 🆘 Need help?

Common issues:
- **Photos not showing?** Check the filename spelling exactly matches (case-sensitive). Try `profile.jpg`, not `Profile.JPG`.
- **Site not updating after upload?** Hard refresh: Ctrl+F5 (Windows) or Cmd+Shift+R (Mac)
- **Want to change colors?** At the top of `index.html`, find `:root` — change `--copper` to any hex code you like

---

**Made with care. Hosted freely. Yours forever.**
