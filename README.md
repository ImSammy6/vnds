# VNDS
VNDS with many new features.

List of changes:
- Added back mp3/aac support
- Added new text features
  - RGB text color support by putting "\x1b[r;g;bm" in a line. Values are from 0-31
  - Change the font with \font(fontname.ttf). Works mid-line as well. Fonts go in the root folder of the novel, and it needs a font called default.ttf in there or it'll probably break.
  - Use \n for a new line
  - Use \i to display the rest of the line instantly, regardless of text speed
- Text now auto-scrolls so only the most recent message is shown on-screen, so you don't have to move your eyes as much
- Added a new parameter to setimg to set how long the fade time should be. If multiple sprites change at once, only the last one sets the speed.
- Fixed sound effect looping. Playing them an exact number of times still doesn't work (And possibly never even worked???)
- Added a "very fast" text speed option. Seems to lag the game a bit so idk if it's actually faster
- Sound effects are no longer ignored while skipping
- Increased the sound effect size limit to 6MB on DSi's
- Disabled the brightness button on DSi's
- Increased the number of save slots from 18 to 72 and sped up the animation for switching pages
- Disabled the loading animation during delay commands
- Fixed a bug where quickly tapping up or down in a choice would move up or down 2 options instead of 1
- Fixed the pause between lines when text has a custom color (or at least reduced it)


Original version is from https://github.com/asiekierka/vnds
