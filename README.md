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
.m<`b \| t \| r \| l \| x \| y`>-<`1-5`>  | margin <`bottom \| top \| right \| left \| x(left and right) \| y(top-botton)`>
.p<`b \| t \| r \| l \| x \| y`>-<`1-5`>  | padding <`bottom \| top \| right \| left \| x(left and right) \| y(top-botton)`>

#### Sizing & Borders

Class Name | Description
---------- | -----------
.<`w \| h`>-<`1-100`> | width or height in terms of % from 1-100
border-<`top \| right \| left \| bottom`> | border on the top, right, left and bottom
.border-`<primary \| secondary \| success \| info \| warning \| danger \| light \| dark \| white \| muted>` | border with colors `<blue \| gray \| green \| light blue \| yellow \| red \| very light grey \| black \| white \| blur gray>`
.rounded-<`top \| bottom \| left \| right \| circle \| 0`> |rounded border at top, bottom, left, right, circle and no border

## CSS Components

#### Button & Button Groups

Class Name | Description
---------- | -----------
.btn-<`outline`>-<`primary \| secondary \| success \| info \| warning \| danger \| light \| dark \| link`> | btn color (with or without line) blue, gray, green, light blue, yellow, red, very light gray, black, button as link
.btn-<`sm \| lg \| block`> |  button small, large or block type i.e. extending entire conatiner width
.btn-group | to group multiple buttons together
.btn-group-vertical | to group buttons vertically
.btn-toolbar | to group multiple button groups `.btn-group`
.dropdown-toggle | add a dropdown caret button

```
  <!-- BUTTON DROPDOWNS -->
        <div class="dropdown">
            <button class="btn btn-primary dropdown-toggle" type="button"
            data-toggle="dropdown">
                My Dropdown
            </button>
            <div class="dropdown-menu">
                <a class="dropdown-item" href="#">Link One</a>
                <a class="dropdown-item" href="#">Link Two</a>
                <div class="dropdown-divider"></div>
                <a class="dropdown-item" href="#">Link Three</a>
            </div>
        </div>
```
#### Navbar & Navs

Class Name | Description
---------- | -----------
nav.navbar | creates a standard navbar
nav.navbar-expand-`<sm \| md \| lg \| xl>`| expand the navbar from vertical to horizontal depending on the option
.navbar-brand | brand of the application or navbar
ul.navbar-nav | actual navbar menu normal
ul.nav ul.nav-pills | to use for submenu page
li.nav-item | nav menu items
a.nav-link | link of the nav menu items
button.navbar-toggler with data-toggle="collaspe" data-target=`<id>` | create a toggle button to collaspe depending on `nav.navbar.expand-<option>` value
div.collaspe .navbar-collaspe id=`<data-target>`| the target wrapper div for collasping
span.navbar-toggler-icon | create a standard toggle button
form.form-inline | to create inline form within a div
.ml-auto | align object on the right
.mr-auto | align object on the left
div.dropdown | to create dropdown menu or information
button.dropdown-toggle & data-toggle="dropdown" | button for the dropdown
div.dropdown-menu | dropdown menu
.dropdown-item | dropdown menu items
.navbar-`<light \| dark>` | to have navbar text light or dark
.fixed-`<top \| bottom>` | to have object fixed at top or bottom
.sticky-`<top \| bottom>` | to have object stick to top or bottom when you move to it
.justify-content-`<center \| right>` | to justify and move to center or right
.flex-column | to align vertically
.nav-fill | justify menu items

