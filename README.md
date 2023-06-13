# lenroy (WIP) 🚧
3D-printed robotic arm controlled by servo motors, with 3 degrees of freedom. Don't ask me why I called it lenroy, it was just the first thing that popped into my mind..

As a note, this project is currently under construction (literally) and I have not got a prototype working myself. I'll update it once I am done, but in the meantime you can see progress on my (Mastodon)[https://aus.social/@mightyspaceman]. But just for context, this'll be done really soon. Like... a week or something from now (6/13/23), so be patient :)  

For some specs, the body is printed in ABS, but the filament type shouldn't really matter because the overall strength is bottlednecked by the tips of the servos themselves. I'm printing it on school printers/the one at my local makerspace because I don't have access to one myself. Also speaking of servos, the ones in question are the MG90S, due to the durability from their metal gears as well as having slightly more torque. They're only slightly more expensive than their SG90 counterpart, but it's certainly worth the upgrade - but if you want to go with the cheaper option, the code will still work, and you will only need to make minor tweaks to the 3D files. The microcontroller to drive everything is an Arduino Nano, mostly just because of the 5v GPIO output pin, which alternatives like the ESP32 (which I wanted to use before) lack.

More documentation coming soon. Sorry if I butchered that paragraph, my brain isn't wording today

