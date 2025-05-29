# Project Guide

## Dir and Code Structure

* `apps/main` main app desc

## Tech Stack

server:

* `next.js`
* `prisma` on `supabase`
* ...

client:

* `shadcn/ui`
* `zustand`: make sure use `zustand` for shared state management if you need cross-component state management
* `ahooks`
* `dayjs`
* `lodash`
* `swr`: in react components, must use `swr` for data fetching and processing

use native `fetch` for data fetching, more can be seen from `package.json`

## Conventions

[Next.js]

> code examples to guide app architecture design

* MUST use `composeServerActions`, `composeServerPage` and `composeAPIRoute` wrap for auth middleware functions, for server actions, server pages and api routes, you can check the similar implementation for case to use

you must learn from the following examples:

* server action: `server/actions/example/example.server.action.ts`
* api route: `server/api/example/route.ts`
* page: `client/app/example/page.tsx`


## Dev Notice

* use `pnpm` to add dependencies under specific sub-packages


