# Elaboration Studio Next.js App Template

This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

This is the best practice boilerplate for Next.js powered and implement the principles of [Next.js Architecture Guide via Arno](https://arno.surfacew.com/posts/nextjs-architecture)

Features:

* 🦄 **AI friendly**: add `.context` as context folder to follow the [BP of Arno](https://arno.surfacew.com/posts/cursor.bp#building-project-specific-instructions-for-cursor-ai-code-generation) we add `cursor.mdc` by default to reference the project specific instructions for cursor ai code generation
* 🧰 **Cool Tech Stack**: use the latest and cut-edged cool tech stack to build the app, and also a good practice for AI to handle, less code, more time for crafting ideas
* 💰 **SaaS Minimal Features**: MVP level for a SaaS app x Supabase x basic features to start with: payments, auth, account, etc.

## Tech Stack for this boilerplate

[Basic]

* [TypeScript](https://www.typescriptlang.org)
* [Jest](https://jestjs.io) for testing both client and server

[AI]

* [ai-sdk](https://ai-sdk.dev/docs/introduction)

[Server]

* [Next.js 15](https://nextjs.org) with `Turbopack`
* [Prisma](https://www.prisma.io)
* [Vercel](https://vercel.com) for deployment and CI/CD
* [Supabase](https://supabase.com) platform powered abilities for MVP
  * Supabase Postgres
  * Supabase Auth
  * Supabase Storage
  * Supabase Realtime
  * Supabase KV
  * ...

[Client]

* [React](https://react.dev)
* [Shadcn/ui](https://ui.shadcn.com)
* [Tailwind CSS](https://tailwindcss.com)
* [swr](https://swr.vercel.app/)
* [zustand](https://zustand-demo.pmnd.rs/)

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.
