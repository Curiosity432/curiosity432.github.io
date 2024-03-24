# Curiosity432 website

## Theme installation
This blog is using [hugo-PaperMod](https://github.com/adityatelange/hugo-PaperMod) a theme of [HUGO](https://gohugo.io/) static site generator. Read the Wiki for more information [hugo-PaperMod - Installation](https://github.com/adityatelange/hugo-PaperMod/wiki/Installation).

## Process to publish the blog

> The method to build this type of websites is called AMstack (Javascript API Markup stack), there is no backend (server-side), all runs on the frontend (client-side). In case you need a database is done via external API.

1. Write the content with a text/code/markdown editor (neovim, vscode, Obsidian.md).

2. Use HUGO as Static Site Generator with a theme to convert notes writted in markdown (an easy markup language) to the web format (HTML, CSS, JS)

3. Use a web hosting to serve and deploy your content
    - Hosting: GitHub
    - Deploying/serving:
      - [Netlify](https://www.netlify.com/) for free hosting of static websites.
      - [Github Pages](https://pages.github.com/): frontend pages of GitHub.
        - a. Deploy the generated site on GitHub repo directory `/ (root)` or `/docs`
        - b. Generate the static site using GitHub Actions workflows. Using Ubuntu server, and a script of node.js.

> If you are creating a web page with the web standard (HTML, CSS, JS) you can deploy directly to the `main` branch and selet GitHub Pages on root directory `/` to autobuild and serve.

