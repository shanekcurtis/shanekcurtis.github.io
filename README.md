
# Shane Curtis's Portfolio Site

This portfolio site is forked from https://brittanychiang.com/, who deserves all of the credit for the beautiful design. I have made modifications to the site to reflect my own personal information, experiences, and projects.
This is a gatsby site hosted by GitHub pages, which uses the gh-pages module to deploy using GitHub's automated deploy actions. 



## Installation & Set up

Prerequisites (macOS)
- node v14.16.0 `nvm install 14.16.0` (I recommend using [NVM - Node Version Manager](https://github.com/nvm-sh/nvm))
- yarn v1.22.22 `npm install yarn@1.22.22`
- gh-pages v5.0.0  `npm install gh-pages@5.0.0`
- gatsby-cli v3.4.1  `npm install gatsby-cli@3.4.1`

Install dependencies with
    ```
    yarn
    ```

## Start the development server
```zsh
  npm start
```

## Build & Run for Production
```zsh
  npm run build
  npm run serve //Loads build onto localhost:9000
```

## Deploy
```zsh
  npm run deploy //Uses config package.json script for calling gatsby & gh-pages deploy operations
```
