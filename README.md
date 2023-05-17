# info-aarp
NextJS app for AARP info.aarp.org domain

## Getting Started

First, run the development server:

Install dependencies
```
npm install
```

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000/work/aarp-memd22-pyp](http://localhost:3000/work/aarp-memd22-pyp) with your browser to see the result.

The pages are developed under pages/work folder.
You can start editing the page by modifying `pages/work/*.js`. The page auto-updates as you edit the file.

## Docker execution

Build the docker image:
```
docker build -t hpc/info-aarp .
```

Execute the docker image:
```
docker run -it -p 3000:3000 --rm --name info-aarp-1 hpc/info-aarp
```

## API routes

[API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:3000/api/hello](http://localhost:3000/api/hello). This endpoint can be edited in `pages/api/hello.js`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

