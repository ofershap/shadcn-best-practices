# shadcn/ui Best Practices

shadcn/ui done right. Component customization, form patterns with React Hook Form + Zod, theming,
accessibility, and composition patterns your AI agent should follow.

## Install

### Cursor IDE

```
/add-plugin shadcn-best-practices
```

### Claude Code

```
/plugin install shadcn-best-practices
```

### Skills only (any agent)

```bash
npx skills add ofershap/shadcn-best-practices/shadcn-best-practices
```

Or copy `skills/` into your `.cursor/skills/` or `.claude/skills/` directory.

## What's Included

### Skills

- **shadcn-best-practices** - shadcn/ui done right. Component customization, form patterns with
  React Hook Form + Zod, theming, accessibility, and composition patterns your AI agent should
  follow.

### Rules

- **best-practices** - Always-on rules that enforce current shadcn/ui patterns

### Commands

- `/audit` - Scan your codebase for shadcn/ui anti-patterns

## Why This Plugin?

AI agents often treat shadcn/ui as a conventional npm dependency and suggest imports from
`@shadcn/ui` or wrap components instead of customizing source. They skip the `cn()` utility for
class merging, use template literals for conditional styles, and build forms without React Hook
Form + Zod. They hardcode colors instead of CSS variables, write manual validation instead of
schema-based validation, and ignore the CLI for adding components. This plugin anchors your agent to
the copy-paste model, proper form patterns, theming via CSS variables, and the composition patterns
shadcn/ui is designed for.

## License

MIT
