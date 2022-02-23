## How to use It 
# we Have to add Bootstarp CDN link in index.html 
` <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.6.1/dist/css/bootstrap.min.css" integrity="sha384-zCbKRCUGaJDkqS1kPbPd7TveP5iyJE0EjAuZQTgFLD2ylzuqKfdKlfG/eSrtxUkn" crossorigin="anonymous">
   `
 **Note: This is our tag of npm package**
 `<Main/>`

`import {Main} from  'chalk-iriaresearch'`

`import data from '../node_modules/chalk-iriaresearch/dist/componants/data.json'`

`function App() {`
 
  `return (`

    `<>`

      `<div>`

       `<Main

          props={

            (data.content = {

              SERVICE_API: " ",

              FOGOT_PASSWORD: "",

              UPDATE_PASSWORD: "",

              LOGIN_API: "",

              SITE_LOGO: "",

              GOOGLE_RECAPTCH_ID: "",

              ISCAPTCHER_ENABLED: "",

              HEADER_BG_COLOR: "",

              FOOTER_BG_COLOR: "",

              FOOTER_FONT_COLOR: "",

              BODY_BG_COLOR: "",

              BODY_FONT_COLOR: "",

              CONTACT_API: "",

              PROVIDER: "",

              PORTALNAME: "",

              APP_NAME: "",

              APP_NAME_SH: "",

              ABOUT_US: "",

              ABOUT_US_ISENABLED: "",

              CONTACT_US: "",

              CONTACT_US_ISENABLED: "",

              NAME: "",

              PRIVACY_POLICY: "",

              PRIVACY_POLICY_ISENABLED: "",

              PRIVACY_POLICY_LINK: "",

              TERMS_AND_CONDITIONS: "",

              TERMS_AND_CONDITIONS_ISENABLED: "",

              TERMS_AND_CONDITIONS_LINK:"",

              ABOUT_US_CONTENT:  "",

            })

          }

       />`
      `</div>`
    `</>`
  `);`
`}`
`export default App;`

### Thses are Our standard parameters to change the data

`
data.content = {

              SERVICE_API: " ",

              FOGOT_PASSWORD: "",

              UPDATE_PASSWORD: "",

              LOGIN_API: "",

              SITE_LOGO: "",

              GOOGLE_RECAPTCH_ID: "",

              ISCAPTCHER_ENABLED: "",

              HEADER_BG_COLOR: "",

              FOOTER_BG_COLOR: "",

              FOOTER_FONT_COLOR: "",

              BODY_BG_COLOR: "",

              BODY_FONT_COLOR: "",

              CONTACT_API: "",

              PROVIDER: "",

              PORTALNAME: "",

              APP_NAME: "",

              APP_NAME_SH: "",

              ABOUT_US: "",

              ABOUT_US_ISENABLED: "",

              CONTACT_US: "",

              CONTACT_US_ISENABLED: "",

              NAME: "",

              PRIVACY_POLICY: "",

              PRIVACY_POLICY_ISENABLED: "",

              PRIVACY_POLICY_LINK: "",
              
              TERMS_AND_CONDITIONS: "",

              TERMS_AND_CONDITIONS_ISENABLED: "",

              TERMS_AND_CONDITIONS_LINK:"",

              ABOUT_US_CONTENT:  "",

 ##  If there is cjs.js error
  run this command in terminal
  `npm install core-js --save `
