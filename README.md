simple-youtube-gallery
======================

Youtube Gallery that aims to be as simple yet functional as possible.  Built using jQuery.

##Features
- Connect to a playlist
- Retrieve the latest videos every refresh
- Change maximum number of videos
- Change videos per row

##How to use
Load **gallery.js** and **style.css** onto the page you want the gallery to show up on.  Change/remove the *body* style in style.css, it will likely mess up your other styles (only used for the demo).


Change lines 2, 3, and 4 in gallery.js to set the playlist options.  **Change [your key here]** in gallery.js on line 7 to your Youtube API key.  If you want to change the max number of returned results from the API you can do that on line 7 also.


On your page, wherever you want the player to show up, put a *div* with id 'player'.  Wherever you want the rows of videos to show up put a div with id 'rows'.

##Demo

http://www.jackjamieson.me/syg/demo.html
