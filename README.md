# expand-discord-emojis
JavaScript bookmark to make Discord emojis bigger.

Copy the code from "growmoji.js" into a bookmark's URL field and run it when starting Discord from the Web browser.

It should also work if you copy everything after "javascript: " and run it from one of the desktop clients.

PLEASE NOTE: MUST BE RUN EVERY TIME DISCORD LOADS (INCLUDING REFRESH).

Change the size to whatever you want, but anything over 150px is probably unreasonable, and I really wouldn't recommend over 100-125.
Default is 75px.

Works by looping through each instance of the ".emoji" class and changing the CSS style for height and width.
