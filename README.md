# PrecisionSketch

A 2D drawing tool for engineers: sketch shapes with CAD-style constraints and dimensions (as in Onshape or SolidWorks sketch mode), style them, and drop the result into PowerPoint or Visio.

**Live site:** https://andrew3201.github.io/precisionsketch/

- Constraint solver written from scratch in plain JavaScript (Levenberg–Marquardt, analytic Jacobians, degrees-of-freedom coloring).
- Lines, corner and center rectangles, center and 3-point circles, 3-point, center-point and tangent arcs, ellipses, polygons, slots, splines, points and text.
- Type a size while drawing (a length, `40, 25` for a rectangle, a diameter or a radius) and the dimension is added for you.
- Trim, extend, split, fillet, chamfer, offset, mirror, linear and circular patterns, and move / rotate / scale by exact values.
- Copy, cut, paste and duplicate (Ctrl+C / X / V / D) with constraints and styling carried along.
- Variables and expressions in dimensions (`width/2 + 3`, `1.5 in`).
- Layers, groups, stacking order, align and distribute, arrowheads, gradients, page presets, light and dark themes.
- Export SVG (true size, PowerPoint-friendly), PNG with physical size, vector PDF and DXF; copy as image.

The whole app is one self-contained `index.html` with no dependencies.
