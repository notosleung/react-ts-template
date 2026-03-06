# [@notos9312/react-ts-template](https://github.com/notos9312/react-ts-template)

- Base on the **[Vite](https://vite.dev/)** officially recommended `react-ts` template
- Use **[React-Router](https://github.com/remix-run/react-router)** as the Router for [React](https://github.com/facebook/react)
- Use **[@antfu/eslint-config](https://github.com/antfu/eslint-config)** as Linter and Formatter
- Use **[husky](https://github.com/typicode/husky)** and **[commitlint](https://github.com/conventional-changelog/commitlint)** as CLI

## Dev

```bash
pnpm run dev
```

## Build

```bash
pnpm run build
```

## ESLint

use **[@antfu/eslint-config](https://github.com/antfu/eslint-config)**

## Lint the code in project

```bash
pnpm run lint:fix
```

## View what rules are enabled

```bash
npx @eslint/config-inspector
```

## Lint Staged

If you want to apply lint and auto-fix before every commit, this template use [lint-staged](https://github.com/lint-staged/lint-staged) and [simple-git-hooks](https://github.com/toplenboren/simple-git-hooks) (they are already in the `package.json`).

Run the CLI script to update the git hooks with the commands from the config:

```bash
npx simple-git-hooks
```

## Commitlint hint

```bash
feat:     新功能
fix:      修复 bug
docs:     文档修改
style:    代码格式修改（不影响逻辑）
refactor: 代码重构
test:     测试相关
chore:    构建/工具/依赖更新
```

## State Management Solution

Recommend **[Zusand](https://github.com/pmndrs/zustand)**

## Style

Recommend **[UnoCSS](https://github.com/unocss/unocss)** or **[tailwindcss](https://github.com/tailwindlabs/tailwindcss)**
