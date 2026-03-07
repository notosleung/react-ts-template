# [@notosleung/react-ts-template](https://github.com/notosleung/react-ts-template)

- Base on the **[Vite](https://vite.dev/)** officially recommended `react-ts` template
- ~~Use **[React-Router](https://github.com/remix-run/react-router)** as the Router for **[React](https://github.com/facebook/react)**~~
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

> [!TIP]
> your first commit should be with `--no-verify`:

```bash
git commit -m "..." --no-verify
```

## State Management Solution

Recommend **[Zusand](https://github.com/pmndrs/zustand)**

## Style

Recommend **[UnoCSS](https://github.com/unocss/unocss)** or **[tailwindcss](https://github.com/tailwindlabs/tailwindcss)**
