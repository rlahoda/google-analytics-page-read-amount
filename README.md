# Google Analytics Event Trigger For How Far Down A Page A User Has Read
A script that adds events to Google Analytics to show how far down the page a user has read.

## To use:
Add `<script type="text/javascript" src="pagereadamount.js"></script>` to the bottom of your page, just before the closing `</body>` tag.

This script works for sites using the older analytics.js setup for Google Analytics but I haven't tried it with the newer Google Tag Manager script. 

To read my blog post about how it works go to [my blog post on the topic](http://roblahoda.com/trying-to-get-more-out-of-google-analytics/)

## To find the event information on Google Analytics:
You can find **Events** on the Google Analytics by starting from the reports page (the default view of your site information) then go to **Behavior** > **Events** > **Top Events** where you'll see the events listed. If you leave this script as-is, you will see **Blog Posts** listed. If you click on that you will see the "Event Action" **User Read** listed. Clicking on that will take you to the listing of the percentage amounts.  

## To change the event information:
Currently it will fire an event category of `Blog Posts` and the action is `User Read` then broken out into the different lengths down the page. If you want it to show up differently, change `Blog Posts` and `User Read` to whatever you choose. 
