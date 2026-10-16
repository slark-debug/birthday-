# Happy Birthday

A self-contained static birthday website. No build step or dependencies are
required.

## Deploy

Publish the repository root as the site's document root. The host will serve
`index.html` as the home page.

- **GitHub Pages:** In the repository, open **Settings → Pages**, choose
  **Deploy from a branch**, select the branch containing this site and the
  `/ (root)` folder, then save.
- **Netlify:** Import the repository and leave the build command blank and the
  publish directory as `.`.
- **Vercel:** Import the repository, select **Other** as the framework preset,
  and leave the build command blank and the output directory as `.`.

The page is also customizable with a name query parameter, for example
`/?name=Sam`.
