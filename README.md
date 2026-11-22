# `recipes.crisbarreiro.com`

This public repository is the GitHub Pages entry site for the English recipe address. It is not
the recipe application and does not contain the recipe collection.

The private [`Recipes`](https://github.com/CrisBarreiro/Recipes) repository owns the recipes and
the protected Cloudflare Pages app at `recipes-app.crisbarreiro.com`. This repository exists so
`recipes.crisbarreiro.com` can remain a public, non-Cloudflare entry point. Its page keeps the
browser on this hostname while embedding the protected app in a full-page iframe.

The source of truth is `Recipes/entry-pages/recipes/`. Changes are normally published here by
the `Sync public entry pages` workflow in the private repository. GitHub Pages uses this repo's
`CNAME`, `index.html`, `404.html`, and `roll.svg` files.
