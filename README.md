<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/hero-dark.svg" />
  <img src="./assets/hero-light.svg" width="100%" alt="Luís Felipe, software engineer in Brasília" />
</picture>

I'm a developer at [Luby](https://www.luby.com.br/), mostly on the backend, but I like owning a feature all the way: the schema and its access rules, the API, and the React screen on top of it.

Most of my time outside work goes into **[WeddingPlan](https://weddingplan.com.br)**, a platform for planning weddings and other events. Couples and professional planners use it for guest lists, RSVPs, budgets, tasks, invitations and a public event site. It's a private repo, so the work doesn't show up here, but it's close to 4,000 commits this year.

<br />

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/roteiro-dark.svg" />
  <img src="./assets/roteiro-light.svg" width="100%" alt="A typical weekday as a run sheet: backend work at Luby by day, WeddingPlan with a crew of AI agents by night" />
</picture>

<sub><i>"Roteiro" is the run sheet screen in WeddingPlan. This is mine.</i></sub>

### How I work with AI

AI is one of my main focuses, in two ways.

**In the workflow.** I treat coding agents like a small team. A project gets split into issues with a dependency graph, each agent works on one issue in its own git worktree, and nothing merges without a separate reviewer agent, green CI and a QA pass on staging. My job is the spec, the review rules and the final call. Most of WeddingPlan has been built this way.

**In the product.** WeddingPlan ships an assistant that can actually do things in the app through tool calls, with intent routing, per-plan token budgets and usage limits, and it writes invitation drafts.

### Some things I've built

- **[WeddingPlan](https://weddingplan.com.br)**: React 19, TypeScript, Supabase, Postgres with row-level security, edge functions, Vitest, Playwright and pgTAP.
- **[Collaborative task manager](https://github.com/iLuiszin/fullstack-challenge)**: a technical challenge done as NestJS microservices over RabbitMQ, with JWT auth, real-time notifications over WebSocket, structured logs and a React 19 front end.
- **[AI meter reading](https://github.com/iLuiszin/shopper-teste)**: a backend that reads water and gas meters from photos with an AI vision model. Node.js, TypeScript, Prisma, Docker.

### Tools I reach for

TypeScript · Node.js · React · PostgreSQL · Supabase · NestJS · TanStack Query · Tailwind · Vitest · Playwright · Docker · GitHub Actions · a bit of Go

### Elsewhere

[LinkedIn](https://www.linkedin.com/in/luisfdeveloper/) · [oluis10@gmail.com](mailto:oluis10@gmail.com)

<br />

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/iLuiszin/iLuiszin/output/github-snake-dark.svg" />
  <img src="https://raw.githubusercontent.com/iLuiszin/iLuiszin/output/github-snake.svg" width="100%" alt="Contribution graph being eaten by a snake" />
</picture>
