# antlerworldmap
Map for Antler redesign


The Map is very basic. It works using a static world map as a background, then placing locations using EM coordinates. The style file in this repo contains most of the styling needed to make this happen - the commented sections refer to references to locations. I used a basic CMS to store these locations and then reference with the co-ordinates in EM referencing where they will sit on the map and the name, being of course,  the name. Using EM is crucial for this method so it stays consistently in the right spot on the  map no  matter the screen size.

These pointer events also help:

```
<style>
.collection-wrapper {pointer-events: none;}
.c-map_dot {pointer-events: auto;}
</style>
```
