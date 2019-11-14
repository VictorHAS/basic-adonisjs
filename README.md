# Adonis API application

This is the boilerplate for creating an API server in AdonisJs, it comes pre-configured with.

1. Bodyparser
2. Authentication
3. CORS
4. Lucid ORM
5. Migrations and seeds

## Installing AdonisJs
#### Via AdonisJs CLI
AdonisJs CLI is a command line tool to help you install AdonisJs.

Install it globally via npm like so:

Using npm:
```js
npm i -g @adonisjs/cli
```

Using yarn:
```js
yarn global add @adonisjs/cli
```


## Setup

Use the adonis command to install the blueprint

```bash
adonis new yardstick --api-only
```

or manually clone the repo and then run `npm install`.


## Migrations

Run the following command to run startup migrations.

```js
adonis migration:run
```

## Serving the application

Once the installation process has completed, you can cd into your new application directory and run the following command to start the HTTP Server:
```js
adonis serve --dev
```
This command starts the server on the port defined inside the root .env file.
