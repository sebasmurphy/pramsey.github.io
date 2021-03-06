---
layout: post
title: The State of the State of Open Source GIS
date: '2006-07-29T08:49:00.000-07:00'
author: Paul Ramsey
tags: 
modified_time: '2006-10-21T11:22:57.831-07:00'
blogger_id: tag:blogger.com,1999:blog-14903426.post-115418992610304195
blogger_orig_url: http://blog.cleverelephant.ca/2006/07/state-of-state-of-open-source-gis.html
comments: True
---

About a week ago, my colleague Jody Garnett posted a link to a [paper of mine](https://web.archive.org/web/20060830221232/http://www.refractions.net/white_papers/oss_briefing/2006-06-OSS-Briefing.pdf) on the OSGeo mailing list.  From there, some other folks passed it on, and finally the cycle closed again, as I found a [posting-about-a-posting](http://spatiallyadjusted.com/state-of-net-open-source-gis/) on James Fee's excellent blog.

The paper itself is a backgrounder for a talk I have been trying with varying degrees of success to shoehorn into 30-minute time slots for the past several years.  Any student of the open source GIS world will soon realize that in order to try and talk about it coherently, a great deal will have to be left out.  That said, my criteria for taking and leaving have hardly been scientific. 

* I have tried to include projects that are "important" for infrastructural reasons (like the widely re-used libraries).
* I have tried to include projects that are "big" in terms of having more than a few developers or users.
* I have included projects that meet neither of the above criteria, but I just personally find "neat" or "promising"

  * "Neat" like GMT, which has a small development community,and no technical ties to the rest of its tribe, but is really useful for UNIX types stringing calculations together, a great power-user tool for non-developers.
  * "Promising" like Mapnik, with a very focussed developer with some very clear design goals up front, and a shameless love of the bleeding edge.
  
James guesses that my choices have something to do with focussing on "the open source GIS clique that revolves around Refractions and OSGeo", which is not correct.  I include references to projects (QGIS, gvSIG, GMT, TerraLib, OpenEV, OpenMap, Mapbender) which our company has never touched, or which have no association with OSGeo.  Like everyone, I write through the frame of my experience, but I do try to get beyond it occasionally.

The [original post](http://www.sharpgis.net/OpenSourceGISCanOnlyBeMadeUsingEitherCAndJava.aspx) took issue either with my failure to include a ".Net tribe", or perhaps with the whole "tribe" concept entirely.  

I won't defend the lack of a ".Net tribe" section. The document was largely written about three years ago, and updated more or less incrementally since then. When I did the initial survey, there was no .Net GIS community that minimally met the standards I was holding the other tribes to.  That has changed now.  Attendees at my talks this year will have heard me point out that gap in my materials.

I do defend the "tribe" concept, as a way of organizing a talk about open source GIS, because I believe that the "community" is more important than the technology.  Do a little association graph of high profile members of the communities and you will find they all clump around particular groups of projects, and those groups tend to be defined by their implementation language.

The same seems to be true of the .Net tribe. As I read the contributor names to those projects, I find few points of reference to contributors in the other tribes, with the exception of a spome people who have gotten involved in the Java side just enough to port things to .Net.

Anyhow, if people are going to read my work and take it seriously, I have a responsibility to update it a little more carefully and frequently.  Among the things I noted while doing talks this spring:

* I do not have an entry for Worldwind! Oops!
* OpenEV pretty irrelevant these days, the world has passsed it by. So it is due to be cut.
* Same thing for WKB4J, all its functionality seems to have migrated to other places.
* GeoAPI should probably be cut from the talk. Though it is a dependent library for GeoTools, its purpose is just too abstract to clearly explain.
* The "web" projects are hard to talk about definitively, because there are so many and it is still so unclear where the balance of implementation is settling.  And so many people just roll their own web interfaces anyways.

    * In any event, I am missing [OpenLayers](http://www.openlayers.org/), which is talking about merging with [ka-map](http://ka-map.maptools.org/).

* I need to spend the time figuring out which parts of the .Net tribe should be included in a new .Net section.

Frankly, even with my arbitrary cutting of whole swathes of projects from my "survey" the survey itself is getting unwieldy, which seems to call for yet another approach.  I did the survey as a sort of reaction to the [FreeGIS](http://www.freegis.org) approach, which while egalitarian has resulted in an undifferentiated mass of entries.  Comprehensiveness can be a curse.

I think my next series of talks or documents will focus on particular combinations of projects that can be stacked into solutions.
