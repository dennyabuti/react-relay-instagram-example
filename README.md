# react-relay-instagram-example

![] (http://i.imgur.com/Hqwsxmq.png)

## Getting Started

After [downloading this example](https://github.com/graphcool-examples/react-relay-instagram-example/archive/master.zip) please follow these steps.

### 1. Create an account

To run this example, please create a [graph.cool](http://graph.cool) account and **copy your endpoint**. This shouldn't take longer than a minute. We promise!

![](https://i.gyazo.com/a0fb8e342ec9844e466cd6dc0a27516d.gif)


### 2. Configure app data endpoint

Open `src/app.js` and paste your endpoint to the following line:

```js
Relay.injectNetworkLayer(
  new Relay.DefaultNetworkLayer('https://api.graph.cool/relay/v1/__PROJECT_ID__')
);
```

### 3. Configure build schema endpoint

Set the `GRAPHQL_ENDPOINT` variable by passing it to your npm script.

```sh
GRAPHQL_ENDPOINT=https://api.graph.cool/relay/v1/__PROJECT_ID__ npm start
```

This step is needed in order to support Relay. More info can be found here: [babel-plugin-react-relay](https://github.com/graphcool/babel-plugin-react-relay).


### 4. Run the example

You're done configuring the example application. Please run the following command and open [localhost:3000](http://localhost:3000) in your browser. Have fun exploring! 🎉

```sh
npm install
GRAPHQL_ENDPOINT=https://api.graph.cool/relay/v1/__PROJECT_ID__ npm start
```

### 5. Deploy the example

```sh
npm install -g netlify-cli
netlify deploy
```

or click the deploy button to see it live.

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/graphcool-examples/react-relay-instagram-example)

## Help & Community [![Slack Status](https://slack.graph.cool/badge.svg)](https://slack.graph.cool)

Join our [Slack community](http://slack.graph.cool/) if you run into issues or have questions. We love talking to you!

![](http://i.imgur.com/5RHR6Ku.png)
