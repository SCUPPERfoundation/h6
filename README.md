# h6

##  Intro
This is a prototype engine for Federation 3 called Hexmosphere / H6.

The goal is to develop a social overlay of the world, starting with a "null"
space, tentatively referred to as the Mentagon. The Mentagon is a 5-sided
virtual map where all new players in Hilbert Space start. A Hexmosphere
Hilbert Space is a virtual world encoded in a database, based on the H3
coordinate system which maps real globe-based geography onto a wrappable
hexagonal grid.

Since it is mathematically impossible to perfectly tile a sphere with
hexagons, H3 includes 12 pentagons at various sensible locations (in both
the topological and geographical senses). New players will enter the virtual
world without reference to real location (hence, Mentagon). However, as
they progress through their understanding of the virtual world, they will
be able to "anchor" themselves in one of the real-world analogous pentagons.

Aside: An interesting topic of research, would be the fraction of human
population that literally lives in one of the "big pentagons" on an H3 grid.
I currently believe this to be a small-ish fraction, as the pentagons are
all centered on oceanic terrain.

As we develop the engine, players of Federation 3 will be able to collectively
"claim" large hexagons based on TBD criteria. Eventually, we will want to
subdivide the virtual territory into smaller sections. In H3, this is known
as increasing the resolution of the grid. The criteria for increasing the
resolution will involve some critical mass of players choosing to center
their "home hex" in a particular reality-corresponding zone.

## Tech
H3 is a particular method of aggregating data across general segments of
real geography. A particular human's geographic location is sensitive /
private data. Thus, great care must be made, as geographic location is
more personal the *more specific* it is, coupled to digital identity. The
resolutions used for H6 will be reasonably large, but some of the specific
pentagons are large population centers:
https://observablehq.com/@nrabinowitz/h3-index-inspector#801dfffffffffff%2C8031fffffffffff%2C8063fffffffffff%2C8075fffffffffff%2C804dfffffffffff%2C80c3fffffffffff%2C80a7fffffffffff%2C8009fffffffffff%2C807ffffffffffff%2C8091fffffffffff%2C80d7fffffffffff%2C80ebfffffffffff

Early on, we can highlight the fact that our technology can de-anonymize
in two ways: we receive some geographic information based on IP address,
and we receive some geographic information based on user-selected data --
including time zone, time of logged-in activity, and a variety of other
general location-based self-reported information like city of residence.


## Knowledge Base

20 subjects! This will be controversial.

* Music
* Language Arts
* Fine Arts
* Martial Arts
* Physics
* Economics
* Statistics
* Maths
* Sociology
* Psychology
* Biology
* Zoology
* History
* Geography
* Politics
* Government
* Some Type of Dance
* Philosophy
* Personal Health
* Astronomy
