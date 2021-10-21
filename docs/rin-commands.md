# Rin Commands

---
## `.rinhelp`

Provides a list of commands that can be used

**Parameters**: None

## `.rininfo`

Provides basic info for what the bot does.

**Parameters**: None

## `.valid`

Provides some support... This is meant to say you're valid.

**Parameters**:

- keyword/name - usually a name goes better with this

## `.ping`

Pings the bot to obtain lag in ms.

**Parameters**: None

## `.meme`

Performs a search on memes on reddit. Picks from a certain list of words + meme.

**Parameters**: None

## `.transmeme`

Find trans-related memes

**Parameters**:

- keyword - the keyword being used to search reddit via praw

## `.reddit`

Performs a search on reddit.

**Parameters**:

- keyword/subreddit - For subreddit, include the "r/" prefix as well

## `.devartfind`

Browses Deviantart.

**Parameters**:

- keyword - keyword in order to perform a search


## `.devartsearch`

Performs a search on the tags within Deviantart.

**Parameters**:

- keyword - Keyword in order to search. Will look up results that are similar to the keyword. For example, if I typed in "anime" as the keyword, it would give "animeart", "animegirls", etc


## `.image`

Image Scraper for Deviantart.

**Parameters**:

- keyword - the keyword for the image scraper to work

## `.invite`

Makes an invite for the server

**Parameters**: None

## `.botinfo`

Shows Bot info.

**Parameters**: None

## `.translate`

Translates a string or message.

**Parameters**: None. Requires input after running cmd.

## `.botgrowth`

Shows tips on how to grow your server with a bot.

**Parameters**: None

## `.prune`

Prunes any spare servers that the bot is not used in. This is an admin command.

**Parameters**: None

## `.broadcast`

Performs a broadcast using the Global chat system. Use with caution.

**Parameters**: None. Requires input after running the cmd.

## `.rtupdatestatus`

Updates the status of the Twitter User.

**Parameters**:

- update message - The message you want to send to update the status on your twitter account.

## `.rtsearch`

Performs a search on Twitter.

**Parameters**:

- keyword - Used to determine the search

## `.pinger`

Pings everyone on the server with a message

**Parameters**:

- amount of pings - whole number
- keyword - the message you want to send. This needs to be wrapped in "" marks. The message should look like this: "This is an message" (basically wrap it so it's a str instead)

## `.iguserinfo`

Finds and extracts user info for that account

**Parameters**:

- client id - *Client ID of the user 

*Note: In order to find the Client ID, you will need to use [this](https://codeofaninja.com/tools/find-instagram-user-id/) website, and input the username you want. Then the number is labeled under "profilePage".

## `.igusersearch`

Finds users with that username. Will only show the first result of each search.

**Parameters**:

- keyword - The user you are searching for

## `.igtaginfo` 

Extracts info about the tag

**Parameters**:

- keyword - The tag that you want to search for

## `.igusernamecheck` 

Checks if the Instagram username is taken or not

**Parameters**:

- keyword - The username that you want to check

## `.iguserfeed`

Shows the first post of the selected user's profile feed

**Parameters**:

- Client ID - Requires Client ID in order to work

## `.jisho`

Searches up Japanese terms and words along with the English meaning. Uses [Jisho](https://jisho.org/) in order to fetch the data. (Uses the API in order to do so) and JMDict to process the kanji, hiragana, and katakana

**Parameters**:

- keyword - The term that you want to search for. Can be in both Japanese and English

## `.serverinfo`

Shows server info

**Parameters**: None

## `.clear`

Clears number of messages specified from the channel that the command was called in

**Parameters**: 

- keyword - The number of messages to clear 

## `.javamcsrv`

Provides info about a minecraft server (java) of your choice

**Parameters**: 

- keyword - The server's domain name 

## `.bedrockmcsrv` 

Provides info about a minecraft server (bedrock) of your choice

**Parameters**: 

- keyword - The server's domain name 

## `.waifu`

Randomly selects a waifu for you

**Parameters**: None

# `.waifupics` 

Randomly gives you a waifu using WaifuPic's API

**Parameters**: None

# `.mute`

Mutes the specified user. 

**Parameters**: keyword - the user that you wish to mute


# `.advice`

Returns some advice from Advice Slip

**Parameters**: None

