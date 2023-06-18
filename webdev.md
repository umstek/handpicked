# Web development stacks

## Frontend
- Language: [TypeScript](https://www.typescriptlang.org/)
- Framework (better not use a framework and just use vite): [NextJS](https://nextjs.org/) (For SSR+, optional) or [Remix](https://remix.run/) (For nested content, optional, yet to try) or [Astro](https://astro.build/) (For SSG/blog, optional, my blog is Astro)
- State Management: [RxJS](https://rxjs.dev/) based redux-equivivalent or [Apollo Client](https://www.apollographql.com/) if using [GraphQL](https://graphql.org/), [React Router](https://reactrouter.com/)
- UI Library: [React](https://reactjs.org/)
- Components/Styling: [TailwindCSS](https://tailwindcss.com/) augmented with, [Shadcn UI](https://ui.shadcn.com/) which uses radix ui and tailwindcss, [Headless UI](https://headlessui.dev/), [Radix UI](https://www.radix-ui.com/), or [the components used in Ant.Design](http://react-component.github.io/badgeboard/). TailwindCSS is for styling and others are minimal/un-styled components. You can even use all of them.  
- Compiler/bundler: [Vite](https://vitejs.dev/) (Uses [esbuild](https://esbuild.github.io/) and can configure to use [SWC](https://swc.rs/) for HMR, optionally use [Vite SSR plugin](https://vite-plugin-ssr.com/) for SSR/SSG)
- Testing: [Jest](https://jestjs.io/)/[TS-Jest](https://kulshekhar.github.io/ts-jest/) or [vitest](https://vitest.dev/), [Testing Library](https://testing-library.com/) (yet to try)

## Backend
- Language: TypeScript
- Framework: [NestJS](https://nestjs.com/) ([express](https://expressjs.com/) based [or optionally fastify based], create standard APIs fast), or [Fastify](https://www.fastify.io/) (performant, flexible more framework-ey than express)
- Libraries: Express and Apollo if using GraphQL
- Compiler/bundler: NestJS default (TSC)
- Database/ORM-equivalent: [MongoDB](https://www.mongodb.com/)/[Mongoose](https://mongoosejs.com/) (flexible and simplifies most use cases, but the official driver will still be the most flexible) or MongoDB/[TypeORM](https://typeorm.io/) (clean) or [MariaDB](https://mariadb.org/)/[Prisma](https://www.prisma.io/) or MariaDB/[Sequelize](https://sequelize.org/)
- Testing: Jest/TS-Jest

## Other
- Dependency Manager: [PNPM](https://pnpm.io/)
- VCS/Repo: [Git](https://git-scm.com/)/[GitHub](https://github.com/)
- CI/CD: [GitHub Actions](https://github.com/features/actions)
- CDN: [Cloudflare](https://www.cloudflare.com/)
- Formatter: [Prettier](https://prettier.io/)
- Linter: [ESLint](https://eslint.org/)
- Editor: [Visual Studio Code](https://code.visualstudio.com/)
- E2E Testing: [Playwright](https://code.visualstudio.com/)
