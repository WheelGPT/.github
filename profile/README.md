# WheelGPT

More information on [wheelgpt.dev](https://wheelgpt.dev).

WheelGPT is a [Trackmania](https://www.trackmania.com/) Twitch bot that was originally developed for the Twitch channel of GranaDyy - the wheel guy. With the bot, viewers can ask for the current map of the streamer. They can also guess the next personal best time of the streamer. To automate the evaluation of the guesses and the updating of the map, this plugin was developed.

## Projects

- Trackmania Plugin: https://github.com/WheelGPT/wheel-gpt-plugin ([OpenPlanet](https://openplanet.dev/plugin/wheelgpt-plugin))
- WheelGPT Backend: https://github.com/WheelGPT/wheel-gpt-backend
- WheelGPT Frontend: https://github.com/WheelGPT/wheel-gpt-frontend

## Features

### Token

To use this plugin, you need a token. For that you need to register on [wheelgpt.dev](https://wheelgpt.dev). The token assigned to you is sent with every request to our server and identifies your Twitch channel. So don't share this token with anyone. Otherwise, others can use the plugin under your name and, for example, send best times to your Twitch channel that you have never driven.

The token assigned to you must be entered in the `Settings` -> `WheelGPT-Plugin` -> `Info/Token`.

### Personal Best

With the Twitch Bot, your viewers can guess what your next best time will be with `!guess <time>`. The format of the time is `hours:minutes:seconds.milliseconds`. `Hours` and `minutes` are optional. Example: `!guess 12.345` or `!guess 01:23.456`.

If the plugin is activated, whenever you set a new best time on a map, this time will be sent to our server. Afterwards all received guesses of your users will be checked and in the bot will announce in the chat which viewer was closest with the guess.

If you want to deactivate that your best times are sent to our server, you can deactivate this under `Settings` -> `WheelGPT-Plugin` -> ` Send PBs to Server`.

### Map

With the Twitch bot, viewers can use the command `!map` to find out which map you are currently playing. 
If the plugin is activated, whenever you enter a new map, this map is sent to our server. If you use the `Champion Medals` plugin, the Champion Medal time will also be sent to the server.

If you want to disable this feature, you can deactivate this under `Settings`->`WheelGPT-Plugin`->` Send Maps to Server`.

## Any Questions? Feedback?

If you have any questions regarding the plugin or the Twitch Bot, feel free to contact me!

- Twitter: https://twitter.com/sowiemarkus
- Discord: sowiemarkus



