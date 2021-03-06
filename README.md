# Heroes of the Storm IRC bot

## Code status

[![Build Status](https://travis-ci.org/chadrien/hots-irc-bot.svg?branch=master)](https://travis-ci.org/chadrien/hots-irc-bot)
[![Test Coverage](https://codeclimate.com/github/chadrien/hots-irc-bot/badges/coverage.svg)](https://codeclimate.com/github/chadrien/hots-irc-bot)
[![Dependency Status](https://www.versioneye.com/user/projects/54da6f1cc1bbbd5f8200023d/badge.svg?style=flat)](https://www.versioneye.com/user/projects/54da6f1cc1bbbd5f8200023d)
[![Code Climate](https://codeclimate.com/github/chadrien/hots-irc-bot/badges/gpa.svg)](https://codeclimate.com/github/chadrien/hots-irc-bot)

## Run

* Get sources
* Copy `config.yml.dist` to `config.yml` and edit it with your configuration
* Install dependencies with [bundler](http://bundler.io/) (`bundle install`)
* Run the bot: `bundle exec rake run`

## Available bot commands

* getbt USERNAME - Print the BattleTag for the entered name
* addbt BATTLETAG REGION - Saves your BattleTag
* removebt - Remove your BattleTag from the database
* rating USERNAME - Replies with a list of players with the given BattleTag from HotsLogs
* rotation - Prints the current free hero rotation
* tierlist - Replies with the url for the Zuna tierlist
* tips - Links the tips section
* tips USERNAME - Links the tips section and highlights user
* mumble - Prints server info of the Reddit Mumble
* ts - Prints server info of the Reddit Teamspeak
* bug - Submit an issue the bot's bug tracker
* help COMMAND - Displays help information for the COMMAND
* help - Lists available commands

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md)
