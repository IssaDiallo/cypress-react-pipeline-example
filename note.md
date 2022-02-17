# CYPRESS notes

npm install cypress --save-dev

npx cypress open
npx cypress run

# Install packages
npm install start-server-and-test --save-dev

# Then add following in package.json{}
   "cypress-run": "cypress run",
    "int-test": "start-server-and-test next http://localhost:3000 cypress-run"

# Then run
npm run int-test 