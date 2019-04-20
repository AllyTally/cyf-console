# cyf-console

cool console, myan..

press `` ` `` or `f10` to open the console

BASIC SETUP:

```lua
function EncounterStarting()
    require "Libraries/console"
end
```

just throw a `require "path/to/library"` in your EncounterStarting function and it should be good to go



the console is stored inside of the `console` variable in the encounter file

`console.cursorcolor` changes the color of the cursor, default is 00FF00
`console.lines` changes the amount of lines to display, default is 10
`console.font` changes the font, default is arial

you can set this stuff up in the encounter file, but really, there's no real reason

you can open up the console.lua file and change the `self.cursorcolor/lines/font` variables directly

there's an easter egg, try and find it

thanks to WD200019 for the arial font
