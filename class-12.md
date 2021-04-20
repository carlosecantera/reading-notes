# Chart JS

## How to create a chart

- The script used to creat a chart is `<canvas>.

## Canvas element

`<canvas> element is is used to draw different kinds of things.

- Canvas' shape can be changed to any variety of sizes but initially its dimensions 300px x 150px.

-Fallback content - THis is the abilty to insert alternative content within the canvas element so in case the user's browswer is unable to see the the canvas you've built.


## Drawing Shapes

**Rectangles**

1.Filled
2.Outline
3.Transparent

**Paths**
1. `(beginpath)` -creates a new path
2. Path Methods - method for objects to have their own path.
3. `closePath()` - adds a straight line
4. `stroke()` - drase a shape
5. `fill()` - draw solid shape

**Lines**

`lineTo(x, y)` - Draws a line

**Arcs**

`arc(x, y, radius, startAngle,endAngle, counterclockwise)` - This draws an arc.

## Applying style and color

- fillStyle = color
- strokeStyle = color
- golbalAplpha = trasparencyValue
- lineWidth = value
- lineCap = type
- lineJoin = type
- miterLimit = value
- `getLineDash()`
- `setLineDash(segments)`
- lineDashOffset = value

## Drawing text

There are two methods to render text

`fillText (text, x, y [, maxwidth])`
`strokeText (text, x, y [, maxwidth])`