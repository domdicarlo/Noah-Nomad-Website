You can check out this code featured at whereisnoah.com !

It updates based on an input array feauturing countries and dates. 

It draws a country using its geoJSON data for path data. 

This showcases my ability to manipulate javascript arrays (as there is a lot of that going on here), as well as develop scaling algorithms so that different countries of all shapes and sizes can fit nicely on a page whether on mobile or web. 

It does not rely on any external libraries (aside from jquery for ajax at one point), working in vanilla javascript.

I have done some hard editing of the geoJSON file at times, so if you want to do something like this for yourself, make sure to use my geoJSON. 

I have commented a few problem countries in the data, being Russia and smaller countries. Certain countries have land spread far out in the geoJSON file, making their plotting and scaling a problem. To fix this for those countries, you must hard edit the geoJSON to either cut out small islands recognized as Russia (or any country) or place them nearer the central land mass. For the extra small countries, you will need to include a higher resolution set of coordinates within the geoJSON. I have not done this at this time but it is definitely possible.


