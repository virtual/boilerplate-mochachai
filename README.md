FCC Test Challenge Prototype 
============================

QA with mocha & chai

## Setup

- `npm install` to install dependencies
- `npm run start` to run tests (or `nodemon server.js` if you use nodemon to automatically update)

## Notes

- You can comment out suites within the `tests/*.js` files in order to focus on fixing one test suite at a time.
- Updated node to version 4.7.0 - `"node": "4.7.0"` in package.json to support Heroku
- Use automatic deployment from `gomix` branch on Deploy tab in Heroku