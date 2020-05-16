# SheetySite [Free Version]

This is a Gatsby template for creating a website based on Google sheets.

## Getting Started 🚀

### Pre-setup Requirements

1. Install [NodeJs](https://nodejs.org/en/download/)
2. Install [Yarn](https://classic.yarnpkg.com/en/docs/install/#mac-stable)
3. Create [Google Sheets API key](https://developers.google.com/sheets/api/guides/authorizing#APIKey)

### Preparing the Project
1. Download this project
2. Run `yarn install` to download dependencies
3. Make a copy of the [google sheets template](https://docs.google.com/spreadsheets/d/1S-S1dzVsPlbYtYTq_jiXCcVYKf75wFlGxB2fKkdVc7w/edit#gid=1818216905)
4. Fill in the google sheets with the site's data and item listings details
   - Ensure to not leave any fields empty. Write `nil` to indicate no value instead

### Running on Dev Environment

1. Create `.env.development` on the project root
   - Include `GATSBY_GOOGLE_CREDENTIALS`=Google-Sheets-Api-Key-Here
   - Include `GATSBY_SHEET_ID`=Google-Sheets-Id-Here
      - _Where is the [Google Sheets Id](https://developers.google.com/sheets/api/guides/concepts#spreadsheet_id)?_

2. Run `yarn start`
   - Your site will run at `http://localhost:8000`
   - You graphiql will run at`http://localhost:8000/___graphql`

### Running on Prod Environment
1. Create `.env.production` on the project root
   - Include `GATSBY_GOOGLE_CREDENTIALS`=Google-Sheets-Api-Key-Here
   - Include `GATSBY_SHEET_ID`=Google-Sheets-Id-Here
      - _Where is the [Google Sheets Id](https://developers.google.com/sheets/api/guides/concepts#spreadsheet_id)?_
2. Run `yarn build`
3. Run `yarn serve`
   - Your site will run at `http://localhost:9000`


## Underlying Tech

- Typescript
- TailwindCSS
- Sheets API

The following setup have been configured in this project:

- Dark Mode
- Social Share
- SEO
- PWA and offline capabilities
- Site metadata
- eslint & prettier
- husky

## TODO
SheetySite - Free Dev Version
- [ ] Build custom google sheets plugin that is more flexible
- [ ] Back to top button
- [ ] Write tests

SheetySite - Premium Dev Version
- [ ] Create layout options
- [ ] Add option for Google Analytics in [google sheets template](https://docs.google.com/spreadsheets/d/1S-S1dzVsPlbYtYTq_jiXCcVYKf75wFlGxB2fKkdVc7w/edit#gid=1818216905)
- [ ] Add option for site's SEO metadata in [google sheets template](https://docs.google.com/spreadsheets/d/1S-S1dzVsPlbYtYTq_jiXCcVYKf75wFlGxB2fKkdVc7w/edit#gid=1818216905)
- [ ] Add option to remove SheetySite branding

SheetySite - Consumer Version
- [ ] Auto build and deploy directly via Google Sheets
- [ ] Build landing page to explain SheetySite
- [ ] Create consumer-friendly explainer material on how to use SheetySite


## What's inside? 🧐

A quick look at the top-level files and directories you'll see in a Gatsby project.

    .
    ├── node_modules
    ├── src
    ├── static
    ├── .gitignore
    ├── .eslintrc.js
    ├── .prettierrc.js
    ├── gatsby-browser.js
    ├── gatsby-config.js
    ├── LICENSE
    ├── yarn-lock.json
    ├── package.json
    ├── tailwind.config.js
    ├── postcss.config.js
    └── README.md
