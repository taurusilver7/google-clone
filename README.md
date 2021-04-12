# Google Clone

> A google search engine using react-js & next-js & tailwind css
> The next js is a react framework for server-side rendering.

- To set up the tailwind css onthe next-js project
  `npm install -D tailwindcss@latest postcss@latest autoprefixer@latest`
- To create the configure files fo tailwind (generate your tailwind.config.js and postcss.config.js files)
  `npx tailwindcss init -p`
- Enable the 'jit' mode in the config file for a more powerful engine for tailwind.
  mode: 'jit',
- Inclue the base, component, utilities directives in `/styles/globals.css`

- When an image using _Image_ component isused, next-js has to be informed about it to configure the image for the project. It is configured in the _next.configure.js_ file to add the domains of the resources used in next-js.
  `module.exports = { images: { domain: ["domain names..."] } } `

- Use a rest_api to invoke an api key for developer [here](https://developers.google.com/custom-search/v1/using_rest)
- The google content search authorization [here](https://cse.google.com/cse/create/new)

- A plugin for the tailwind to use a dependency
  ` plugins: [require("@tailwindcss/line-clamp")],`

- Deployed on vercel integrated to github with cli-pipeline integrated.

## Stock

- [Google logo](https://www.google.co.in/images/branding/googlelogo/1x/googlelogo_color_272x92dp.png)
- [title icon](https://www.favicon.cc/?action=icon&file_id=960348)

This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.js`. The page auto-updates as you edit the file.

[API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:3000/api/hello](http://localhost:3000/api/hello). This endpoint can be edited in `pages/api/hello.js`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
