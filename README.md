# FiveM-PlaneSmoke-OneSync
Revamped plane smoke script that is compatible with onesync. 

Original script was made by JayMontana36 however i added support for color presets instead of manually having to use RGB.

`Usage`

/smokecolor red
/smokesize 0.1

`Colors`

The list could potentially be expanded however it currently supports:

red, blue, green, purple, cyan, black, pink, yellow, orange, white

It also can still use rgb color codes!

`Customisable!`

You can choose what aircraft can use smoke via the simple list in `client.lua`

`Limits`

Smoke size has a maximum of 5.0 so if the user does /smokesize 6.0 it will default to 5.0 (This is easily able to be disabled if you would like)

`Usage`

Once you are in an aircraft that is on the whitelist within `client.lua` simply press `z` and the smoke will start!

Then you can use `/smokecolor` to view a list of available colors so that you can have whatever color you wish!

Or you can change the size with `/smokesize 4.3`
