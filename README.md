Drag-Data
=========

A Live Widget that copies a the value of the data-data attribute on a DOM element into a drag event on that DOM element to allow transfer of the value of data-data to the drop target of the drag event.


```html


						<div draggable="true"
						     data-widget="drag-data"
						     data-data="' + encodeURIComponent(JSON.stringify(data)) + '">

            </div>

```
