# Basic Next.js template

This is a basic [Next.js](https://nextjs.org/docs) template intended for getting started quickly without having to remove template cruft from the most basic of the `create-next-app` templates.

I started with `create-next-app --template default --use-npm` and made these changes:

- removed Home.module.css (keeping the basic global.css)
- made the index.js very minimal
- changed from two-space indents to four-space indents
- removed the favicon and Vercel logo from `public`, and added a `.gitignore` to persist the empty directory.
- added a basic `pages/_document.js`

## Notes
- This uses `pages` and not `app`, although it uses Next 13 (i.e. it isn't using the newer experimental features, for now).
- This uses javascript and not typescript.

## Getting Started

Just clone this repo, remove `.git`, run `npm install`, and start work on your own Next.js project.

Then you can follow the usual `create-next-app` instructions, as below.

### Copied from create-next-app

First, run the development server:

```bash
npm run dev
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
