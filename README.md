# Boxes
## Box Dimensions( width, height)
### By default a box is sized just big enough to hold its contents. To set your own dimensions for a box you can use the height and width properties.
### The most popular ways to specify the size of a box are to use pixels, percentages, or ems. Traditionally, pixels have been the most popular method because they allow designers to accurately control their size.
### When you use percentages, the size of the box is relative to the size of the browser window or, if the box is encased within another box, it is a percentage of the size of the containing box.
### When you use ems, the size of the box is based on the size of text within it. Designers have recently started to use percentages and ems more for measurements as they try to create designs that are flexible across devices which have different-sized screens.
![Box dimensions](https://user-images.githubusercontent.com/70091044/92375340-a72d8780-f109-11ea-89ab-e685ea3803fe.PNG)
## Limiting Width (min-width, max-width)
### Some page designs expand and shrink to fit the size of the user's screen. In such designs, the min-width property specifies the smallest size a box can be displayed at when the browser window is narrow, and the max-width property indicates the maximum width a box can stretch to when the browser window is wide.
## Limitig Height (min-height, max-height)
### In the same way that you might want to limit the width of a box on a page, you may also want to limit the height of it. This is achieved using the min-height and max-height properties.
## Overflowing Content
## overflow
### The overflow property tells the browser what to do if the content contained within a box is larger than the box itself. It can have one of two values:
### *hidden*: This property simply hides any extra content that does not fit in the box.
### *scroll*: This property adds a scrollbar to the box so that users can scroll to see the missing content.
![overflow](https://user-images.githubusercontent.com/70091044/92376169-da244b00-f10a-11ea-873d-a1e87440dfd2.PNG)
## Border, Margin & Padding
### Every box has three available properties that can be adjusted to control its appearance:
![border](https://user-images.githubusercontent.com/70091044/92376401-32f3e380-f10b-11ea-8fa0-29a0357a6c14.PNG)
## Border Width (border-width)
### The border-width property is used to control the width of a border. The value of this property can either be given in pixels or using one of the following values:

- [x] thin

- [x] medium

- [x] thick

####(You cannot use percentages with this property.)
### You can control the individual size of borders using four separate properties:

- [x] border-top-width

- [x] border-right-width

- [x] border-bottom-width

- [x] border-left-width

### You can also specify different widths for the four border values in one property, like so:
### border-width: 2px 1px 1px 2px;
#### The values here appear in clockwise order: top, right, bottom, left.
![border width](https://user-images.githubusercontent.com/70091044/92377499-e7dad000-f10c-11ea-9285-b2ca84c48e68.PNG)
## Border Style (border-style)
### You can control the style of a border using the border-style property. This property can take the following values:

- [x] solid a single solid line 

-[x] dotted a series of square dots (if your border is 2px wide, then the dots are 2px squared with a 2px gap between each dot)

- [x] dashed a series of short lines

- [x] double two solid lines (the value of the border-width property creates the sum of the two lines)

- [x] groove appears to be carved into the page

- [x] ridge appears to stick out from the page

- [x] inset appears embedded into the page

-[x] outset looks like it is coming out of the screen

-[x] hidden / none no border is shown

### You can individually change the styles of different borders using: border-top-style, border-left-style, border-right-style, border-bottom-style
