# Easel-Mosaic

Inventables Easel Mosaic App Challenge Entry  
by Thomas Suarez ([tomthecarrot](https://github.com/tomthecarrot))

Please see the [challenge forum post](https://discuss.inventables.com/t/mosaic-app-challenge/28873).

## Installation
1. Create a new app in Easel.
- Name it "Mosaic".
- Upload a thumbnail for the app.
- Check the box "Requires selected shape"
- Copy and paste the contents of `mosaic.js` into the Code window.
- Add each script in `lib/` to the Dependencies section.
- Save the app.

## Usage
1. Back in Easel, import an SVG or other type of design.
- Click the design object you want to "mosaic" (shift-click if there are multiple).
- From the Apps menu, choose the Mosaic app.
- Use the sliders and the preview to style it the way you want.
- Click the green Import button.
- Move each Mosaic piece where you want, then Carve! :)

**Tip:** If your design is too big for your 3D carving machine, you can use Mosaic to split it up into smaller jobs!
Simply follow the steps above, then "hide" the pieces you are not actively cutting by setting their *cut depths* to *0*.

### Dependencies

- [d3-path](https://github.com/d3/d3-path)
- [d3-shape](https://github.com/d3/d3-shape)
- [clipper and Easel helpers](https://gist.github.com/nevernormal1/b69139572185d7a2ef2dd6d6a3ea1a23)
