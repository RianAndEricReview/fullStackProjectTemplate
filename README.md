# fullStackProjectTemplate
*Basic template for starting new full stack projects built with:*

* Server: Express

* Database: Postgres

* ORM: Sequelize

* Frontend: React and Redux

## Initialization --> 

* Create a local project directory and git init

* Then run the following commands:

  * git remote add ******** https://github.com/RianAndEricReview/fullStackProjectTemplate.git 

  * git fetch ********

  * git merge ********/master

  NOTE: (******** is the template branch name you choose)

* Create a new Github repository and follow instructions for 'create from existing repository'

## Setup -->

To use this template:

* Update project name and description in package.json

* Change the project title in HTML <head>

* npm install or yarn install

* Create two postgres databases: one for production and a -test version for development

* Update database name in /server/db/db.js

* Update test-database name in /package.json

* Rename secrets.js in the project root to be localSecrets.js: this file is .gitignore'd, and will only be required in your development environment

* Delete secrets.js file from your GitHub directory

* Template is currently set up to use google OAuth using your client Id and client secret from Google. Your localSecrets file should contain:

  -process.env.GOOGLE_CLIENT_ID = 'Add your id here'

  -process.env.GOOGLE_CLIENT_SECRET = 'add your secret here'

  -process.env.GOOGLE_CALLBACK = '/auth/google/callback'

  * You can get them here: https://console.developers.google.com/apis/credentials

* Create your own Favicon to replace the placeholder


## Start -->

* npm run start-dev will run in development mode

* You can npm run start-server and npm run build-client to run the server and/or webpack separately.

* npm test will run all frontend and backend sample tests. If you update or add to the test file
structure, you will need to update the test script to match

