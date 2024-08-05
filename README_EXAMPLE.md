# Name of the repository
A little description of what it does 

## Table of Contents

- [Setup](#setup)
- [Getting Started](#getting-started)
- [Development Mode/Local dev](#development-mode)
- [Environment Variables](#environment-variables)
- [Testing](#testing)
- [Database](#database)
- [Service Specifics](#service-specifics)

## Setup
This section will cover prerequisites along with the versions for this service.
<!-- a little summary of the bellow and or any specifics/unique -->

### Prerequisites
Ideally, a list of required tools and frameworks to run the service:
- npm 10.0.0+
- node 20.0.0+
<!-- please make sure that tools and framework versions are defined along with links to the installation -->

## Getting started
This should be focused on what it takes to get the service up and running along with all dependencies and env configurations
<!-- 
- First, ensure you're running the correct version of npm, then install dependencies using:
```sh
npm install
```

- Bringing up dependency services. Most of the times we would use docker e.g: 
```sh
docker compose up -d
```

- Database migrations if needed for the service e.g:
```sh
# run database migrations
npm run db:migrate
# followed by dabatase seeding
npm run db:seed
```

- Any other required operations for the service to function e.g: process flows
```sh
# installs process flows
npm run flows 

# builds ts and tsoa
npm run build
```

- In some cases we would need to run some scripts to be able to run service so please cover that as well e.g:`
```sh
# this script imports DIDs from local .env file
./scripts/import.sh
```
-->


## Development mode
In order to run the service in development mode, please follow the instructions below.
<!-- cover in detail what it takes to run this service locally including environment configuration -->
- Environmental variables that are required by the service
<!-- For example: create .env file and explain what variables are needed and where to retrieve the values, it can be a person or a tool
Make sure that .env file contains the below variables:
EXTERNAL_API_KEY=some-api-key
LOCAL_USER=username
-->
- Ither operations required by the service to start in development mode
- Specifics like importing storybook components
- If we have some seeds with regard to the development mode
- If there are multiple scenarios. e.g. environmental persona and multi-persona, please cover both in separate paragraphs

## Environment variables
This is the list of all environment variables
<!-- A short description of environment variables, if there are any unique cases please cover and mention where to retrieve the values -->
- Table of environemnt variables as per the below example:
- There are multiple tools for helping to automaticallt generate a markdown table [one of the tools](https://www.tablesgenerator.com/markdown_tables)


| variable              | required |      default      | description                                                                          |
| :-------------------- | :------: | :---------------: | :----------------------------------------------------------------------------------- |
| EXTERNAL_API_KEY      |    Y     |         -         |  An API key of external service                                                      |
| LOG_LEVEL             |    N     |      `info`       | Logging level. Valid values are [`trace`, `debug`, `info`, `warn`, `error`, `fatal`] |
| PORT                  |    N     |       `80`        | Port on which the service will listen                                                |
| API_DOCS_FILE_PATH    |    N     | `./api-docs.json` | Location of the api-docs file on the filesystem                                      |
| API_PUBLIC_URL_PREFIX |    N     |        ``         | Public prefix to prepend for accessing api-docs                                      |

## Testing
Please cover all test we are using for this repository. Each should have its own section.
<!-- tooling that we use and types of test we do e.g: cypress, e2e, mocha, jest and etc -->
<!-- usage in CI/CD e.g. github checks -->
<!-- fixtures and where they are stored and in what format e.g. JSON, .ts, .js, etc -->
<!-- helpers and mock services, how they structured -->

<!-- if service does not use any of the below tests, please remove this paragraph -->

### Unit Testing
In this paragraph mention how UNIT tests are structured and how to run.g: all Unit tests should be under `src/` folder and follow the below format
```sh
./src/controllers/health/__tests__/health.test.ts
``` 
Unit tests can be executed by running:
```sh
npm run test:unit
```

### Integration Testing
Mention the structure of the integration tests and how to execute them e.g: All integration tests will be at the root level of the repository in `tests/` folder. Fixtures for integration should not be mixed with UNIT test ones and placed inside `tests/fixtures` folder, preferred format if needed, e.g. JSON or other. Integration tests can be executed by running:
Integration tests can be executed by running:
```sh
npm run test:integration
```

### E2E Testing
If this repository has any E2E test suites, then please describe it using the same pattern as for unit/integration tests, otherwise remove this section.

### UI Testing
Most services will not have UI testing, so in that case please remove this paragraph.
<!-- please find an example of cypress UI testing below -->
<!-- Configuration e.g. Cypress:
#### configuration `/cypress.config.js`
```js
  e2e: {
    supportFile: false,
    specPattern: 'cypress/ui/*.spec.js',
    baseUrl: 'http://localhost:3000',
  },
  component: {
    devServer: {
      framework: 'react',
      bundler: 'webpack',
    },
  },
```
execution of UI test suites:
```sh
# running using cypress control panel
npx cypress open-ct

# running in the background
npx cypress run
```
-->

## Database
<!-- If there is no database, then please remove this section, otherwise please cover the below bullet points: -->
<!-- In most cases we would use knex/PSQL -->
- Database migrations how to run and where they are stored
<!-- Seeding is a fairly new practise so not every service will have it, but if it does mentioned where seeds are located and what they are for e.g. populating query table -->
- database seeds if there are multiple then explain what is it for
<!-- If we have methods for resetting the database, please cover them, it can also be a script -->
- Resetting the database e.g: any commands like `npm run db:reset`

## Service Specifics
In this section please cover all repository specifics such as `scripts` or API specifications

- Any scripts that are relevant for setting up / configuration of the service
- API specification, please refer to the examples below
- Other relevant unique configurations
<!-- 
### Scripts
If service uses scripts please cover in a detail here.
In order to form connection you would need to import DIDs that are saved in .env local file (should be mentioned in the previous paragraph). 
#### ./scripts/<name>.sh 

- A short description about each
- Provide some examples
- Does it take any arguments

### API specification
If service exposes some endpoints please cover them in a bit more detail here.
<!-- #### GET /members - The address parameter identifies the user running this process, and the alias representing a more friendly name version of this. The default value of the latter is null, and is optionally set.
```sh
[
  {
    "address": "5GrwvaEF5zXb26Fz9rcQpDWS57CtERHpNehXCPcNoHGKutQY",
    "alias": "ALICE"
  }
]
```

#### PUT /members/:address - The address parameter identifies the user running this process, and the alias representing a more friendly name version of this. The default value of the latter is null, and is optionally set.
```sh
{
  "address": "5GrwvaEF5zXb26Fz9rcQpDWS57CtERHpNehXCPcNoHGKutQY",
  "alias": "ALICE_UPDATED"
}
```
otherwise remove this section.

if it uses TSOA/Swagger, then explain how to access it and mention that it's a swagger interface with the URL e.g: 
Once running, the API is available at http://localhost:3000/api/docs
-->
