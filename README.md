*For initial setup and documentation on utilizing the original template, follow the instructions found at this [repository](https://github.com/LekoArts/gatsby-starter-portfolio-cara). Additionally, [this documentation from Gatsby](https://www.gatsbyjs.com/docs/how-to/previews-deploys-hosting/how-gatsby-works-with-github-pages/#deploying-to-a-github-pages-subdomain-at-githubio) may prove to be very useful.*

# Deploying Gatsby Site to GitHub Pages
1. Add the following line to "scripts" in your package.json file:
```
"deploy": "gatsby build && gh-pages -d public -b main",
```
2. Change your default branch (which should be titled `username/username.github.io`) to something else apart from `main`.
3. Use the `main` branch for deployment by running
```
npm run deploy
```
4. Optionally, store your source code in a separate branch or repository.
