---
title: Hosting React on GH Pages
draft: false
tags:
  - github
  - react
  - hosting
---

### react-gh-pages

I love building quick static sites in React for small one-off projects, and I love hosting them publicly for others to interact with them. What I don't love though, is having to pay to host free hobby sites.

One of the greatest npm libraries I've found for this is [react-gh-pages](https://github.com/gitname/react-gh-pages).

It's ridiculously easy to use; however, the README is a _tiny bit_ outdated, at least for Vite, so I wanted to write up a quick guide as a note to self (and others!) for the process I've found that works.


### Process

1. Create your React Vite App As Normal
2. Run the following command: `npm install gh-pages --save-dev`
3. Open up your `package.json` and add the following line: `https://{username}.github.io/{repo-name}`
4. In the `scripts` section of `package.json` add the following lines:

    ```
    "predeploy": "npm run build",
    "deploy": "gh-pages -d dist"
    ```

6. In your `vite.config.ts`, add `base: /{repo-name}/` to your `defineConfig` arguments
7. Add your remote reository git remote add origin https://github.com/{username}/{repo-name}.git and ensure this aligns with step 3.
8. Run `npm run deploy`
9. Your remote repository should now have a `gh-pages` branch. Open your GH Repo Settings and open the Pages settings. Configure your Build and deployment settings like so:
![GH Pages Settings](_assets/gh-pages-settings.png)
10. Navigate to `https://{username}.github.io/{repo-name}` and you should now have a deployed static site!