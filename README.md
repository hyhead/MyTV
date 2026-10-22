# LaunchPad

LaunchPad is a static dashboard and can be deployed to Vercel without a build step.

## Deploy to Vercel

1. Push this repository to a Git provider supported by Vercel.
2. In Vercel, create a project and import the repository.
3. Use the **Other** framework preset and leave the build command empty. The included `vercel.json` serves the dashboard at `/`.
4. Deploy.

You can also deploy from this directory with the Vercel CLI using `npx vercel --prod`.

## Data and embedded sites

Tiles and theme preferences are saved in the browser's local storage. They are not shared across browsers or devices. Some sites block being displayed in an embedded frame; those tiles can be opened in a new tab instead.
