# hoodie-app-tracker

> Default Hoodie app

[![Build Status](https://travis-ci.org/clpo13/hoodie-app-tracker.svg?branch=master)](https://travis-ci.org/clpo13/hoodie-app-tracker)
[![Dependency Status](https://david-dm.org/clpo13/hoodie-app-tracker.svg)](https://david-dm.org/clpo13/hoodie-app-tracker)
[![devDependency Status](https://david-dm.org/clpo13/hoodie-app-tracker/dev-status.svg)](https://david-dm.org/clpo13/hoodie-app-tracker#info=devDependencies)

Tracker is a simple Hoodie app, meant to be a starting point to play and build
with Hoodie. Find the repository on [GitHub](https://github.com/clpo13/hoodie-app-tracker).

## Requirements

Tracker needs `node >=4`. To see which version you have installed, run
```
node -v
```

## Setup

```
git clone https://github.com/clpo13/hoodie-app-tracker.git
cd hoodie-app-tracker
npm install --production
```

Start server with

```
npm start
```

### Optional: Setup email for password reset

If you want to use the password reset feature, you must configure an email account
to send out notification, like a Google Mail account. Edit the `.hoodierc` file,
the options are passed to [nodemailer.createTransport()](https://github.com/nodemailer/nodemailer-smtp-transport#usage)

```
cp .hoodierc-example .hoodierc
```

## Deployment

You can find a detailed instruction [here](deployment.md).

## Contribute

`hoodie-app-tracker` is work in progress. The goal is to have a simple
application with very clear and easy to understand HTML / CSS / JS code which
ideally uses no 3rd party code at all, besides the Hoodie client.

If you want to contribute to the frontend assets, you can simply open
the project folder and edit the files in
the [public/](public/) folder.

## Tests

Install devDependencies by running `npm install` without `--production`

```
npm install
```

Then run tests with

```
npm test
```

## Need help or want to help?

It’s best to join our [chat](http://hood.ie/chat/).

## License

[Apache 2.0](http://www.apache.org/licenses/LICENSE-2.0)
