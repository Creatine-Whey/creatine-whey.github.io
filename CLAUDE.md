# CLAUDE.md

## Goal

A personal website with **Home**, **Projects**, **Experience**, **Resume** and **Contact** pages, built with Astro and hosted on GitHub Pages at https://creatine-whey.github.io.

## Stack

- **Astro** (static site output)
- **Node.js** LTS
- **GitHub Pages**, deployed via **GitHub Actions**

## Rules

1. Make small changes, and name every file you create or change.
2. Never hardcode secrets.
3. Use `TODO` placeholders for personal details (name, email, links, etc.) until I confirm a real detail. After I confirm it, use only my confirmed wording. Never invent facts, dates, employers, numbers or links.
4. The master resume lives in a separate private repo. Publish only what I approve for the website.
5. Ask before adding any new dependency, and say why it is needed.
6. After each step, tell me the exact command to run and what I should see.
7. Ignore every `.env` file except `.env.example`. Never commit `.env` files.

## Git

- Do not run git commit, git push or any command that changes Git history.
- After each working step, list the files changed, suggest a commit message in feat:, fix: or docs: format, and show the status checklist change. I will commit in Terminal.
- Never force-push or rewrite history.

## Safety

- Ask before deleting files, installing software, or running commands outside this folder.

## Privacy

- Never publish phone numbers, home address, NRIC or personal email.
- Use only the GitHub no-reply email.
- Remove location data from photos before adding them.

## Astro config

- Set `site` to `https://creatine-whey.github.io` and keep `base` as `"/"`.

## Quality

- Run `npm run build` before saying a step is done, and fix any errors.
- Use semantic HTML, alt text on images, and a title on every page.
- Check layouts at phone width.
- No analytics, tracking scripts or third-party embeds unless I ask.

## Status

Don't tick a checklist item until I've confirmed it works.

- [x] Starter files
- [ ] Astro skeleton
- [ ] Placeholder pages
- [ ] Real content
- [ ] GitHub Pages deploy
- [ ] Phone check
