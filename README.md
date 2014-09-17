## Let's Talk About Your Geostack

[_Let's Talk About Your Geostack_](http://erictheise.github.io/geostack-deck) is a workshop aimed at getting
participants up and running with the open source software and open data needed to build a very simple web mapping
application that, despite its simplicity, demonstrates

 * a [PostGIS](http://postgis.refractions.net/)-enabled [PostgreSQL](http://postgresql.org/) database holding
 * a [metro extract](https://mapzen.com/metro-extracts/) of [OpenStreetMap](http://openstreetmap.org/) data that gets
   used with
 * [TileMill](https://www.mapbox.com/tilemill/) and [TileStream](https://github.com/mapbox/tilestream) to style, render,
   and serve map tiles, plus
 * a simple [Node.js](http://nodejs.org/) API that returns [GeoJSON](http://geojson.org/geojson-spec.html#examples) so
   that
 * the [Leaflet](http://leafletjs.com/) mapping library can display markers and popups for points of interest

The workshop itself can be comfortably presented in about four hours, even allowing for some exploratory _studio time_.
In advance of the workshop, participants need to set aside an additional three hours or so for downloading and installing
software. The deck contains instructions for Mac OS X, Ubuntu 14, and Windows 8.1, including the option of using
virtual machines via [VirtualBox](https://www.virtualbox.org/).

An early version of the workshop was run at [MaptimeSF](http://www.meetup.com/Maptime-SF/) in Nov 2013. More recently,
it's been/being offered at

  * [NACIS Annual Meeting 2014](http://nacis2014.sched.org/event/f65ab42257e61bc7a0066554a466f20d), 11 Oct 2014,
    Pittsburgh, PA
  * [FOSS4G 2014](https://2014.foss4g.org/schedule/workshops/), 8 Sep 2014, Portland, OR

If the deck ends up being a sizable component in a workshop you offer, feel free to send me a pull request that adds it
to the list.

The deck is licensed under the Creative Commons [Attribution-NonCommercial-ShareAlike 4.0
International](http://creativecommons.org/licenses/by-nc-sa/4.0/) license. My intent is that the deck be used
by people studying on their own time, either individually, or in a group where everyone has come together voluntarily
to learn. If a presenter is being paid for their time as they lead people through this deck, in any context, they need
to [contact me](https://github.com/erictheise) about licensing.

Two small code repositories that accompany this deck, [`geostack-api`](https://github.com/erictheise/geostack-api] and
[`geostack-map-pages`](https://github.com/erictheise/geostack-map-pages], are MIT-licensed.

If you come across any inaccuracies, or have other suggestions for improving this deck, please consider [opening an
issue](https://github.com/erictheise/geostack-deck/issues) or submitting a fix via a pull request.


## Nuts and Bolts

### Presentation Framework

The deck uses [Hakim El Hattab](http://twitter.com/hakimel)'s wonderful [reveal.js](http://lab.hakim.se/reveal-js/).

### Screenshots

Screenshots are taken using Apple OS X's Grab utility after setting window size with [Irradiated Software's
SizeUp](http://www.irradiatedsoftware.com/sizeup/). SizeUp's _Center_ shortcut is set to use an absolute size of
`1024w 704h`.

Web screenshots use Chrome after disabling _View ➭ Always Show Bookmark Bar_, then applying SizeUp.

TIF files saved from Grab are added to the `images` directory following a loose naming convention of
`ApplicationName-Action-Detail.tiff`. TIF files are generally resized to `768w 528h` at `72 pixels/inch` and saved to
the `images` directory as non-interlaced PNGs. Both the unaltered TIF and sized PNG are committed to the repository.
