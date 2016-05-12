---
layout: portfolio
title: An Online Radio Player
teaser: I worked with a small team to get a live streaming player out to public radio stations quickly.
micro-teaser: Design & Front-end
category : portfolio
assets: beta-player
hero: heroa
tags : [backbone,javascript,css,ux,front-end,design,npr]
---

You’d expect it to be easy to find ways to listen to live streams on a radio station’s website. But this hasn’t always been the case for a lot of public radio stations.

While almost every station’s web site has some mechanism for listening live, it often involves asking the would-be listener to navigate through a list of links with names like .pls and .m3u, or selecting from buttons for a “flash player,” “windows player” or “itunes.” Obviously, it shouldn’t be so hard.

For this project, I worked with a small team tasked with getting something out to stations relatively quickly. Something we could test, learn from, and improve upon over time. I always like these kinds of projects, because the focus is on moving quickly from research to prototype to design and build — and because it was a small team, I got to be involved in all aspects of the process.

{% assign photo="full-size" %}
{% assign caption="Screenshot on desktop" %}
{% include custom/pic_normal filetype="png"%}

{% assign photo="hand" %}
{% assign caption="A smartphone view of the player" %}
{% include custom/pic_normal %}

In the first week, I spoke with stations and to a panel of public radio listeners — and did some quick guerilla research out in the field (a local cafe where I asked strangers for their thoughts). In the prototypes I showed, people generally understood how to start and stop the player; they understood the name of the thing they were listening to; they understood there were other listening options.

{% assign photo="paper" %}
{% assign caption="I created paper cut-outs that I played with like puzzle pieces, trying out different configurations of copy and functionality." %}
{% include custom/pic_normal %}

Working with paper prototypes, I was able to try a lot of ideas quickly — different copy; different information; different arrangements features. We found that the phrase ‘Live Radio’ communicated clearly to most people the difference between listening live and listening to on-demand — more clearly than “listen live,” at least with our panel of public radio listeners.

In the meantime, our team was working out how to build the player. We wanted it to be persistent — not as common a couple of years ago — but we also had reservations. Creating a player that could live on station’s existing sites and be persistent would be a very hard problem, both technically and in terms of usability and user experience.

Further — and critically — it wasn’t at clear to us that our audience actually wanted or needed a persistent player. If you’re listening to a news/talk program like Fresh Air or All Things Considered, how likely is it you’ll want to be browsing a site and reading at the same time? If it’s a music stream, the possibility seems more likely, but it was still just a guess.

We decided to split the difference, creating a player that would reside in its own browser window. Users who wanted to listen could go to an uncluttered, focused listening experience, where they could browse between different sorts of audio content. Putting the player into its own window also enabled us to take the first steps toward building persistence without having to solve the various challenges of working on an existing universe of drupal sites.

In the next few weeks, we built a player that let users select from among various live streams, see appropriate information about what they were listening to, and listen to a selection of on-demand clips.

Was it any good? It was okay, a lot better than the stations had before. But it was only a first step, one that enabled us to work out various challenges, learn about audience and user-needs, and try out some ideas — like, did people actually care to listen to on-demand clips in this context? (Answer: a little bit). Or, would stations be able to sell underwriting against a player? (Answer: yes).

Unfortunately, we didn’t get to take any next steps because NPR’s focus changed. We’re now working on a true persistent player embedded in station sites. A few of the 'beta’ players are still being used. NPR only provides minimal support for them at this point (I don’t think they’re getting song and artist information anymore), but [this one for KUNC](http://www.kunc.org/player) in Colorado seems to still exist.

### The Design Process

Following are sketches from my design process, illustrating some of my explorations. For example, I considered treating the player with a very clean and white design but ended up making it dark so that it has enough contrast to really stand out as the center of attention. The experience doesn’t include much visual branding at this point so that we can focus on creating a flexible and extensible template. I also considered how to include basic display advertising — unfortunately, it was a requirement that we support standard 300x250 and possibly 320x50 ad unit sizes.

{% assign photo="process01" %}
{% assign caption="" %}
{% include custom/pic_normal filetype="png" %}

{% assign photo="process02" %}
{% assign caption="A smartphone view of the player" %}
{% include custom/pic_normal filetype="png" %}

{% assign photo="process03" %}
{% assign caption="A smartphone view of the player" %}
{% include custom/pic_normal filetype="png" %}

{% assign photo="process04" %}
{% assign caption="A smartphone view of the player" %}
{% include custom/pic_normal filetype="png" %}

{% assign photo="v3" %}
{% assign caption="A smartphone view of the player" %}
{% include custom/pic_large filetype="png" %}

{% assign photo="ia-thoughts" %}
{% assign caption="Exploration of the different kinds of information people would want to see depending on the type of audio, live, on-demand, music, or talk." %}
{% include custom/pic_large filetype="png" %}

{% assign photo="drawings" %}
{% assign caption="Examples of paper prototype cutouts I created." %}
{% include custom/pic_normal %}