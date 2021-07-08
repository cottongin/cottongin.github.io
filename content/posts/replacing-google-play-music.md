+++
author = "cottongin"
title = "Replacing Google Play Music"
date = "2021-07-08"
description = ""
featured = true
categories = [
]
tags = [
  "music",
  "gpm",
  "plex",
  "sad",
]
series = [
  "GPM"
]
+++

Google has officially killed their popular music streaming service Google Play Music and replaced it with their YouTube Music service, and as awesome as YouTube can be it just does not quite cut it for me and thus this documents my trials and tribulations while seeking my own replacement.

<!--more-->

![GPM](https://i.imgur.com/0cRioK9.jpg)

>   No wires, no painful syncing. Your music collection is stored in the cloud, so you can stop worrying about where your songs are and start enjoying your music.
>
>  — <cite>Paul Joyce[^1]</cite>

## History

To begin... Google announced a slew of new services and products during their 2011 I/O Keynote, and among them was a new music service aimed at taking on the likes of other popular music streaming services at the time like Rdio, Groove Shark, Pandora, and Spotify. Launched in limited invite-only beta at first it was later fully announced and came to be known as *Google Play Music* (GPM)

Unlike most other music streaming services at the time, Google launched GPM as a locker-style service. This enabled a user to upload their own audio files and play them back on any web-connected device. 

As a person with a rather eclectic collection of music, this was like a dream come true: I would be able to fill in any gaps in whatever GPM ended up including in the library (GPM launched without any sort of storefront or library of its own) with tracks of my own! And boy did I...

A decade later and the service had evolved and changed a few times over its life but the core promise remained the same: **Your music collection is stored in the cloud, so you can stop worrying about where your songs are and start enjoying your music.**

{{< figure src="https://i.imgur.com/JGLkDy6.png" width="100%" caption="Nice tracksuit! 😎" class=" img-fluid mx-auto text-center mt-3" >}}

[The Wikipedia article](https://en.wikipedia.org/wiki/Google_Play_Music#:~:text=Users%20with,the%20device) for GPM summarizes it quite well:

>   Users with standard accounts could store up to 50,000 songs from their personal libraries at no cost. A paid Google Play Music subscription allowed users to on-demand stream any song in the Google Play Music catalog and in YouTube Music Premium catalog and in several territories in [YouTube Premium](https://en.wikipedia.org/wiki/YouTube_Premium) catalog. Also, users could purchase additional tracks from the [music store](https://en.wikipedia.org/wiki/Online_music_store) section of Google Play. Google Play Music [mobile apps](https://en.wikipedia.org/wiki/Mobile_app) also supported offline playback of tracks stored on the device.
>
> — <cite>Google Play Music[^2] From Wikipedia, the free encyclopedia</cite>

It was a fantastic service that I made great use of for nearly 10 full years and though I have had plenty of notice about the plan to kill it, I have never quite been able to find the perfect replacement.

## Options

Truth be told, I have tried most of the popular music streaming services in one capacity or another over the years. My favorites have been Pandora, Rdio (R.I.P.), and of course GPM.

I love the ability to tune automatically generated playlists based on my tastes ("Radio stations") and the Music Genome Project-powered Pandora is unmatched in its ability to play music I enjoy without me having to think too hard about picking something to listen to. 

Unfortunately however, none of the major services I am aware of today offer the same ability of uploading my own songs and also choosing from an extensive library that GPM did.

So am I out of options?

## Enter Plex

![Preview of http://plex.tv](https://i.imgur.com/z4xZUaB.png)

My (sort of) hard requirement of being able to manage and play my own library remotely sent me down the rabbit hole of self hosting.

The options for self hosting are nearly endless and there are lots of options depending on your requirements. I tend to prefer FOSS (Free with the big F not the little f) though sadly my experience with media/audio open source projects is rather limited. This is partly because my brief searching did not yield anything super promising other than the open source alternative (Emby) to the solution I ended up going with (Plex).

Plex. You may have heard of it. It is a rather popular media server aimed more at the movie and television crowd but the fine folks that develop the software have focused lately on some great music features (including an Android app from Plex Labs called Plexamp).

I was already using Plex for my video needs, it made sense to at least try it for my music needs as well.

## The Missing Piece

So aside from some nitpicking I have with the way Plex wants to try to organize my collection, I am overall pretty satisfied with the Plex music streaming experience, the only thing missing is the Spotify/Rdio side of the service. I am investigating signing up for the Tidal service as it is seamlessly integrated into Plex and offers very high quality audio. If their radio/playlist algorithms are even close to Pandora this may replace my Pandora subscription as well!

## Conclusion

As I begin the tedious process of uploading my entire GPM collection to my NAS and letting Plex handle all of my streaming needs it is becoming apparent to me that though this is a great and elegant solution I now have a single point of failure: Plex. This is **not** ideal and I long-term I may investigate Emby or something similar a bit more thoroughly.

[^1]: Paul Joyce [introducing Google's "music beta"](https://www.youtube.com/watch?v=OxzucwjFEEs&t=1589s) @ `Google I/O 2011`
[^2]: [Google Play Music - Wikipedia](https://en.wikipedia.org/wiki/Google_Play_Music)