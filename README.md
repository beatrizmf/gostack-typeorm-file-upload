# gostack-typeorm-file-upload

The CSV Finance Balance Importer is an API that simplifies the process of importing finance balance files in CSV format. Users can send a POST request to the API endpoint with their CSV file attached, which is then processed and generates a report detailing balance information. The API only accepts CSV files and can be configured to ignore certain columns, map data to specific fields, or apply custom logic to the data. The API returns reports in JSON format, making it a great choice for developers looking to streamline their finance balance import process.

## Setup

```shell
npm install
```

```shell
npm dev
```

```json
"dependencies": {
    "@types/csv-parse": "^1.2.2",
    "csv-parse": "^4.8.9",
    "dotenv": "^8.2.0",
    "express": "^4.17.1",
    "express-async-errors": "^3.1.1",
    "multer": "^1.4.2",
    "pg": "^8.0.0",
    "reflect-metadata": "^0.1.13",
    "typeorm": "^0.2.24"
  },
  "devDependencies": {
    "@types/express": "4.17.3",
    "@types/express-serve-static-core": "4.17.2",
    "@types/jest": "^25.2.1",
    "@types/multer": "^1.4.2",
    "@types/supertest": "^2.0.8",
    "@typescript-eslint/eslint-plugin": "^2.27.0",
    "@typescript-eslint/parser": "^2.27.0",
    "cross-env": "^7.0.2",
    "eslint": "^6.8.0",
    "eslint-config-airbnb-base": "^14.1.0",
    "eslint-config-prettier": "^6.10.1",
    "eslint-import-resolver-typescript": "^2.0.0",
    "eslint-plugin-import": "^2.20.1",
    "eslint-plugin-prettier": "^3.1.2",
    "jest": "^25.3.0",
    "prettier": "^2.0.4",
    "supertest": "^4.0.2",
    "ts-jest": "^25.3.1",
    "ts-node": "3.3.0",
    "ts-node-dev": "^1.0.0-pre.44",
    "typescript": "^3.8.3"
  }
  ```
