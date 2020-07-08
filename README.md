# Reddinterest | reddi
_Reddinterest_ is a discord bot written in Nodejs that allows servers to monitor subreddits of interest to them. Users with reddinterest priveleges can add keywords to the bot and subreddits that will tell reddi what to look for. When reddi detects a new post to a watched subreddit that matches a user defined keyword, reddi will echo that post the its text channel. This makes for a great way to keep tabs on topics you care about, without having to filter through all the other junk you dont.

### Repository
- **discord.js**

  This repository uses [discord.js](https://discord.js.org/?source=post_page---------------------------#/) for creating a discord bot. For more information on how to set up a discord    bot yourself take a look at this [guide](https://discordjs.guide/). Also see the [documentation](https://discord.js.org/#/docs/main/stable/general/welcome).

- **snoowrap and snoostorm**

  This repository uses the packages [snoowrap](https://www.npmjs.com/package/snoowrap) and [snoostorm](https://www.npmjs.com/package/snoostorm) to interact with the reddit API via node. Take a look at those links for more information.

- **Prettier**

  This repository uses [prettier](https://prettier.io/) to format code. The setting for prettier are contained in the file `.prettierrc.json` in the project root. It is reccomended you use [VS Code](https://code.visualstudio.com/) to work with this repository as this will make setting up prettier easier. For more information on using and setting up prettier with VS code take a look at this [guide](https://glebbahmutov.com/blog/configure-prettier-in-vscode/)