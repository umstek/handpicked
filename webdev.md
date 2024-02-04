# Web development stacks

## Frontend
- Language: [TypeScript](https://www.typescriptlang.org/)
- Framework (better not use a framework and just use vite): [NextJS](https://nextjs.org/) (For SSR+, optional, not a personal recommendation, only professional) or [Remix](https://remix.run/) (For nested content, optional, yet to try) or [Astro](https://astro.build/) (For SSG/blog, optional, my blog is Astro. Astro _probably_ can do whatever nextjs does, better).
- State Management: [RxJS](https://rxjs.dev/) based redux-equivivalent or [Apollo Client](https://www.apollographql.com/) if using [GraphQL](https://graphql.org/), [React Router](https://reactrouter.com/). TBH haven't found anything good, yet. Certainly not redux.
- UI Library: [React](https://reactjs.org/)
- Components/Styling: [TailwindCSS](https://tailwindcss.com/) for styling; [React Aria by Adobe](https://react-spectrum.adobe.com/react-aria/), [Radix UI](https://www.radix-ui.com/), [Material UI Base](https://mui.com/base-ui/getting-started/), [Headless UI](https://headlessui.dev/) (not many components), or [the components used in Ant.Design](http://react-component.github.io/badgeboard/) -- all of them are unstyled components; you likely can use them together. You may also want to look at [Shadcn UI](https://ui.shadcn.com/) which downloads component templates created using Radix UI and TailwindCSS.  
- Compiler/bundler: [Vite](https://vitejs.dev/) (Uses [esbuild](https://esbuild.github.io/), [Rollup](https://rollupjs.org/) under the hood and can configure to use [SWC](https://swc.rs/) for HMR.)
- Testing: [Jest](https://jestjs.io/)/[TS-Jest](https://kulshekhar.github.io/ts-jest/) or [vitest](https://vitest.dev/), [Testing Library](https://testing-library.com/) (yet to try)

## Backend
- Language: TypeScript
- Runtime: [Bun](https://bun.sh/) when stable, NodeJS for now
- Framework: [NestJS](https://nestjs.com/) ([express](https://expressjs.com/) based [or optionally fastify based], create standard APIs fast), or [Fastify](https://www.fastify.io/) (performant, flexible more framework-ey than express)
- Next-gen (kind of) frameworks: [Hono](https://hono.dev/) runs on edge platforms too, [Elysia](https://elysiajs.com/).
- Libraries: Express and Apollo if using GraphQL
- Database/ORM-equivalent: For [MongoDB](https://www.mongodb.com/) -> [Mongoose](https://mongoosejs.com/) (flexible and simplifies most use cases, but if you can help it, just use the official mongodb driver) or [TypeORM](https://typeorm.io/) (clean). For [MariaDB](https://mariadb.org/) -> [Drizzle](https://orm.drizzle.team/) or [Sequelize](https://sequelize.org/) (old way). 
- Testing: Jest/TS-Jest
- Creating interactive CLIs: [Prompts](https://github.com/terkelg/prompts) because Inquirer.js is not feature rich and enquirer v2x is broken.

## Other
- Dependency Manager: Bun, [PNPM](https://pnpm.io/)
- VCS/Repo: [Git](https://git-scm.com/)/[GitHub](https://github.com/)
- CI/CD: [GitHub Actions](https://github.com/features/actions)
- CDN: [Cloudflare](https://www.cloudflare.com/)
- Formatter: [Prettier](https://prettier.io/)
- Linter: [ESLint](https://eslint.org/)
- Editor: [Visual Studio Code](https://code.visualstudio.com/), [Zed](https://zed.dev/) (mac only) or [Neovim](https://neovim.io/) + a good "framework" like [LunarVim](https://www.lunarvim.org/) may serve you same or better than vscode, but I'm not that nerdy.
- Shell: [ZSH](https://www.zsh.org/) + [Oh My Zsh](https://ohmyz.sh/)
- E2E Testing: [Playwright](https://code.visualstudio.com/)
- Sending email: [Resend](https://resend.com/) (yet to try)

### Other libraries for JavaScript/TypeScript
- Functional Reactive Programming: [RxJS](https://rxjs.dev/)
- Date/Time: All of them are garbage; try to use temporal API with [@js-temporal/polyfill](https://github.com/js-temporal/temporal-polyfill) and write methods yourself.

### Other libraries for React
- Forms: [React Hook Form](https://react-hook-form.com/)
- I18n: [FormatJS/React-Intl](https://formatjs.io/)
- Displaying a large set of data efficiently: [Tanstack Virtual](https://tanstack.com/virtual/latest), [React Window](https://github.com/bvaughn/react-window)
- Routing: [React Router](https://reactrouter.com/en/main)
- Managing Meta Tags: [React Helmet Async](https://github.com/staylor/react-helmet-async)
