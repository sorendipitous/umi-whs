Umineko Project GOAT Edition
=================

This is a modified script of [Umineko Project](https://umineko-project.org) bringing various optional changes to the base release.

So far this is **only for playing the game in English** with Umineko Project's translation, so do not install the patch using this script if you intend to play in any other language.

#### Changes to vanilla Umineko Project
- Original Akiko Shikata opening movies for EP1-4
- Spoiler-filled Rondo and Nocturne OPs only viewable after finishing EP4 and EP8 respectively
- New logos for menus, chapter breaks and text boxes
- Increased text size, updated margins and positioning
- EP1 Tea Party post-credits scene moved back to before the credits as in the original PC games
- _no Naku Koro ni_ changed to _When They Cry_ to match the official English naming convention with the logos
- _Nocturne of Truth and Illusions_ is now _Nocturne of **the** Truth and Illusions_, to make its name consistent with _Rondo of the Witch and Illusions_ and _Symphony of the Cat Box and Dreams_ (the upcoming Switch/PS4 game)

#### Known Issues
- Credits scenes use the old logos/titles, simply because the images haven't been edited yet
- Changed files have not been added to file verification at the start of the game
- Patch relies on ons.cfg settings to increase Japanese text size and skip file verification
- No openings displayed at launch
- legacy op1.ogg is the same file as op.ogg, just required separately for the current version of the script to work
- Smaller text than preferable in some scenes to avoid awkward line breaks

## Installation instructions
1. Get and extract all the game files as instructed [here](https://umineko-project.org/en/downloads/).
2. Download the latest GOAT Edition patch from releases.
2. Extract the patch contents into the same folder you installed everything else in, replacing files when prompted.*
3. Launch **onscripter-ru.exe** to play!

*_The patch replaces your existing ons.cfg file. If you have played the game before and wish to keep your previous settings, instead of using the ons.cfg that comes with the patch, just add the following lines to your existing ons.cfg:_<br>
```font-multiplier=p0:6:1.16```<br>
```env[verify]=none```

Extra: if you wish to avoid some scenes possibly inducing motion sickness, add this line to your ons.cfg after installing:<br>
```reduce-motion```

## Credits
- Umineko Project - Most of the things
- Pteryon - Additional scripting and logos
- Forteissimo - Original OP PS3fication
