## Welcome to Web Test
#### **Description**
This web application is intended to test the functionality of the github pages function. 

#### **How I created this repository**
1. Navigate to folder where you want to place app

    `cd ~/Documents/GitHub`
2. Generate application template
    
    `yarn create react-app [app name] --template typescript`

3. Add sass

    `yarn add sass`

4. Add homepage field to package.json. Insert the following line at the top of package.json.

    `"homepage": "https://showar2.github.io/[branch-name]/"`

5. Add gh-pages

    `yarn add gh-pages --save-dev`

6. Add gh-pages scripts to package.json

    `"predeploy": "npm run build",`

    `"deploy": "gh-pages -d build",`

7. Push changes to the main branch. Under Settings/Pages, make sure branch points to "gh-pages" "/[root]"


#### **Commands**
| command | description |
| ----| ----|
| `npm run deploy` | deploys application to web |
| `yarn` | update libraries |
| `yarn start` | run project on local host |



