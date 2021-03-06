---
layout: post
title: 'CalGIS Notes: Day 1'
date: '2007-04-04T22:22:00.000-07:00'
author: Paul Ramsey
tags: 
modified_time: '2007-04-04T23:01:37.265-07:00'
blogger_id: tag:blogger.com,1999:blog-14903426.post-7284315790630491684
blogger_orig_url: http://blog.cleverelephant.ca/2007/04/calgis-notes-day-1.html
comments: True
---

I am attending CalGIS, the California GIS conference, this year in lovely Oakland. Sam Smith and I are manning a Refractions booth on the trade show floor, or rather, Sam is manning the booth most of the time and graciously allowing me to go to whatever talks strike my fancy.

Counting on my thumbs, attendance appears to be around 400 to 500, with about 100 of those folks associated with the sponsors on the exhibition floor.

Quick notes on talks:

* Keynote from Dave Sonnen, IGN analyst. Sonnen is the big name in industry analysts for geospatial, is suitably well connected, and has big generic things to say. Analysts are supposed to predict the future, so the big takeaways are the five things Sonnen says will change the direction of the industry over the next few years.

    * Full spatial data search, the first glimmerings of which we are seeing with the new Google KML search
    * Entry of old-line IT firms into geospatial with "good enough" products to hold onto their existing customer base while adding spatial functionality. Oracle, SAP, IBM, etc. We're already seeing this with Oracle adding their own map renderer, their own slippy map user interface, etc, to their spatial offerings
    * Shortage of skilled geospatial workers
    * Spatial data quality becoming a core concern (I imagine lots of people taking the georeferencing of base maps from the consumer mapping providers as gospel will do wonders for creating data of poor quality)
    * **Open source** changing the relationship between vendors and customers<
    * Sonnen really talked up open source, not just in that part of the talk, but others as well, mentioning World Wind as an example of a must-see open source geospatial app. Needless to say, I made sure to button-hole him and invite him to [FOSS4G 2007](http://2007.foss4g.org/).

* I caught the tail end of a talk from a Microsoft rep on Virtual Earth. The most interesting bit was a question at the end, asking what he thought made VE better than Google Maps/Earth. He said oblique photos, web browser integration of 3D, roof-top geocoding (said they got data from corporate partners, Fedex, UPS, DHL, who GPSed addresses at delivery time), and better routing (because their data was NavTeq, driven, not TeleAtlas, compiled).  The latter points feed into some of the (none-too-subtle) language coming out of the [Virtual Earth for Government](http://virtualearth4gov.spaces.live.com/Blog/) blog, which avers that Microsoft is doing great work on data quality. We'll see.
* The Autodesk Map3D product manager gave a good talk on open source, focusing mostly on FDO, and how being open source was benefiting Autodesk and its customers, by providing a faster release cycle and new features from the community. A good talk, it seem well pitched to me, but some of the audience still seemed confused about the idea of a data access abstraction library. It's hard to talk software library concepts to folks who understand software as something that appears on your screen, no matter how carefully you pitch the message. One question: "does FDO run on the desktop, or on the server"? Both, the presenter gently explained.
* Very nicely presented talk from a Farralon consultant on a basic Virtual Earth web mapping project they did for Boston Redevelopment. Good thoughts on resisting creeping featuritis, focusing on the real end user and stopping there. Good demonstration of the value-adds you get for free building on the VE API (or, as the presenter noted, the GMaps or Yahoo APIs).  Good free base data, geocoding, nice UI.  Some very nice shots of how VE provides multiple views of the same data.  They put some red data dots on their map (*yawn*), flipped to oblique and there the dots are on the side of the buildings (*huh?*), flipped to 3D and there the dots are on the tops of the 3D buildings (*nice!*). Very impressive demonstration of how VE ties together the three views under one API.
* Afternoon talk from CalTrans on their use of Google Earth. They bought the Whole Enchilada, a complete Google Enterprise license ($200K, he said). Looks like they have a good quantity of their live data accessible to their staff via the interface now, some good pretty pictures. Interesting, gave some reasons for not going with other 3D options: ArcGIS Explorer, too vertically integrated, tied into other ESRI things, trying to get their IT more diversified (I guess you *can* have too much of a good thing); World Wind, harder to use, more "scientist oriented"; Virtual Earth, more business-to-business or business-to-customer oriented. I just report the news, ma'am.
* Finally, a talk from a Google employee on KML Regions. Nothing I did not know already, or you could not learn from the API documentation, but a nice overview of what can be done. I'm looking forward to playing with this technology more, particularly in the relatively untapped field of publishing large amounts of *vector* data progressively via super-overlays.

Took the BART over the San Francisco for a little evening stroll through the city, had dinner at a "gourmet burger" place on Polk, and BARTed back.  In the words of Samuel Pepys, "And so, to bed."