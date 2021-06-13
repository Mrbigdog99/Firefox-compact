This is a userChrome for Firefox that makes Proton compact.

With this userChrome Firefox is 63(85) pixels tall, and for reference default Proton is 85(113). Parentheses are when the bookmarks bar is shown.

Right now only the default dark theme is supported until I can firgure out how to get the sound icon coloring working properly. 
Make sure that you are using "Normal" density, not "Compact (not supported)".

Known bugs: 

When you press alt the min, max, close buttons don't look right. I don't know how to fix this. 

Sound icon colors only really work in dark mode, the problem being getting the right color for the stroke when the tab is not active and being hovered, and when it's   multiselected. Maybe add a circle the same size behind the sound icon?
