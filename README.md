# ClickService

Allows managing click, long click and double click in the same element.

Can be used importing the module 'ClickService'.
To the object constructor pass double click and long click delays (300 and 1000 ms by default).

Call clickCall, dblClickCall, longClickCall, longClickEndCall passing a handler if that
event is going to be used.

In the html element, attach click event to click() method and mouse down event to mouseDown() (this one is only needed if long click is going to be used).
