Web Application Skeleton Codebase:
<a href="https://github.com/bromite/bromite/blob/master/LICENSE">
  <img src="https://www.bromite.org/license.svg" alt="GNU GPL v3" title="GNU VPL v3" />
</a> <br>

All development commands are run from the root of the project, from a terminal:

| [terminal]Command         | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies - run at initial setup     |
| `npm run dev`             | Starts local dev server at `localhost:3000`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |



# How I created this web application:

Configuring a new full stack web application using this skeleton:

Configuring environment:
Make sure node.js (npm) is installed
Check Version: [terminal]npm -v	Download: https://nodejs.org/en/download

First, create the template for the webapp (I use astro, you can use another templating service)
[terminal]npm create astro@latest
Name the directory, create an Empty project, and Install dependencies.  
Then you can start developing the webApp with React, Vue, or other prebuilt components

Deploying the WebApplication:
Free website deployment for free use @ http://vercel.com
For commercial use, AWS or _ are better options

Upload project as a public project on GitHub, make sure to create a free account connected GitHub account.
Add a new project- select repository, and click import.
After website builds, there should be a url for the website.

Connecting the webpage to a DNS:
TODO