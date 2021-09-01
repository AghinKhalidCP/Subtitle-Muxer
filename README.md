# Sub-Muxer
Telegram bot to mux subtitle with video.

## Deploy the bot on heroku

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

## Features
* Softmux subtitle with video
* Hardmux subtitle with video
* Supported subtitle formats - (ass, srt)
* Supported video formats - (mkv, mp4)

## Notes
* The subtitle file you add will be default subtitle file and will
  be placed as first stream of mkv file and the original streams will
  be placed below it in the same order.
* When hardmuxing only the first Video amd the first Audio file will
  be present in the output file.
  
## Commands
* /help - To get some help about how to use the bot.
* /softmux - softmux the sent video and subtitle file.
* /hardmux - hardmux the sent video and subtitle file.

## To-Do :

- [x] Download file using URL.
- [x] Hardmux support.

## Thanks to :
* [Dan](https://github.com/pyrogram/pyrogram) - Telegram Framework for bots and users.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details

