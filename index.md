# Guides XiosVeganzy Development

**Hai teman2 ini adalah GitHub Repository Guide resmi dari _XiosVeganzy Repository_
maka kalian bisa membaca disini peraturan maupun fitur2 dari server kami ini....**

## Fitur / Feature

- Bots Moosic
- Administration
- Anti BadWords
- AFK Channel
- Town Hall Channel
- Self Roles
- Bot Channel

---------------------------

## Documentation's

**We support Docs discord.js**

```js

const Discord = require("discord.js")
const client = new Discord.Client({disableEveryone: true}) // You can select `true` or `false`

// Listener : Events

client.on("ready", async () => {

console.log("I am Ready")
client.user.setActivity("Your Games", {

type : "PLAYING" // `PLAYING`,`LISTENING`,`WATCHING`,`STREAMING`
})

})

client.on("message", async function (msg) {

if (msg.content.startsWith("hi")) {
msg.channel.send("Hello !")
}
})


client.login("SECRET TOKEN")
```


**Coming Soon**
