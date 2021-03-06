# Twitch Plays Choice Chamber
This is a script to allow Twitch to play [Choice Chamber](https://choicechamber.com). Choice Chamber is a game where the Twitch chat can decide your fate, but this script allows it to control the player!

When finished and tested, the code will be released here.

## Code Setup

### Setting up the script dependencies
1. Head to the [Node.js website](https://nodejs.org) and download the latest release.
2. Run the Setup file. It will install everything that is needed to run the script.
3. Restart your computer.

### Configurating the script
1. Head to the [OAuth Password Generator](https://twitchapps.com/tmi/) and copy your OAuth key.
2. Open config.json.
3. Put in the OAuth Key under `oauth`.
4. By default, powers are disabled, however if you want chat to be able to give [subscriber](https://choicechamber.com/sub) or [Kickstarter](https://choicechamber.com/powers) powers, set it to `true` under `powers`.
5. If you enable powers, you will need to put in if you backed the Kickstarter. Most people haven't, so by default it's `false`, but if you did, set it to `true` under `backed`.
6. The most important parts! Enter your Twitch username under `streamer` and the username that will respond to bot commands under `bot`.
7. Save the file and exit.

### Starting TPCC
Not much to it really, open the Start script and watch it roll.

To stop it, open the Stop script. Pretty simple stuff.
