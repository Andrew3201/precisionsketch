# PrecisionSketch

A 2D drawing tool for engineers: sketch shapes with CAD-style constraints and dimensions (as in Onshape or SolidWorks sketch mode), style them, and drop the result into PowerPoint or Visio.

**Live site:** https://andrew3201.github.io/precisionsketch/

- Constraint solver written from scratch in plain JavaScript (Levenberg–Marquardt, analytic Jacobians, degrees-of-freedom coloring).
- Lines, rectangles, circles, arcs, ellipses, polygons, slots, splines, points and text.
- Trim, extend, split, fillet, chamfer, offset, mirror, linear and circular patterns.
- Variables and expressions in dimensions (`width/2 + 3`, `1.5 in`).
- Layers, groups, stacking order, align and distribute, arrowheads, gradients, page presets.
- Export SVG (true size, PowerPoint-friendly), PNG with physical size, vector PDF and DXF; copy as image.

The whole app is one self-contained `index.html` with no dependencies.
