---
title: "Roller Derby Magnet Board"
layout: single
hidden: true
---
By Wonder Zebra (Vienna Rollergirls), April 2013
Contact, feedback, feature requests: <wonderzbra@gmail.com>

Skaters are represented by circular shapes. They can be dragged with the mouse or finger and push other skaters. The circles around the skaters change colours depending on the situation.
## Colour codes
- OOB: red
- OOP: black
- Pack: green
- No pack: grey (for all in-bounds upright skaters)
- Down: dark red

## Keyboard and mouse commands
- C toggles the cheat sheet with all keyboard shortcuts
- I toggles the GUI
- F toggles full screen
- space bar toggles pack highlighting
- P toggles OOP highlighting
- B toggles OOB highlighting
- N toggles no-pack highlighting
- M toggles numbers on blockers
- left and right arrows cycle through history (so does mousewheel)
- E toggles engagement zone highlighting
- V toggles middle-of-track virtual line display
- S makes everyone skate forward. Shift-S to go faster
- R makes everyone skate backward. Shift-R to go faster
- double-click on a skater to toggle this skater's stance, possible stances are 'upright' and 'down'
- D toggles downed skaters highlighting
- Shift-[n] (where [n] is a digit key) to save current positions and config to bookmark number n. Alt key acts as a +10 modifier so you can save up to 20 bookmarks
- Digit key [n] to load bookmark number n. Alt key works as with saving.
- Alt-mousewheel cycles through the bookmarks too.
- The [escape] key brings you back to the beginning of history and resets history
- Z toggles zebra visibility
- G exports the current situation on the track to a standalone SVG file. Your browser must allow popups for this to work.
- H starts/stop recording. Once recording has stopped, the recorded session is opened as a standalone animated SVG file. Your browser must allow popups for this to work.
- Skaters can be selected in a similar fashion as modern operating systems: draw a rectangle with the mouse, press the control key to modify the current selection, etc. All selected skaters move at the same time. Keep the shift key pressed to have the skaters follow the track, i.e. skaters on the outside go faster.

## Other features
- The number of laps performed by each skater is recorded, so if blockers are in the middle of the pack but OOP then that's because they are one lap late (or ahead). Can be useful to illustrate illegal return. Hover the mouse over a skater to display its current lap
- At the moment the method used to measure distance between skaters is the following: for each skater we take the closest point from the skater's centre to the central green line. Then the distance between two skaters is the distance to go from one point to the other following this line.
