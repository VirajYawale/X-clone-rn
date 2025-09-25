# x-clone-rn

Backend

setup the node js and express js for the backend... cmd: 1. npm init -y (for package.json) 2. npm i express mongoose dotenv cors 3. npm install @clerk/express @arcjet/node @arcjet/inspect
Mobile

Expo is a framework and platform built on top of React Native that makes it much easier to build mobile apps for iOS, Android, and the web with a single codebase.

cmd:

npx create-expo-app@latest . (. means it will initiate the app in the current folder) - ()it give the app folder boilerplate
Backend

setup all the files required

src > server.js
in package.json: "scripts": { "dev": "node --watch src/server.js", "start": "node server.js" },

(we use dev for the development purpose and start to run the app while the deplotment)

in src folder i make the required folders middleware, models, routers, controllers, config and files in it. Also we setup the file gitignore and .env file
in env file

use clerk for authentication url used:
https://dashboard.clerk.com/apps/app_33AkmBnYiOAZ2OWTROxFGdO4LEK/instances/ins_33AkmBarC67WCGU4gjNVLWsybfA/api-keys

https://clerk.com/docs/quickstarts/expo

https://app.arcjet.com/sites/site_01k5zc0sesedt99sh9rg5pdkb2/sdk-configuration?first-install

https://console.cloudinary.com/app/c-b4a26d3e1a355f12348187b8d5b1c4/settings/api-keys