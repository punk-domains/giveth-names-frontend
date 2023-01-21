# Giveth Names frontend

Frontend for .giveth domain service powered by the [Punk Domains protocol](https://punk.domains).

## Quickstart

```bash
npm install
npm run dev
```

## What to adapt?

Search for all `@todo` occurences in the code.

In addition to that also change the necessary files in the `abi` folder:

- Minter.json (Minter contract ABI)
- tlds.json (add the TLD address for a given chain ID)
- tokens.json (add the correct tokens; this shows up on the Send Tokens page)

## Cover/preview image (Twitter/FB)

Use the Twitter post size of 1600x900 px.

## Branches & deployment

- **Important:** Never commit directly to the `main` branch.
- Development is done on the `develop` branch (or temporary branches which then merge with the `develop` branch).
- Deployment: When you want to make deployment to the production server, merge `develop` into the `main` branch. A CI/CD system on GitHub (GitHub Actions) will automatically build and deploy the new code to GitHub Pages.