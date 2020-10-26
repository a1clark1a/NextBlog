# Next.js/SanityStudio Blog

## Live: https://nextblogtest.vercel.app/

```

# Install the Sanity command line interface

~/

> npm i -g @sanity/cli

# Initiate your own project in the studio folder

~/this-blog/studio

> sanity init

# Add a CORS-origin rule to allow the frontend to request data

~/this-blog/studio

> sanity cors add http://localhost:3000 --no-credentials

# Insert the projectId and dataset name from Sanity in client.js

~/this-blog/web

> nano client.js

# Install frontend dependencies

~/this-blog/web

> npm install

# Run Next.js in development mode

~/this-blog/web

> npm run dev

```
