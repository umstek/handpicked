# Web development stacks

## Frontend
- Language: [TypeScript](https://www.typescriptlang.org/)
- Framework (better not use a framework and just use vite): [NextJS](https://nextjs.org/) (For SSR+, optional) or [Remix](https://remix.run/) (For nested content, optional, yet to try) or [Astro](https://astro.build/) (For SSG/blog, optional, my blog is Astro)
- State Management: [RxJS](https://rxjs.dev/) based redux-equivivalent or [Apollo Client](https://www.apollographql.com/) if using [GraphQL](https://graphql.org/), [React Router](https://reactrouter.com/)
- UI Library: [React](https://reactjs.org/)
- Components/Styling: [TailwindCSS](https://tailwindcss.com/) for styling; augmented with [Shadcn UI](https://ui.shadcn.com/) which downloads component templates created using Radix UI and TailwindCSS; [Headless UI](https://headlessui.dev/), [Radix UI](https://www.radix-ui.com/), or [the components used in Ant.Design](http://react-component.github.io/badgeboard/) -- all of them are unstyled components; you can even use all of them together. 
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
- Editor: [Visual Studio Code](https://code.visualstudio.com/), Or [Neovim](https://neovim.io/) + a good "framework" like [LunarVim](https://www.lunarvim.org/) can serve you same or better than vscode, but I'm not that nerdy.
- Shell: [ZSH](https://www.zsh.org/) + [Oh My Zsh](https://ohmyz.sh/)
- E2E Testing: [Playwright](https://code.visualstudio.com/)
- Sending email: [Resend](https://resend.com/) (yet to try)

### Other libraries for JavaScript/TypeScript
- Functional Reactive Programming: [RxJS](https://rxjs.dev/)
- Date/Time: [Date-fns](https://date-fns.org/)

### Other libraries for React
- Forms: [React Hook Form](https://react-hook-form.com/)
- Displaying a large set of data efficiently: [React Window](https://github.com/bvaughn/react-window)
- Routing: [React Router](https://reactrouter.com/en/main)
- Managing Meta Tags: [React Helmet Async](https://github.com/staylor/react-helmet-async)
