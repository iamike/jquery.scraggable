**jQuery.scraggable** is a plugin that lets you drag elements by means of scrolling, single and multi dimensional (depends on browser).

To make elements scraggable just:

    $(selector).scraggable([options]);

# Options

## `axis`

Constrains dragging to either the horizontal (x) or vertical (y) axis. Possible values:

    'x', 'y', false

Default <code>false</code>

## `parent`

A DOM element which will receive the <code>mousewheel</code> event. Possible values:

    'selector', $('selector'), document.getElementById('elementId')

Default: <code>window.document</code>

## `sensitivity`

An abstract <code>float</code> value for scroll sensitivity to regulate dragging speed. Default: <code>1</code>

## `inverted`

<code>Boolean</code> value to invert dragging axis. Default: <code>false</code>

## `containment`

Constrains dragging to within the bounds of the specified element or region. Possible values:

     'parent', 'document', [x1, y1, x2, y2], false

Default: <code>false</code>

# Events

## `dragstart`

This event is triggered when dragging starts.

## `drag`

This event is triggered when the mouse is moved during the dragging.

## `dragstop`

This event is triggered when dragging stops

# Methods

## `enable`

Enable the scraggable.

## `disable`

Disable the scraggable.

# Compatibilty

Tested in:

* Chrome 9.0
* Firefox 3.6
* Opera 11 (single-dimensional)