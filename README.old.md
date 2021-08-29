# goit-react-hw-05-movies

1. npx create-react-app .
2. npm install --save-dev prettier eslint
3. npx mrm@2 lint-staged
4. edit packege.json

<!-- "lint-staged": {
   "*.{js,jsx}": "eslint --cache --fix",
   "*.{js,jsx,css,scss,md}": "prettier --write"
   } -->

5. npm install --save prop-types

6. @import-normalize; - в файл index.css

7. deploy on Netlify

   7.1 npm install netlify-cli -g
   7.2 netlify login
   7.3 удалить "homepage": "https://Guns1301.github.io/goit-react-hw-03-phonebook",
   7.3 npm run build
   7.4
   7.5 add scripts :
   "predeploy": "npm run build",
   "deploy": "netlify deploy -p",
   7.6 npm run deploy

   7.7 This folder isn't linked to a site yet
   ? What would you like to do? + Create & configure a new site
   ? Team: guns1301's team

   Published

8. npm i axios
9. npm i react-spinners
10. npm i react-toastify
11. npm i @emotion/core
    11.1 npm i @emotion/react
    11.2 npm install --save @emotion/css
12. npm i @material-ui/core
13. npm i @material-ui/lab
