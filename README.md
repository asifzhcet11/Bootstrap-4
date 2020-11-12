# Bootstrap-4
Documentation for bootstrap 4 classes

## Typography & Utilities

#### Text and Unordered Lists

Class Name | Description
---------- | ------------
.lead | makes the text leading (Grey bigger)
.text-monospace | making text in monospace format
.font-weight-bold | make text bold
.font-weight-normal | make text normal (looks better than normal html text)
.font-italics | make text italics
.text-lowercase | convert text to lowercase
.text-uppercae | convert text to UPPERCASE
.text-capitalize | convert text to Camel Case
.text-right | make the text go to right
.text-truncate | make the text truncate...
.ul.list-unstyled | make the unordered list look better
.ul.list-inline | make unordered list inline
.li.list-inline-item | make list items of `ul.list-inline ` list inline  

#### Text Alignment and Display

Class Name | Description
---------- | -----------
.text-left | align text left
.text-right | align text right
.text-center | align text center
.text-justify | make text justified in a container
.text-`<sm \| md \| lg \| xl>`-`<left \| right \| center>` | for eg. text-sm-right will make text aligned right on small or larger devices
.d-inline | convert block(extends 100% width) level to inline(extends only till the content)
.d-block | make the inline level to block level
.d-inline-block | create multiple inline level into block levels

#### Float and Fixed Position

Floats are used for block-level element like `<div></div>`

Class Name | Description
---------- | -----------
.float-`<right \| left \| none>` | div on right, left or none.
.float-`<sm \| md \| lg \| xl>`-`<right \| left \| none>` | for e.g. float-sm-right will make div on left side for small or larger devices
.clearfix | to clear the area so that whatever comes next goes down rather than aligning within same element.
.fixed-`<top \| bottom>` | to keep the element fixed at top for e.g header
.sticky-top | to keep the element sticky when we scroll to the element

#### Colors & Background

Class Name | Description
---------- | -----------
.`<text \| bg>`-`<primary \| secondary \| success \| info \| warning \| danger \| light \| dark \| white \| muted>` | `<text color \| background>` : `<blue \| gray \| green \| light blue \| yellow \| red \| very light grey \| black \| white \| blur gray>`

#### Margin & Padding Spacing

Class Name | Description
---------- | -----------
m<`b \| t \| r \| l \| x \| y`>-<`1-5`>  | margin <`bottom \| top \| right \| left \| x(left and right) \| y(top-botton)`>
p<`b \| t \| r \| l \| x \| y`>-<`1-5`>  | padding <`bottom \| top \| right \| left \| x(left and right) \| y(top-botton)`>

#### Sizing & Borders

Class Name | Description
---------- | -----------
<`w \| h`>-<`1-100`> | width or height in terms of % from 1-100
border-<`top \| right \| left \| bottom`> | border on the top, right, left and bottom
border-`<primary \| secondary \| success \| info \| warning \| danger \| light \| dark \| white \| muted>` | border with colors `<blue \| gray \| green \| light blue \| yellow \| red \| very light grey \| black \| white \| blur gray>`
rounded-<`top \| bottom \| left \| right \| circle \| 0`> |rounded border at top, bottom, left, right, circle and no border
