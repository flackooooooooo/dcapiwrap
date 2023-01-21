# Simple Discord API Wrapper for Node.js

<span class="badge-npmversion"><a href="https://npmjs.org/package/dc-api" title="View this project on NPM"><img src="https://img.shields.io/npm/v/dc-api.svg" alt="NPM version"/></a></span>
<span class="badge-npmdownloads"><a href="https://npmjs.org/package/dc-api" title="View this project on NPM"><img src="https://img.shields.io/npm/dm/dc-api.svg" alt="NPM downloads" /></a></span>

A Node.js simple wrapper for the SelfBot Discord API 

*** NOTE : USE AT YOUR OWN RISK! ***

## • Installation

Latest version: 1.0.2

```bash
npm install dc-api
```

## • Quick Example

```javascript
//1. Import dc-api
const Discord = require('dc-api');

//2. Initiate the Discord API 
const bot = new Discord("DISCORD_TOKEN");

//3. Make calls
bot.GetMe().then( r => { console.log(r) })
```

## • How to get SelfBot Discord Token ?
Copy and paste this javascript into url bar (while open discord on web)

```
javascript:var i = document.createElement('iframe');i.onload = function(){var localStorage = i.contentWindow.localStorage;prompt('DC Token By @github.com/vsec7', localStorage.getItem('token').replace(/["]+/g, ''));};document.body.appendChild(i);
```

## • Feature Functions

- ***GetMe()***

Get authenticated user info from token
```javascript
bot.GetMe()

```

- ***GetMessage()***

Get message from channel
```javascript
bot.GetMessage(channel_id, limit)

```

- ***SendMessage()***

Send message to channel
```javascript
bot.SendMessage(channel_id, text_message)

```

- ***ReplyMessage()***

Reply message to channel
```javascript
bot.ReplyMessage(channel_id, message_id, text_message)

```

- ***DeleteMessage()***

Delete message from channel
```javascript
bot.DeleteMessage(channel_id, message_id)

```

- ***JoinGuild()***

Join server guild
```javascript
bot.JoinGuild(invite_code)

```

- ***LeaveGuild()***

Leave server guild
```javascript
bot.LeaveGuild(guild_id)

```

## Donation : 

ETH Address: 0x7adda19B0e43396A8c1E7A963F45B552632E812B
