# cyf-console

cool console, myan..

!! if you encounter any issues, join the unitale server !!

press `` ` `` or `f10` to open the console

if a line has more `(`s than `)`s, it automagically goes to a new line when you press enter

if a line ends with `;`, it goes to a new line when you press enter

if a line ends with `\`, it goes to a new line when you press enter, except this one works for strings (and breaks with anything else)

you can also just press shift+enter to go to a new line

arrow keys work like how youd expect

![cool imamge of console](https://ringo.is-a-good-waifu.com/7K3Nh9q.png)

BASIC SETUP:

```lua
function EncounterStarting()
    require "Libraries/console"
end
```

just throw a `require "path/to/library"` in your EncounterStarting function and it should be good to go

also, put the font in `Sprites/UI/`, to make it look like `YourMod/Sprites/UI/Fonts/arial.png` and `YourMod/Sprites/UI/Fonts/arial.xml`

the console is stored inside of the `console` variable in the encounter file

`console.cursorcolor` changes the color of the cursor, default is 00FF00

`console.lines` changes the amount of lines to display, default is 10

`console.font` changes the font, default is arial

you can set this stuff up in the encounter file, but really, there's no real reason

you can open up the console.lua file and change the `self.cursorcolor/lines/font` variables directly

there's an easter egg, try and find it

thanks to Eir for the arial font, and help with the j turning into \[ bug
