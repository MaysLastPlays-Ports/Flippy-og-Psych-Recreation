# Friday Night Funkin' Vs Fliqpy

# Compiling infos:
you must have [newer version of haxe](https://haxe.org/download/) because 4.1.5 misses lots of stuff

follow a friday night funkin' source code compilation tutorial, after this you will need to install luajit.

the engine has an android support. for making mp4 cutscene works in android you have to install this extension: `haxelib git https://github.com/MaysLastPlay77/extension-videoview ` on a command prompt/powershell

to install luajit you have to use this because of the android support stuff: `haxelib git linc_luajit https://github.com/MAJigsaw77/linc_luajit-nebulazorua ` on a command prompt/powershell

if you don't want your mod to run lua, remove in project.xml the "lua_allowed" line

also you need this for compiling: `https://github.com/MaysLastPlay77/androidtools ` on a command prompt/powershell 

## Credits:
* psych engine team - base engine
* mayslastplay - play engine coder and lead developer

### Special thanks
* psych engine contributors - contributing on the base engine
* vegethyt - additional coding
* m.a jigsaw - android support and libraries
* angël - android controls style maker

# Features

## attractive animated dialogue boxes:

![](https://user-images.githubusercontent.com/44785097/127706669-71cd5cdb-5c2a-4ecc-871b-98a276ae8070.gif)


## Mods support
* probably one of the main points of this engine, you can code in .lua files outside of the source code, making your own weeks without even messing with the source!
* comes with a mod organizing/disabling menu. 

## Cool new chart editor changes and countless bug fixes
![](https://github.com/shadowmario/fnf-psychengine/blob/main/docs/img/chart.png?raw=true)
* you can now chart "event" notes, which are bookmarks that trigger specific actions that usually were hardcoded on the vanilla version of the game.
* your song's bpm can now have decimal values
* you can manually adjust a note's strum time if you're really going for milisecond precision
* you can change a note's type on the editor, it comes with two example types:
  * alt animation: forces an alt animation to play, useful for songs like ugh/stress
  * hey: forces a "hey" animation instead of the base sing animation, if boyfriend hits this note, girlfriend will do a "hey!" too.

## Multiple editors to assist you in making your own mod
![screenshot_3](https://user-images.githubusercontent.com/44785097/144629914-1fe55999-2f18-4cc1-bc70-afe616d74ae5.png)
* working both for source code modding and downloaded builds!

## Story mode menu rework:
![](https://i.imgur.com/ub2ekpv.png)
* added a different bg to every song (less tutorial)
* all menu characters are now in individual spritesheets, makes modding it easier.

## Credits menu
![screenshot_1](https://user-images.githubusercontent.com/44785097/144632635-f263fb22-b879-4d6b-96d6-865e9562b907.png)
* you can add a head icon, name, description and a redirect link for when the player presses enter while the item is currently selected.

## Awards/Achievements
* the engine comes with 16 example achievements that you can mess with and learn how it works (check achievements.hx and search for "checkforachievement" on playstate.hx)

## Options menu:
* you can change note colors, delay and combo offset, controls and preferences there.
 * on preferences you can toggle downscroll, middlescroll, anti-aliasing, framerate, low quality, note splashes, flashing lights, etc.

## Other gameplay features:
* when the enemy hits a note, their strum note also glows.
* lag doesn't impact the camera movement and player icon scaling anymore.
* some stuff based on week 7's changes has been put in (background colors on freeplay, note splashes)
* you can reset your score on freeplay/story mode by pressing reset button.
* you can listen to a song or adjust scroll speed/damage taken/etc. on freeplay by pressing space.
