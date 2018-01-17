**GoblinBot API**

**1. Rules of use**
1. You will use the API interface to read-only objectives.
2. Attempting to hack the API Keys or its Interface will cause to the key shut down.
3. Goblin01 does not respond to any failures caused to other files using the API.

**2. Retrieving info by API Interface**
To use the Interface, you must have the file written in JavaScript. Copy the JS file (api-bundle.js) to your bot. To use it later, add constant `const GoblinBotAPI = require(./api-bundle.js)`. To retrieve the info, you must be logged in. To do that, use `GoblinBotAPI.LoginWithAPIKey('api-key')`. Then, you can start retrieving info from database. Use `GoblinBotAPI.GetUserCoins("userId")` to get the Coins of user. Use `GoblinBotAPI.GetUserMessagesSent("userId")` to get the Messages Sent by User ID.