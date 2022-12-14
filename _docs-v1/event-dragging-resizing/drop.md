---
title: drop
type: callback
since_version: 1.4.7
---

Called when a valid jQuery UI draggable has been dropped onto the calendar.

<div class='spec' markdown='1'>
function( *date*, *allDay*, *jsEvent*, *ui* ) { }
</div>

`date` holds the JavaScript Date object of where the draggable was dropped.

`allDay` holds a boolean of whether the draggable was dropped on an all-day cell (like in month view) or in a slot with a specific time (like in agenda view).

`jsEvent` holds the primitive JavaScript event, with information like mouse coordinates.

`ui` holds the jQuery UI information.

`this` holds the DOM element that has been dropped.

To see this callback function in action, view the [droppable](droppable) article or look at [this example](/releases/fullcalendar/1.6.6/demos/external-dragging.html).
