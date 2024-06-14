::: tip Compatibility Note
Vite requires [Node.js](https://nodejs.org/en/) version 18.x.x or 20+. However, some templates may require a higher Node.js version to work, please upgrade Node if your package manager warns about it.
:::

::: code-group

```bash [pnpm]
$ pnpm create @vite-pwa/pwa
```

```bash [yarn]
$ yarn create @vite-pwa/pwa
```

```bash [npm]
$ npm create @vite-pwa/pwa@latest
```

```bash [bun]
$ bun create @vite-pwa/pwa
```

:::

Then follow the prompts!

You can also directly specify the project name and the template you want to use via additional command line options. For example, to scaffold a Vite PWA + Vue project, run:

```bash
# pnpm
pnpm create @vite-pwa/pwa my-vue-app --template vue

# yarn
yarn create @vite-pwa/pwa my-vue-app --template vue

# npm 7+, extra double-dash is needed:
npm create @vite-pwa/pwa@latest my-vue-app -- --template vue

# bun
bun create @vite-pwa/pwa my-vue-app --template vue
```

See [create-pwa](https://github.com/vite-pwa/create-pwa) for more details on each supported template: `vanilla`, `vanilla-ts`, `vue`, `vue-ts`, `react`, `react-ts`, `preact`, `preact-ts`, `lit`, `lit-ts`, `svelte`, `svelte-ts`, `solid`, `solid-ts` (templates can be found inside the `templates` folder).
