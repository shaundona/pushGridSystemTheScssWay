# Pencil & Fox SASS push left grid system
Open-source stylekit generator, optimized for quick reusable frontend styling

## How it works
- The grid.scss file creates a grid system based on columns having a left margin space.
- To define grid columns for desktop and responsive devices, gutter space just update the variables at the top of grid.scss file.
- [Based on thoughtbot blog post] (https://robots.thoughtbot.com/building-the-future-of-floated-css-grids)

Grid follows this equation:
width: calc(percentage($columns / $grid-columns) - $grid-gutter + ($grid-gutter * percentage($columns / $grid-columns)));

## Demo
- https://www.pencilandfox.getforge.io/scrummylibrary/responsive-SCSS-grid

## Requirements
- SASS compiler

## Version
- Version 1.0
