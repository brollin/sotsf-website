<div align="center">
  <h2>Servants of the Secret Fire</h2>
  <p><a href="https://se.cretfi.re"> https://se.cretfi.re</a></p>
</div>

## Development

It is encouraged to use **pnpm** so the husky hooks can work properly.

```bash
pnpm install
```

You can start the server using this command:

```bash
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result. You can start editing the page by modifying `src/pages/index.tsx`.

## Features

This repository is 🔋 battery packed with:

- ⚡️ Next.js 14 with App Router
- ⚛️ React 18
- ✨ TypeScript
- 💨 Tailwind CSS 3 — Configured with CSS Variables to extend the **primary** color
- 💎 Pre-built Components — Components that will **automatically adapt** with your brand color, [check here for the demo](https://tsnext-tw.thcl.dev/components)
- 🃏 Jest — Configured for unit testing
- 📈 Absolute Import and Path Alias — Import components using `@/` prefix
- 📏 ESLint — Find and fix problems in your code, also will **auto sort** your imports
- 💖 Prettier — Format your code consistently
- 🐶 Husky & Lint Staged — Run scripts on your staged files before they are committed
- 🤖 Conventional Commit Lint — Make sure you & your teammates follow conventional commit
- ⏰ Release Please — Generate your changelog by activating the `release-please` workflow
- 👷 Github Actions — Lint your code on PR
- 🚘 Automatic Branch and Issue Autolink — Branch will be automatically created on issue **assign**, and auto linked on PR
- 🔥 Snippets — A collection of useful snippets
- 👀 Open Graph Helper Function — Awesome open graph generated using [og](https://github.com/theodorusclarence/og), fork it and deploy!
- 🗺 Site Map — Automatically generate sitemap.xml
- 📦 Expansion Pack — Easily install common libraries, additional components, and configs.

## Deploying

Also will explain why we have `brollin/sotsf-website` as well as `sotsf/sotsf-website`.

Vercel does not allow you to deploy an organization repo like `sotsf/sotsf-website` on their free hobby tier. So instead, we deploy `brollin/sotsf-website`.

To deploy, all you have to do is to push a new commit to the `main` branch. First you will need to be a collaborator on the `brollin/sotsf-website` repo, so just ask Ben for that.

For ease, you should clone `sotsf/sotsf-website`. Then you can set up a new remote called `prod` to point at `brollin/sotsf-website`:

```
git remote add prod ssh://git@github.com/brollin/sotsf-website.git
```

And then to deploy would just look like:

```
git remote add prod ssh://git@github.com/brollin/sotsf-website.git
```
