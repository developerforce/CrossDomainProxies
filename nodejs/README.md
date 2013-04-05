### A A simple proxy server to help with Salesforce (forcetk) cross-domain requests ###

If you want to build and test a Salesforce web/mobile app that uses forcetk library, then you need
to setup a proxy server to avoid cross-domain requests. This provides a very simple support for such
requests

#### Setup

1. Install Node.js from <a href="http://nodejs.org" target="_blank">nodejs.org</a>
2. Clone this project and cd into sfproxy
3. Run `npm install` to install dependencies
4. Run `node app.js` to run proxy server.