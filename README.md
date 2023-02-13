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

Tasks:
- commit your project to your Github account
- add a "styles.css" file and add it to the index.html file (read parcel docs)
- install vscode plugins that make web dev easier