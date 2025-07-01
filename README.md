# API-Project-using-Unit-testing-and-integration-testing


Dependencies to Install..
(npm install --save-dev jest supertest mongodb-memory-server @types/jest)

Also update package.json:
(
    "scripts": {
      "test": "jest --coverage"
    }
)

Setup: jest.config.js

// jest.config.js
module.exports = {
  testEnvironment: "node",
  coveragePathIgnorePatterns: ["/node_modules/", "/__tests__/utils/"],
};


Folder Structure Update

__tests__/
├── unit/
│   └── taskModel.test.js
├── integration/
│   └── taskRoutes.test.js

