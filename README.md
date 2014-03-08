Fun Bot
=======

A script which is used for [Plug.dj](http://plug.dj/communities/)

I don't mind you guys using this script just long as nothing is to be changed on it.

Permission to change anything on this script, You can always contact the author at
[Plug Lounge](http://goo.gl/cMMMc1)
If there happen to be a bug or problem with the bot you can report issue [HERE](https://github.com/DJ-Neon05/Fun-Bot/issues). I'll work on it ASAP! Thanks :)

##### Fun bot version 1.0.49

You customize this bot script once you fork it.
How to function it? scroll down [HERE](https://github.com/DJ-Neon05/Fun-Bot#installing-bot)

---
## What can this bot do? ##

###- Bot Commands
- Bot commands are mainly to instruct the bot
  - Admins of the bot can also use the moderators commands
      - Helpful for moderating the room.
  - While using `.commands` you can also instruct bot to show it's commands to other users. By simply Mentioning the user. `example 1`
  
`commands`

```
.reward | .reload | .die | .addsong | .flipcoin | .catfact | .dogfact | .hug | 
.8ball | .fortune | .songlink | .download | .help | .whywoot | .whymeh | .props | 
.votes | .woot | .meh | .skip | .say | .version | .userstats | .mystats | .source | .status
```
`example 1`
```
#Tools: .commands @Neon
#plugbot: @Neon My commands are ..[commands]..
```

- There some commands that Mention is included!
- Here are the commands below that are required for mentions

`example 2`
```
#JordanTheGuy: .reward @USER
#Plugbot: @USER, JordanTheGuy has rewarded you with a blueberry muffin. Enjoy!
```
- More commands will be available soon!

--
###- Filter Chat
- There is only two chat filters (for now).
- `Begger Filter` can be Enable/Disable by using command `.tbf` This will allow bot to moderate Fan begging in chat [delete fan begging] `example 1`
      - Bot can only do this process if bot has a staff rank.

`example 1`
```
[#Neon: Fan me] = [message deleted]
#Plugbot: Are you serious @Neon?
```
- `Command Filter` Allows bot to delete commands if a user sends out a command to chat.
  - To Enable/Disable Command Filter type `.tcf`

--
###- Gives rewards (Fun Command)


--
###- Gives current songlink


--
###- Limits songs length


--
###- Block Songs/Artist


--
###- Helps put up link


--
###- Greets the Joiners


--
###- Current Music/video Link
  - If `.songlink` It'll instruct bot to give the current playing video/song URL to chat.
    - Imagine provided with can be found [HERE](http://i1328.photobucket.com/albums/w536/Tawi_Bien/songlink_zps934f6316.png?t=1394283093)
  - An example is given below `example 1`

`example 1`
```JavaScript
#Dark: .songlink
#Plugbot: @Dark 'http://youtu.be/R2N16TDszf8'
```
--
###- Remove Video/Audio/Audience
- When the script is being function bot can automatically remove video screen/audio in order for your pc to run faster!
  - This can allow your computer to run extra faster due to low cpu that is already being used.
  - An example screenshot [HERE](http://i1328.photobucket.com/albums/w536/Tawi_Bien/funbot_zpse09a0525.png)
        - You can toggle CPU through a various commands
  - CPU can be activated if moderators type `.die` 
        - Example below `example1`

```
#Neon: .die
#Plugbot: [Re-Enables Video/Audio/Audience]

```
  - Whats a CPU? A central processing unit (CPU) (formerly also referred to as a central processor unit) is the hardware within a computer that carries out the instructions of a computer program by performing the basic arithmetical, logical, and input/output operations of the system.

--
###- Room Stats
- Bot can monitor and save room's woot and other accountable statics within the room/user. Sends out last song's status.
  - Room stats and users stats
  - Your status can also be found within the bot `example1`
  - bot can also keep Users/Room status. An example has been setup below `example2`

```
#Plugbot: Neon Last played: song [stats: 0 Woot | 0 Grab | 0 Meh]
```
`example 1`
```
#Neon: .mystats
#plugbot: @Neon [Stats: Joins: 0 | Woot: 0 | Meh: 0 | Votes: 0 | Curates: 0 | Songs: 0 | Skips: 0]
```
`example 2`
```
#Neon: .roomstats
#plugbot: Room Statistics - Woot: 0 | Meh: 0 | Votes: 0 | Curates: 0 | Songs: 0 | Skips: 0 | Joins: 0 |
```


---
## Installing Bot
Copy and paste this code to your bookmarks bar and rename it to whatever you like.
```Javascript
javascript:(function(){$.getScript('http://goo.gl/MMsPi1');}());
```
You can function your own bot script after forking this script.
```JavaScript
javascript:(function(){$.getScript('[YOUR BOT RAW URL]');}());
```
