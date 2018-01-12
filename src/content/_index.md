---
title: "Artwork Beef"
date: 2017-11-21T22:44:39-07:00
---

# Artwork Beef <span class="subtitle">An add-on for Kodi</span>

Artwork Beef automatically adds extra artwork for media in your media libraries. It is generally intended to
handle extended artwork just as Kodi and scrapers already do for basic artwork. It grabs artwork from the wonderful web
services [fanart.tv], [TheTVDB.com], [The Movie Database], and [TheAudioDB.com].

[fanart.tv]: https://fanart.tv/
[TheTVDB.com]: http://thetvdb.com/
[The Movie Database]: https://www.themoviedb.org/
[TheAudioDB.com]: https://www.theaudiodb.com/

It is developed for Kodi **17 Krypton**, and should also work for **16 Jarvis** and **18 Leia**.
15 Isengard should mostly still work, but it's really time to update.  
[Support and feedback thread](https://forum.kodi.tv/showthread.php?tid=258886) on the Kodi forums.  
[Source](https://github.com/rmrector/script.artwork.beef) hosted on GitHub.

It fully supports series and season artwork from TheTVDB.com; movie, movie set, music video, series,
and season artwork from fanart.tv; movie and movie set artwork from The Movie Database;
and music video artwork from TheAudioDB.
For those series that really pop, [high-quality fanart] for each episode can be
added from The Movie Database.
The music library is supported in Kodi 18 Leia for artists, albums, and songs, with artwork
from TheAudioDB and fanart.tv.

[high-quality fanart]: {{< ref "examples/_index.md#episode-fanart" >}}

The full list of artwork types grabbed from external web services:

media type | art types
--- | ---
**movies** and **movie sets** | _poster_, _fanart_, _banner_, _clearlogo_, _landscape_, _clearart_, _discart_
**music videos** | _poster_ (album/single cover), _discart_, _fanart_, _artistthumb_, _banner_, _clearlogo_, _clearart_
**series** | _poster_, _fanart_, _banner_, _clearlogo_, _landscape_, _clearart_, _characterart_
**seasons** | _poster_, _fanart_, _banner_, _landscape_
**episodes** | _fanart_
**artists** | _thumb_, _fanart_, _banner_, _clearlogo_, _clearart_
**albums** | _thumb_ (album cover), _discart_, _back_, _spine_
**songs** | _thumb_ (single cover)

Local artwork stored in the file system is preferred if it exists, and Artwork Beef can be configured
to download other artwork that is added. Local artwork is currently only supported for the video library.