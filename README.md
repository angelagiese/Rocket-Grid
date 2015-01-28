# Rocket-Grid
Mixins for an easy and lightweight grid system requiring no markup. Fixed gutter width and margins are responsive.

## About Rocket Grid
This is a LESS [LESS](http://lesscss.org/) mixin (Sass coming soon) which creates rows and columns for your build without adding extra markup to your HTML. You can set the number of columns, the width of the columns, and the width of the gutters between columns. Everything is responsive too.

The idea for this came from [Semantic.gs](http://semantic.gs/) but I needed a much simpler solution that would support fixed width gutters while still being responsive, plus I only build responsive solutions.This is the result.

## Usage
Simply include this file in your project and import in your LESS. Then you can get started utilizing the mixins.

<code>.row();</code> must be placed in the parent element's styles. You should also add a [clearfix](http://css-tricks.com/snippets/css/clear-fix/) for your child floating columns.

Now just use <code>.column(x)</code> in element styles & media queries to make the element into a column that's floating and has a fluid width.

### Examples
<code>.column(2);</code> takes up 2 columns on the grid
<code>.column(3);</code> takes up 3 columns on the grid
<code>.push(4);</code> adds 4 columns of space on the right
<code>.push(2);</code> adds 2 columns of space on the left