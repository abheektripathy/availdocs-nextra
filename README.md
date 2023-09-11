# Avail Docs

## Adding new docs

Add mdx/md files inside the pages folder to add docs, to have nested docs, create a folder and a md file at the same directory level(which would act like it's index page), and add more mdx files inside.

To have more customisations to the sidebar, you can simply edit the `_meta.json` file.

## Component/Theme Customisations

we can use tailwind to style and create components, and have custom designs for the navbar, index page, plus footer and more, by leveraging nextra's custom theme logic like mentioned [here](https://nextra.site/docs/custom-theme#configure-nextra-to-use-the-theme).

## Having State/Interactive Docs

Since we're using mdx we can have interactive docs, by rendering react components directly inside the mdx files. <br/>
For Example- Checkout [This](https://availdocs-nextra.vercel.app/explorer#component)
