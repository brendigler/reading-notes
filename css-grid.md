# CSS Grid
> In the same way that flexbox gave us a way to layout block elements next to each other, CSS grid lets us not only arrange elements in a row or a column, but in multiple rows and columns.

Grid is the most powerful layout system available in CSS. 
It is 2-dimensional, unlike flexbox. 
Grid is applied both to parent (*Grid container*) elements and children (*Grid item*) elements. 

> CSS has always been used to lay out our web pages, but it’s never done a very good job of it

Grid is actually designed for layout from the ground up. Phew. 

how-to: 

    <div class="container">
      <div class="item item-1"> </div>
      <div class="item item-2"> </div>
      <div class="item item-3"> </div>
    </div>
    
Grid line: dividing line that makes up the structure of the grid. Row or Column.

Grid Track: space between adjacent grid lines

Grid area: total space surrounded by four grid lines

Grid Item: childen (direct descendants) of the grid container. `sub-item` can live inside 

grid cell: space between two adjacent grid lines. *single unit* of the grid
