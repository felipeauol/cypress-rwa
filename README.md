# cypress-rwa

Docker setup for Cypress.io's [real world application](https://github.com/cypress-io/cypress-realworld-app) which I use for experimenting with different test automation techniques. This app is developed and maintained by Cypress.io.

## Usage

Start the application:

```sh
docker run -d -p 3000-3001:3000-3001/tcp felipeauol/cypress-rwa
```

You can access the application at localhost:3000 and log in with any of the example users (`data/database.json`). The default password is `s3cret`
