# Medium Clone

Everyone knows about the Medium Blog where you can go and post anything you want.

You can take a look at the result [here](https://medium-clone-polescalera.vercel.app/)

Well, here's the clone using the stack:

- NextJS (React Framework)
- Sanity (as CMS)
- TailwindCSS 

## How to make it work

Checking the project files you'll notice that there's `medium-clone` folder inside the project that's also named the same.
That folder is for Sanity.

So, first of all:

- Clone this repo, cd into it and `npm install`
- After the installation, cd into `medium-clone` and again, `npm install` as it's another project with its own dependencies.
- Notice that you'll need a FREE account for Sanity.
- Env Variables that you need to reproduce this project (you can find them once you are logged in Sanity and created a project):
  - NEXT_PUBLIC_SANITY_DATASET
  - NEXT_PUBLIC_SANITY_PROJECT_ID
  - SANITY_API_TOKEN
- Run app by `yarn dev`
- Run local sanity by cd into sanity folder (medium-clone) and `sanity start` - notice that you will need sanity installed globally on your PC


# Next.js + Tailwind CSS Example

This example shows how to use [Tailwind CSS](https://tailwindcss.com/) [(v3.0)](https://tailwindcss.com/blog/tailwindcss-v3) with Next.js. It follows the steps outlined in the official [Tailwind docs](https://tailwindcss.com/docs/guides/nextjs).

## Deploy your own

Deploy the example using [Vercel](https://vercel.com?utm_source=github&utm_medium=readme&utm_campaign=next-example) or preview live with [StackBlitz](https://stackblitz.com/github/vercel/next.js/tree/canary/examples/with-tailwindcss)

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/git/external?repository-url=https://github.com/vercel/next.js/tree/canary/examples/with-tailwindcss&project-name=with-tailwindcss&repository-name=with-tailwindcss)

## How to use

Execute [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app) with [npm](https://docs.npmjs.com/cli/init), [Yarn](https://yarnpkg.com/lang/en/docs/cli/create/), or [pnpm](https://pnpm.io) to bootstrap the example:

```bash
npx create-next-app --example with-tailwindcss with-tailwindcss-app
```

```bash
yarn create next-app --example with-tailwindcss with-tailwindcss-app
```

```bash
pnpm create next-app --example with-tailwindcss with-tailwindcss-app
```

Deploy it to the cloud with [Vercel](https://vercel.com/new?utm_source=github&utm_medium=readme&utm_campaign=next-example) ([Documentation](https://nextjs.org/docs/deployment)).
