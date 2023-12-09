# Shade

Become The Shade

[![Deploy to Bluemix](https://cloud.ibm.com/devops/setup/deploy/button.png)](https://bluemix.net/deploy?repository=https://github.com/devcheckra1n/Anon-Unblock)
[![Deploy to AWS](https://oneclick.amplifyapp.com/button.svg)](https://console.aws.amazon.com/amplify/home#/deploy?repo=https://github.com/devcheckra1n/Anon-Unblock)
[![Deploy to Cyclic](https://deploy.cyclic.sh/button.svg)](https://deploy.cyclic.sh/)
[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/devcheckra1n/Anon-Unblock)


## Running the website on your computer

1. Install [node.js](http://nodejs.org/)
2. Unzip it
3. Open up a terminal/command line
4. `cd` into the directory
5. Run `npm install` to grab the dependencies.
6. Run `npm start` to start the server. It should spawn a new instance for each CPU core you have.

(Note: running `node app.js` *will not work*. The server code is in the [Gatling](https://npmjs.org/package/gatling)
package, which the `npm start` command calls automatically.)

After that, it will be live on your computer and accessible from your computer at http://localhost:8080/ - accessing it from another computer is beyond the scope of this guide, but it is possible.

## Running the website on ~~Heroku~~/Bluemix/Azure/AWS/etc

This project should be runnable without modification on many cloud providers. Clone/download the code and deploy it, or just click one of the buttons above. (I used to use heroku, but they have since updated changed their policies to not allow it.)

# About the project

The the core of the Shade has been extracted into a [standalone library](https://github.com/devcheckra1n/Anon-Unblock) to make it more flexible, but everything you need to run the website is right here.

This project is released under the terms of the [GNU Affero General Public License version 3](https://www.gnu.org/licenses/agpl-3.0.html).
