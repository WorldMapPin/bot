# worldmappin-bot
Stream the blockchain and process worldmappin activities

### How to Use

- Clone this repository
- Make sure you have latest LTS or greater version of Node JS installed
- Go inside the cloned folder and type `npm install`
- Rename `.settings.json.example` to `settings.json` and add your Upbit api and secret keys
- To start the app, type `npm start`

By default, the monitoring process is run every minute.
You can easily change the claim interval in the `settings.json` configuration file.

###
To run the app continuously in background, you can use use [PM2](https://pm2.io/).
Generate `ecosystem.config.js` file with `pm2 init` command.

When you are done start the bot with following command.

`pm2 start ecosystem.config.js --env production`

### Technologies
- Node JS

### Contributing

Feel free to fork the repo and make changes. If you have any suggestions or want to report bugs, please create an issue.
