# yt2atv-rb

`yt2atv-rb` is a simple command line utility to Airplay a YouTube video to an AppleTV. Simply call `yt2atv <URL>`, select an AppleTV to stream to, and start watching.

## Notes

This is most definitely not a finished product. It's currently at version 0.1, which I would consider to be just a simple functional utility. This is also pretty much the first time I'v done any kind of Ruby programming, so I expect this to not be the best in the world.

# TODO

- **Code cleanup.** I'm sure things could be much better abstracted than what I have here.
- **Control.** I want to add the ability to do some control from the terminal (like pausing the video). I had that in there, but it was causing issues once the process finished executing.
- **Info.** It'd probably be a good idea to show info about the video before it gets sent to the AppleTV.
- **Airplay Device Selection.** Improve the selection system for selecting an AppleTV. Add support for passing in a name as part of the program arguments.
