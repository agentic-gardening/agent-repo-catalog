# agent-repo-catalog

Part of the agentic-gardening tech-debt agents. See README.md for purpose and secrets.
Stack: TypeScript, inversify (explicit `@inject`, classes, ContainerModules), vitest, pnpm 12, eslint + biome format.
Before pushing: `pnpm lint:check && pnpm format:check && pnpm typecheck && pnpm test && pnpm build`.
