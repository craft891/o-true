# rammerhead-heroku

## Rammerhead Proxy, changed to work on Heroku and Replit deploy. Please report any errors to me:
> Discord EnderKingJ#0001

## Thanks to OlyB for the name idea.

### Modified from [website-aio](https://github.com/holy-unblocker/rammerhead-fork-aio/)

> Current Version: 1.2.3 (Latest)

> proxy based on testcafe-hammerhead (password is `sharkie4life`)

Demo links:
https://rammerhead-heroku.enderkingj.repl.co
https://rammerhead-heroku.herokuapp.com
https://demo-opensource.rammerhead.org

## Quick Deploy

<a href="https://replit.com/github/EnderKingJ/rammerhead-heroku"><img src="https://binbashbanana.github.io/deploy-buttons/buttons/official/replit.svg"></a>
<a href="https://heroku.com/deploy/?template=https://github.com/EnderKingJ/rammerhead-heroku"><img src="https://binbashbanana.github.io/deploy-buttons/buttons/official/heroku.svg"></a>
<a href="https://glitch.com/edit/#!/import/github/EnderKingJ/rammerhead-heroku"><img src="https://binbashbanana.github.io/deploy-buttons/buttons/official/glitch.svg"></a>

## Supporting me and contributing

Server infrastructure costs money and developing this project consumes a lot of my time, so I would appreciate it greatly if you become a Patreon member: https://www.patreon.com/rammerhead


## Who is this package for

Package is for those who want a fully-configurable proxy that works on many sites

## Effectiveness of proxy

This proxy supports proxying
- basically everything except google logins

## Features of proxy

The proxy allows users to create a "session". When they access their session, their localStorage and cookies will be synced with rammerhead. This allows for accurately mocking cookied requests and conveniently save their logins even if they switch devices. This also enables users to configure a custom HTTP proxy server for rammerhead to connect to for the session.

## Installing and running

Rammerhead requires you to have at least **node v16** to be installed. After that is installed, clone the repo, then run `npm install` and `npm run build`.

After, configure your settings in [src/config.js](src/config.js). If you wish to consistently pull updates from this repo without the hassle of merging, create `config.js` in the root folder so they override the configs in `src/`.

Finally run the following to start rammerhead: `node src/server.js`

## Discord server

For any user-help non-issue related questions, please ask them here: [Rammerhead Support Server](https://discord.gg/VNT4E7gN5Y).
