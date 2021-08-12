# On this site you find info about our [site](https://botscord.site)!


## Npm Package
NPM: https://www.npmjs.com/package/botscord-api

<a href="https://nodei.co/npm/botscord-api/"><img src="https://nodei.co/npm/botscord-api.png"></a>

Install: npm i botscord-api

Usage Javascript


```
const botscord = require("botscord-api");
const DSL = new botscord("TOKEN-HERE", client);

client.on("ready", async () => {
  DSL.serverCount();
  console.log("Server count posted")
})
```

How to get vote count?
```
let hasVote = await DSL.hasVoted("Your-bot-id");
  if(hasVote === true) {
    console.log("Voted")
  } else {
    console.log("Vote please.")
  }
  
  
  let search = await DSL.search("Your-bot-id")
  console.log(search)
  })
```







# Add bot tutorial (only * )

## Get bot/client ID:

Go to [DiscordDevsPortal](https://discord.com/developers/applications)

Press your bot, go to OAuth2 and copy your ClientID


## Get your prefix

If you bot react on !help your prefix is !
If you bot react on .help your prefix is .


## Short description

Fill in the short description of the bot, aka if I have a moderation bot I fill in: A Good moderation bot with 12 commands!


## Long Description

### Html


You can add for example
<iframe src="https://botscord.site" title="BotsCord Site"></iframe>

