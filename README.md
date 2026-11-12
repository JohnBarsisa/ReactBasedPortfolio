# React-Based Personal Portfolio

A personal software-engineering portfolio built with React and customised from the open-source **masterPortfolio** starter.

> **Project status:** existing web/source implementation. This repository is an adapted portfolio template, not a claim that all original starter features were authored from scratch.

## What the site presents

- Personal introduction and professional profile.
- Technical skills, cloud and application engineering interests.
- Experience, education, certifications and external links.
- Projects and public GitHub activity in a responsive layout.
- Configurable themes and reusable React components.

## Tech stack

React · JavaScript · HTML/CSS · GitHub APIs · Node.js/npm · Docker-related setup files.

## Structure

```text
src/portfolio.js         Personal content and link configuration
src/components/          Shared UI components
src/containers/          Page sections
src/pages/               Page compositions
src/theme.js             Theme configuration
public/                  Static public assets
images/                  Template/project imagery
git_data_fetcher.mjs     Optional GitHub data-fetch script
```

## Local setup

```bash
git clone https://github.com/JohnBarsisa/ReactBasedPortfolio.git
cd ReactBasedPortfolio
npm install
npm start
```

This is a legacy React codebase and may require a compatible Node/npm toolchain and dependency maintenance. Review the `package.json` scripts before deploying.

## Portfolio preparation checklist

- Review `src/portfolio.js` for current CV details, links and contact information.
- Replace any inherited author emails, social URLs, hero graphics or deployment badges.
- **Never hard-code GitHub personal access tokens** in `git_data_fetcher.mjs`; use a secret environment variable if required.
- Verify the actual deployed URL and mobile behaviour before sharing it with interviewers.
- Review embedded project content before making any private work public.

## Upstream credits

Based on [ashutosh1919/masterPortfolio](https://github.com/ashutosh1919/masterPortfolio). The original template's full README has been retained at [docs/UPSTREAM_TEMPLATE_README.md](docs/UPSTREAM_TEMPLATE_README.md) for installation details and credit. See the root `LICENSE` for its licensing terms.

**Maintainer/customisation:** [JohnBarsisa](https://github.com/JohnBarsisa). For the newer gallery of personal concepts and products, see [Portfolio](https://github.com/JohnBarsisa/Portfolio).
