Pre:
- Node via nvm (https://github.com/coreybutler/nvm-windows)
  - prebundles with npm
- VSCode
  - winget install vscode


Steps:
- `npm init `
- `git init`
- `npm install -D parcel`
- edit `package.json` file
- add a "dev" script to start parcel
  ```
  "scripts": {
    "dev": "parcel"
  },
  ```
- read the parcel documentation to learn more about configuration options
- add `"source": "src/index.html",` to your `pacakge.json` file. this tells parcel where the "entry" point file is for your project
- npm run dev

## 13 Feb 2013

Tasks:
- commit your project to your Github account
- add a "styles.css" file and add it to the index.html file (read parcel docs)
- install vscode plugins that make web dev easier
- read more about design systems for example
  - https://polaris.shopify.com
- https://code.visualstudio.com/docs/getstarted/tips-and-tricks
- https://developer.chrome.com/docs/devtools/
- Sass (something like css)
- https://www.w3schools.com/html/html5_semantic_elements.asp
- https://picnicss.com/
- https://getbootstrap.com/docs/5.3/components/buttons/

- add another color
- implement btn variant
- add hover state with transition for the navlinks using the primary color

## 14 Feb

Tools:
- Explore Chrome dev tools
- Explore Lighthouse and the audit capabilities

Terminal:
- Make your terminal more useful
  - oh-my-posh (https://ohmyposh.dev/docs/)
  - posh-git (https://github.com/dahlbyk/posh-git)
  - autocomplete

CSS:
- Explore the concept of a container
- Enable scrollable pages and add smooth scrolling
- Explore CSS flexbox and grid
- Refactor CSS to use scss
- Add different sized buttons
- Implement a ghost button
- Add a hero component to the landing page


Tasks:
- Create a ".section" class to enable:
  - Each section should be 100% of the view height
  - Change it to flex display and make sure content is displayed in the center of the screen
  - Target the h2 element change increase the font size
  - Add a "max-width" to the section so that there is a margin on the left and right of each section.
- Add id's to each section and update the nav links href so that the browser can scroll to each section
- Add smooth scroll to the page to make the sections slide over the screen
- Add a button to toggle the data-theme attibute on the html root. The toggle values are "light" and "dark". Just use plain javascript.