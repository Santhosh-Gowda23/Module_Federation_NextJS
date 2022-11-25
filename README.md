# Module_Federation_NextJS

Step: 1
open /home && npm i && npm run dev
open /shop && npm i && npm run dev

Validate: 

Footer and Header components from Home project are exposed to SHOP project

Code snippet : 
        exposes: {
          "./footer": "./components/Footer.js",
          "./header": "./components/Header.js",
        },


Catalog page from SHOP is exposed to HOME 

Code snippet : 
     extraOptions: {
          exposePages: true,
        }
