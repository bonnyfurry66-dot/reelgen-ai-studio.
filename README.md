# ReelGen AI Studio

This is the first deployable website package for ReelGen.

## Deploy from an Android phone (Samsung Galaxy A17)

1. Download and extract `reelgen-website.zip`.
2. Open GitHub in Chrome and sign in.
3. Tap **+** → **New repository**.
4. Name it `reelgen-ai-studio`, choose **Public** or **Private**, then create it.
5. In the repository, use **Add file** → **Upload files**.
6. Upload the contents of the extracted folder (make sure `index.html` is at the repository root).
7. Commit the files.
8. Open Vercel and sign in with GitHub.
9. Choose **Add New** → **Project**, import `reelgen-ai-studio`, then deploy.
10. Vercel will publish the frontend and provide a website URL.

## Important

The front-end is deployable, but AI generation, story writing, real voice synthesis,
secure user accounts, and cloud video storage will not work until the backend API routes
are implemented and connected to providers. The frontend expects the API routes listed
in `api/README.txt`.

Never paste provider API keys into `index.html` or GitHub. Add secrets only in
Vercel Project Settings → Environment Variables.

## Next build step

Choose the AI video provider and the text/voice provider, then implement the server
routes and connect a database and cloud object storage. Provider usage may require
paid credits; no paid service or transaction is activated by this package.
