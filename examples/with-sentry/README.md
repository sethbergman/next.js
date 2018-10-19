[![Deploy to now](https://deploy.now.sh/static/button.svg)](https://deploy.now.sh/?repo=https://github.com/zeit/next.js/tree/master/examples/with-sentry)

# Sentry example

## How to use

### Using `create-next-app`

Execute [`create-next-app`](https://github.com/segmentio/create-next-app) with [Yarn](https://yarnpkg.com/lang/en/docs/cli/create/) or [npx](https://github.com/zkat/npx#readme) to bootstrap the example:

```bash
npx create-next-app --example with-sentry with-sentry-app
# or
yarn create next-app --example with-sentry with-sentry-app
```

### Download manually

Download the example:

Install it and run:

**npm**
```bash
npm install
npm run dev
```

**yarn**
```bash
yarn
yarn dev
```

**Deploy it to the cloud with [now](https://zeit.co/now) ([download](https://zeit.co/download))**

```bash
now
```

## About example

This example shows you how to add Sentry to catch errors in next.js.

You will need a Sentry DSN for your project. You can get it from the Settings of your Project in **Client Keys (DSN)**. Copy the string labeled **DSN (Public)**.
Note that if you are using a custom server, logging is available for common platforms in the Sentry Docs: https://docs.sentry.io/platforms
