# Day 12 Reading Notes

## Chart.js
To render a chart you need to add a node <.canvas> the cahrt should be in it's own container for responsiveness

Data Structures:
- primiitve: when data is in an array of numbers, values from labels array at the same index are used for the index axis (x for vertical, y for horizontal)
- object[]: used for parsed data. parsing may be disables by specifying parsing:false at chart options.
- object: in this mode property name is used for index scale and value for value scale. for vertical charts scale is x and value scale is y


You may use Global Configurations to keep your code DRY and to allow for making chages to chart across all pages

Chart Types:
- Line Chart
- Bar Chart
- Radar Chart
- Doughtnut & pie Chart
- polar Area Chart
- Bubble Chart
- Area Chart
- Mixed Chart Types

Axes:

Axes determine how data maps to a pixel values on a chart. There are different ways depending on the chart you would like to render
- Cartesian: 1 or more x & y values to map points on a 2D canvas
- Radial: a single axis that maps points in the angular & radial directions

When creating a chart the axes names should tell the viewer what data they are viewing.

[Back to Main](README.md)