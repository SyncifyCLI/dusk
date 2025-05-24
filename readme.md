# Syncify ~ Dusk

A bare bones starting point strap for Shopify theme development using [Syncify](https://github.com/panoply/syncify). This strap is similar to [Skeleton](https://github.com/syncifycli/skeleton) but comes with some feature presets cooked in.

### Showcasing

This strap demonstrates basic level configuration using a blank theme structure.

- Configuration defined within `package.json` file.
- Bundles TypeScript into JavaScript
- Bundles SASS into CSS
- Bundles SVG using SVGO and outputs as snippet
- Using project-level `.env` file for shop credentials

# Instructions

You can start hacking on this project by either forking and installing depedendencies or using the `sy init` command prompt. It is assumed that you have the [@syncify/cli](https://github.com/panoply/syncify) installed as a global depencency on your computer and have access to store credentials.

- [Installation](https://syncify.sh/setup/installation/)
- [Authentication](https://syncify.sh/setup/authentication/)

## Installation

You can initialize a new theme project based on this strap using the `sy init` command:

```bash
sy init dusk
```

## Commands

Couple of basic commands to use during development:

```bash
sy watch           # Runs Syncify in development watch mode
sy watch --hot     # Runs Syncify in development watch mode with hot reloads
sy build           # Runs Syncify in build mode
sy build --prod    # Runs Syncify in build mode with production output
```

# License

UNLICENSED
