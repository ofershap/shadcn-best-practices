# shadcn/ui Best Practices

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Skills](https://img.shields.io/badge/skills.sh-shadcn--best--practices-blue)](https://skills.sh/ofershap/shadcn-best-practices)

shadcn/ui done right. Local component ownership, `cn()` class merging, React Hook Form + Zod forms,
CSS variable theming, `cva` variants, Radix primitives, accessible patterns, and the `npx shadcn`
CLI workflow.

> AI coding assistants import from `@shadcn/ui`, use template literals for conditional classes,
> build forms without React Hook Form, hardcode colors, and skip the CLI. This plugin anchors your
> agent to the copy-paste ownership model shadcn/ui is built on.

## Install

### Cursor / Claude Code / Windsurf

```bash
npx skills add ofershap/shadcn-best-practices
```

Or copy `skills/` into your `.cursor/skills/` or `.claude/skills/` directory.

## What's Included

| Type    | Name                    | Description                                                                          |
| ------- | ----------------------- | ------------------------------------------------------------------------------------ |
| Skill   | `shadcn-best-practices` | 12 rules for component ownership, cn(), forms, theming, cva, accessibility, and more |
| Rule    | `best-practices`        | Always-on behavioral rule that enforces shadcn/ui patterns                           |
| Command | `/audit`                | Scan your codebase for shadcn/ui anti-patterns                                       |

## What Agents Get Wrong

| What the agent writes                     | What shadcn/ui actually uses                      |
| ----------------------------------------- | ------------------------------------------------- |
| `import { Button } from "@shadcn/ui"`     | `import { Button } from "@/components/ui/button"` |
| Template literals for conditional classes | `cn()` utility from `@/lib/utils`                 |
| Manual form validation                    | React Hook Form + Zod with `<Form>` components    |
| Hardcoded color values                    | CSS variables (`--primary`, `--background`)       |
| Complex conditional class logic           | `cva` (class-variance-authority) for variants     |
| `npm install @shadcn/ui`                  | `npx shadcn@latest add button` via CLI            |

## Related Plugins

- [tailwind-best-practices](https://github.com/ofershap/tailwind-best-practices) - Tailwind CSS v4
  patterns (shadcn/ui depends on Tailwind)
- [typescript-best-practices](https://github.com/ofershap/typescript-best-practices) - TypeScript
  5.x strict patterns

## Author

[![Made by ofershap](https://gitshow.dev/api/card/ofershap)](https://gitshow.dev/ofershap)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/ofershap)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=flat&logo=github&logoColor=white)](https://github.com/ofershap)

## License

MIT
