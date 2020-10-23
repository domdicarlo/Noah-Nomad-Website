# The Noah Adams Tracker

You can check out this code featured at [whereisnoah.com](https://www.whereisnoah.com) ! 

## What I did

My friend is a world traveler, and for fun would like to inform friends and family of his current whereabouts at the country-level resolution. So, I built him a small web applet that shows which country he is in. 

## How it works

Noah has to load in dates and their corresponding locations, after which the applet looks at the current date to determine where he should be. It updates based on an input array feauturing countries and dates. It draws a country using its geoJSON data for path data. 

## What I learned

This showcases my ability to manipulate javascript arrays (as there is a lot of that going on here), as well as develop scaling algorithms so that different countries of all shapes and sizes can fit nicely on a page whether on mobile or web. 

## What could be improved

Instead of using scaling algorithms, I think it would have been much easier and more standard to use css. I was quite new to web development when I did this project, so my implementation method reflects my inexperience. It was still cool to program the project in this way.

## Miscellaneous

I have done some hard editing of the geoJSON file at times, so if you want to do something like this for yourself, make sure to use my geoJSON. 

I have commented a few problem countries in the data, being Russia and smaller countries. Certain countries have land spread far out in the geoJSON file, making their plotting and scaling a problem. To fix this for those countries, you must hard edit the geoJSON to either cut out small islands recognized as Russia (or any country) or place them nearer the central land mass. For the extra small countries, you will need to include a higher resolution set of coordinates within the geoJSON. I have not done this at this time but it is definitely possible.


