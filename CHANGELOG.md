# sigma.js - changelog:

## 2.2.0

### Features

- [#1161](https://github.com/jacomyal/sigma.js/issues/1161) - Adds `minZoom` and `maxZoom` settings
- [#1166](https://github.com/jacomyal/sigma.js/issues/1166) - Adds HTML colors support
- [#1167](https://github.com/jacomyal/sigma.js/issues/1167) - Adds events TypeScript types
- [#1176](https://github.com/jacomyal/sigma.js/issues/1176) - Cleans and improves event payloads
- [#1177](https://github.com/jacomyal/sigma.js/issues/1177) - Allows overriding arguments with `#graphToViewport` and `#vieportToGraph`
- [#1182](https://github.com/jacomyal/sigma.js/issues/1182) - Adds cached data (from custom reducers) to custom renderers
- [#1187](https://github.com/jacomyal/sigma.js/issues/1187) - Adds `forceLabel` for nodes and edges
- [#1188](https://github.com/jacomyal/sigma.js/issues/1188) - Drops `graphology-metrics` dependency

### Bug fixes

- _undocumented_ - Updates dependencies
- _undocumented_ - Fixes various bugs with the `node.image` program
- _undocumented_ - Fixes the `build/sigma.js` and `build/sigma.min.js` expositions of sigma
- [#1172](https://github.com/jacomyal/sigma.js/issues/1172) - Fixes labels grid display (changes which node labels are displayed by default)
- [#1192](https://github.com/jacomyal/sigma.js/issues/1192) - Fixes alpha blending for most recent WebGL layers
- [#1193](https://github.com/jacomyal/sigma.js/issues/1193) - Fixes dragging with mouse out of stage
- [#1194](https://github.com/jacomyal/sigma.js/issues/1194) - Fixes camera transitions to `angle: 0`
- [#1195](https://github.com/jacomyal/sigma.js/issues/1195) - Improves edge events handling (thanks to @avenzi)
- [#1199](https://github.com/jacomyal/sigma.js/issues/1199) - Fixes issue with hidden nodes and labels rendering (thanks to @avenzi)
- [#1200](https://github.com/jacomyal/sigma.js/issues/1200) - Fixes issue with node labels `""`
- [#1203](https://github.com/jacomyal/sigma.js/issues/1203) - Fixes examples build process

## 2.1.3

### Bug fixes

- [#1178](https://github.com/jacomyal/sigma.js/issues/1178) - Fixes uncaught error in Firefox when using node.image with images with no size
- [#1180](https://github.com/jacomyal/sigma.js/issues/1180) - Fixes edge events not being fired when edge size not set in the graph
- [#1183](https://github.com/jacomyal/sigma.js/issues/1183) - Moves edge labels layer behind nodes layer
- [#1186](https://github.com/jacomyal/sigma.js/issues/1186) - Fixes hovered nodes when mouse not hover sigma container

## 2.1.2

### Bug fixes

- [#1168](https://github.com/jacomyal/sigma.js/issues/1168) - Fixes hover and click events when mouse is hovering a hidden node
- [#1169](https://github.com/jacomyal/sigma.js/issues/1169) - Fixes x / y values in sigma events when mouse is not hovering the sigma container
- [#1173](https://github.com/jacomyal/sigma.js/issues/1173) - Fixes issue where unused program no longer deallocate back to zero
- [#1175](https://github.com/jacomyal/sigma.js/issues/1175) - Fixes zoom scrolling in a scrolled webpage

## 2.1.1

### Bug fix

- [#1165](https://github.com/jacomyal/sigma.js/issues/1165) - Fixes "ghost hovered nodes" issue

## 2.1.0

### Features

- _undocumented_ - Adds edge events
- _undocumented_ - Cleans and fixes all nodes and edges programs
- [#1153](https://github.com/jacomyal/sigma.js/issues/1153) - Adds double-click and wheel events for nodes and edges, with a new `#preventSigmaDefault()` method
- [#1149](https://github.com/jacomyal/sigma.js/issues/1149) - Graphology (and related libs) update to 0.22.1
- [#1102](https://github.com/jacomyal/sigma.js/issues/1102) - Allows custom node and edge label colors
- [#1150](https://github.com/jacomyal/sigma.js/issues/1150) - Adds public methods to enable implementing a proper PNG export, adds related [`png-export` example](https://codesandbox.io/s/github/jacomyal/sigma.js/tree/main/examples/png-snapshot)

### Bug fixes

- _undocumented_ - Edges thickness rendering is now pixel perfect at camera ratio 1, and no more twice bigger on Retina displays
- _undocumented_ - Cleans some browser warnings for
- [#1157](https://github.com/jacomyal/sigma.js/issues/1157) - Fixes unexpected node interaction with zIndex
- [#1148](https://github.com/jacomyal/sigma.js/issues/1148) - Fixes `mousemove` unexpected behaviors
- [#1163](https://github.com/jacomyal/sigma.js/issues/1163) - Implements edge labels ellipsis

## 2.0.0

- Complete rewrite of the library.
