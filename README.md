# 2-Hour Night Mode

Interactive presentation of the v1 PRD for **2-Hour Night Mode**, a feature concept for the Netflix TV app: tell us how much time you have tonight, and get options that end inside it.

Planning Products, final project · Maayan Nakav & Tal Shami · September 2026

![Title slide](og.png)

## What's inside

- 23 slides plus 7 backup slides for Q&A
- Six parts: Problem & Goal, Solution, v1 Scope, Requirements, LoFi Wireframes, Reflection
- One self-contained `index.html`, no build step and no dependencies

## Controls

| Action | Keys |
|---|---|
| Next / previous slide | → ← or Space, or the buttons on the slide |
| All slides | E |
| Fullscreen | F |
| Link to a slide | add `#s12` to the URL |

## Run locally

Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
```

## Deploy to Vercel

On vercel.com choose Add New → Project, import this repository and click Deploy. Framework preset: Other, no build command, no output directory.

From a terminal in this folder: `npx vercel --prod`

## Files

- `index.html` · the whole presentation
- `favicon.svg`, `og.png` · tab icon and link preview image
- `vercel.json` · clean URLs and basic security headers

The page asks search engines not to index it (`robots noindex` in `index.html`). Delete that line to allow indexing.

---

Student project for a university course. Not affiliated with Netflix.
Built with Claude (Anthropic) as a research and drafting collaborator. Every decision was reviewed and approved by the team.
