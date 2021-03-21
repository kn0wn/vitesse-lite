# ⚠ Archived ⚠

This project has been archived, please use the latest version of [vitesse](https://github.com/antfu/vitesse)

# Vitesse-lite

A lighter version of Antfu's Vue3 boilerplate, if you like this please support Antfu's work using the sponsor button on this page.

<br>

## Features

- ⚡️ [Vue3](https://github.com/vuejs/vue-next), [Vite](https://github.com/vitejs/vite), [ESBuild](https://github.com/evanw/esbuild) - born with fastness

- 🗂 [File based routing](./src/pages)

- 📲 [Components auto importing](./src/components)

- 🎨 TailwindCSS with dark mode out-of-box

- 🦾 TypeScript, of course

- ☁️ Deploy on Netlify, zero config

<br>

## Pre-packed

### UI Frameworks

- [Tailwind CSS](https://tailwindcss.com/) - with built-in dark mode!

### Plugins

- [Vue Router](https://github.com/vuejs/vue-router)
  - [vite-plugin-voie](https://github.com/vamplate/vite-plugin-voie) - file system based routing
- [vite-plugin-components](https://github.com/antfu/vite-plugin-components) - components auto import
- [VueUse](https://github.com/antfu/vueuse) - collection of useful composition APIs

### Coding Style

- Use Composition API with [`<script setup>` SFC](https://github.com/vuejs/rfcs/blob/sfc-improvements/active-rfcs/0000-sfc-script-setup.md)
- [ESLint](https://eslint.org/) with [@antfu/eslint-config-vue](https://github.com/antfu/eslint-config), single colons, no semi.

### Dev tools

- [TypeScript](https://www.typescriptlang.org/)
  - [Vue TypeScript Plugin](https://github.com/znck/vue-developer-experience/tree/master/packages/typescript-plugin-vue) - better type support for Vue
- [Netlify](https://www.netlify.com/) - deploy
- [VS Code Extensions](./.vscode/extensions.json)
  - [Tailwind CSS IntelliSense](https://marketplace.visualstudio.com/items?itemName=bradlc.vscode-tailwindcss)
  - [Vetur](https://marketplace.visualstudio.com/items?itemName=octref.vetur)
  - [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)

## Try it now!

### Github Template

[Create a repo from this template on Github](https://github.com/kn0wn/vitesse-lite/generate).

### Clone to local

If you prefer do to it manually with cleaner git history

```bash
npx degit kn0wn/vitesse-lite my-vitesse-lite-app
cd my-vitesse-lite-app
npm i
```

## Checklist

When you use this template, try follow the checklist to update your info properly

- [ ] Rename `name` field in `package.json`
- [ ] Change the author name in `LICENSE`
- [ ] Change the title in `index.html`
- [ ] Change the favicon in `public`
- [ ] Remove the `.github` folder which contains the funding info
- [ ] Clean up the READMEs and remove routes

And, enjoy :)

## Usage

### Development

Just run and visit http://localhost:3000

```bash
npm run dev
```

### Build

To build the App, run

```bash
npm run build
```

And you will see the generated file in `dist` that is ready to be served.

### Deploy on Netlify

Go to [Netlify](https://app.netlify.com/start) and select you clone, `OK` along the way, and your App will be live in a minute.

## Why

I have removed certain items from the original Vitesse as I found I didn't need as much and was removing it whenever I created a new project.
