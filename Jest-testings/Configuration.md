# Configuration of Jest for unit testing
## Step 1 Ensure you have node and npm are both installed
node -v
npm -v

# Step 2 - Create a js files
Name it myFile.js
Add the following:
'''
function sum(a, b) {
    return a + b;
  }
  module.exports = sum;
'''
Add a test file and name it myFile.test.js:
'''
const sum = require('./sum');

test('adds 1 + 2 to equal 3', () => {
  expect(sum(1, 2)).toBe(3);
});
'''

## Step 2 - Add a package.json file by running:
npm init -y

## Step 3 - Install jest locally by running:
npm install --save-dev jest

A node_modules folder is created with the jest framework files

## Step 4 - Update the package.json file
In the pakage.json file make the following changes:
'''JSON
{
  "scripts": {
    "test": "jest"
  }
}
'''

## Step 5 - Run the test
run "npm test" or "npm run test"