# boo-bot BETA
## _fka ReduxBot_

boo-bot is a bot that can add RSS feeds to your server and has global-tags around all Discord.


## Features

- RSS Feeds
- Global tags
- Moderation commands

## Built with

boo-bot uses some repositories.
- [node.js] - **discord.js** backend
- [jQuery] - backend


# Add to your server
### RSS
Use the invite: [click here](https://discord.com/api/oauth2/authorize?client_id=1121792358674079805&permissions=274878024705&scope=bot)
Then run this command to add your first RSS channel!
```sh
/rss <yourChannelID> <rssLink>
```
Example:
```sh
/rss channelid:1134957043594309777 rsslink:http://rss.cnn.com/rss/edition_world.rss
```

### Global tags
Implement your global-tags by running these simple commands:
```sh
/addtag name:yourTagName content:your content without any attachments (only links)
/tag name:yourTagName
```
and the bot will respond with "`content`"
