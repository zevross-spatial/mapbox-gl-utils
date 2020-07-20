## Change log

### 0.31.0

* Major refactor of the codebase to clean up some scoping issues, and allow multiple copies of mapbox-gl-js to exist, attached to different map instances.
* New function, utils.newMap() which instantiates the map object and allows manipulating the style before it loads.