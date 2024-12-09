# Material UI - Next.js Pages Router example

## How to use

Download the example [or clone the repo](https://github.com/mui/material-ui):

<!-- #default-branch-switch -->

```bash
curl https://codeload.github.com/mui/material-ui/tar.gz/master | tar -xz --strip=2  material-ui-master/examples/material-ui-nextjs-pages-router
cd material-ui-nextjs-pages-router
```

Install it and run:

```bash
npm install
npm run dev
```

or:

<!-- #default-branch-switch -->

[![Edit on StackBlitz](https://developer.stackblitz.com/img/open_in_stackblitz.svg)](https://stackblitz.com/github/mui/material-ui/tree/master/examples/material-ui-nextjs-pages-router)

[![Edit on CodeSandbox](https://codesandbox.io/static/img/play-codesandbox.svg)](https://codesandbox.io/p/sandbox/github/mui/material-ui/tree/master/examples/material-ui-nextjs-pages-router)

## The idea behind the example

**Note:** This example is set up to use the Next.js Pages Router.
As of Next.js 13.4, the newer App Router pattern is stable.
We recommend starting new projects with the [Material UI with Next.js (App Router) example](https://github.com/mui/material-ui/tree/master/examples/material-ui-nextjs) unless you need (or prefer) the Pages Router.

The project uses [Next.js](https://github.com/vercel/next.js), which is a framework for server-rendered React apps.
It includes `@mui/material` and its peer dependencies, including [Emotion](https://emotion.sh/docs/introduction), the default style engine in Material UI v6.
If you prefer, you can [use styled-components instead](https://mui.com/material-ui/integrations/interoperability/#styled-components).

## The Link component

The [example folder](https://github.com/mui/material-ui/tree/HEAD/examples/material-ui-nextjs-pages-router) provides an adapter for the use of [Next.js's Link component](https://nextjs.org/docs/pages/api-reference/components/link) with Material UI.
More information [in the documentation](https://mui.com/material-ui/integrations/routing/#next-js-pages-router).

## Upgrading to Next.js 15

This example uses Next.js 14.
To upgrade to version 15, please follow the [official upgrade guide](https://nextjs.org/docs/app/building-your-application/upgrading/version-15) in the Next.js docs.

## What's next?

<!-- #default-branch-switch -->

You now have a working example project.
You can head back to the documentation and continue by browsing the [templates](https://mui.com/material-ui/getting-started/templates/) section.
