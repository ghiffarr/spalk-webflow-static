# Spalk Webflow Static Export

Static Webflow export for https://www.spalk.tv/.

## Deploying to Vercel

1. Create a new Vercel project from this folder.
2. Use the project root as the Vercel root directory.
3. Select the static/other framework preset.
4. Leave the build command empty.
5. Leave the output directory as `.`.
6. Deploy.

`index.html` must stay at the project root. The `css`, `js`, `images`, `documents`, `solutions`, and `industries` folders should remain beside it.

## Vercel Routing

`vercel.json` enables clean URLs, so pages such as `about-us.html` are also available at `/about-us`.

Known missing exported routes:

- `/case-study/infront`
- `/case-study/fiba`
- `/case-study/sky-switzerland`

No placeholder videos or images have been added for missing assets.
