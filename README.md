# Miles

> A SmartThings interface even Chief O'Brien would approve of

**Let's face it**: as great of a home automation platform as SmartThings is, the app user interface *sucks*.

Until now there has been only one main player in the providing an alternative, customizable interface for SmartThings, and that project recently became paid. The ActionTiles team have put in tons of work, and it's hard to fault them for wanting something more tangible in return than the adoration of fellow enthusiasts, but in the process the SmartThings community loses some of the spirit of open collaboration that has made it so strong.

The other option has always been to integrate SmartThings as a simple hardware bridge in some other home automation platform like Home Assistant, and using one of the myriad dashboards available on those platforms. That's great for the hard-core tinkerers, the Geordi LaForges of the home automation world who want to build a master home automation computer out of some isolinear chips, a paperclip, and some string; but what about the middle ground of users who use things like CoRE to leverage their SmartThings Hub in a more powerful, user-friendly way?

## Introducing Miles

Miles is a lightweight, web-based, user-customizeable dashboard/control panel for SmartThings.

The Miles frontend runs in your browser, communicating with SmartThings mostly via [PubNub]() (their free tier should be more than sufficient). If you prefer, there's also a *tiny* server you can host yourself, locally on a always-on machine or Raspberry Pi, or in the cloud.


## Installation Instructions

Coming soon!


## Build Setup

Miles is written in vue.js, for speed and flexibility.

> Miles uses [Yarn]() as its package manager of choice. You can find information on why it's better than NPM for many use cases and how to install it [here]() (we recommend installing it globally via NPM, as silly as that seems).

To get started:

``` bash
# install dependencies
yarn install

# serve with hot reload at localhost:8080
yarn run dev
```

To build for production (with minification):
```bash
yarn build
```

To run tests:
```bash
yarn test

# or run only unit tests
yarn run unit
# or run only e2e tests
npm run e2e
```

For detailed explanation on how things work, checkout the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
