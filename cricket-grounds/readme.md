##Cricket Grounds with d3 - work in progress

Using d3js to show the shapes and sizes of cricket grounds around the world.

###Data
It was surprisingly difficult to find the dimensions of cricket grounds on the web. I measured the majority myself using the 'Measure distance' option in Google Maps.

###Still to do
- Finish collecting data for all major grounds
- At the moment, all grounds are `<ellipse>` elements. Some grounds (in real life) look more like rounded rectangles (e.g. Lord's). I plan to set a conditional 'if' in JS to set those that look rectangular as `<rect>` elements.
- Add more of a story/narrative (including the official rules for cricket ground sizes)
- Update the 'pitch' element to be more dynamic
- Change grass colours depending on country/climate?
- Finish off the 'cricket ball' tooltips. Display info about the ground (capacity, fun fact?)
- Add personal footer with link to code etc
- Double-check the scale and set up code
- Maybe check out something like [this](http://bl.ocks.org/mpmckenna8/566509dd3d9a08e5f9b2) re. the area of the ellipses. Although this probably only matters for circles.
- Sort grounds alphabetically in the JS code
- Perhaps add a drop-down to choose each country instead of having them all on the same page.
- Maybe add a subtle background colour or pattern
