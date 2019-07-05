# gatsby-remark-prismjs

An extended version of official [gatsby-remark-prismjs](https://www.gatsbyjs.org/packages/gatsby-remark-prismjs/) plugin.

## Additions

This version adds a "showLanguage" option to the processed output. Use `showLanguage: true` in gatsby-config.js file for the gatsby-remark-prismjs plugin options.
Setting the option to true adds a `<div class="syntax-lang-name">${languageName}</div>` to the final HTML. You can now style the `syntax-lang-name` class to your liking.