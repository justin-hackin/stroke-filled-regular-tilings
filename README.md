# Stroke-Filled Regular Tilings 

This is a collection of regular tilings as sourced from the Wikipedia entry [Euclidean tilings by convex regular polygons](https://en.wikipedia.org/wiki/Euclidean_tilings_by_convex_regular_polygons). The SVG files have been modified such that:

* one or more paths have been combined into a single path
* this single path has no stroke and its fill is the result of performing a "Stroke to fill" operation on the boundary lines of the regular tiling

These files are published with the intent of providing sample resources for those that wish to experiment with the [Polyhedral Decoration Studio](http://bit.ly/polyhedz-deco). 

## Contributing guidelines

This collection is NOT a comprehensive conversion of all regular polygon Euclidean tilings; it is a curated selection of the most attractive and functional tilings for making shadow-casting patterns on polyhedral sculptures. You are welcome to contribute to this curation. See a tiling that's not in this repo and think it should be? Then feel free to make a PR to add your favorites(s).

### SVG conversion instructions 

1. Download the SVG file for the tiling you like, preserving it's original name.
2. Open the file with [Inkscape](http://inkscape.org).
3. Select all content (Edit -> Select All).
4. Perform the ungroup operation (Object -> Ungroup) repeatedly until no groups are in the selection (notice the selection info at the bottom of the Inkscape window). All of the items in the selection should be paths.
5. Make the selection into one path (Path -> Combine).
6. Optionally, adjust the stroke width by double-clicking the number beside "Stroke:" in the lower left corner and edit the number in the dialog that appears. Thinner strokes may be delicate and subject to tearing. Making the stroke too thick can cause holes to become too small; small holes' material often gets stuck dangling to the pattern when cut out with laser cutters or home die cut machines. You can use the existing tilings as a guide to finding this balance.
7. Now perform (Path -> Stroke to path). 
8. For consistency's sake, please ensure the fill of the new path is black. You can click the black square in the color palette to change the fill of the currently selected path.

## Attribution

The following files are derivatives of [Tomruen](https://en.wikipedia.org/wiki/User:Tomruen)'s work and are thus published under a Attribution-ShareAlike 4.0 International license.
