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

#### List Groups & Badges

Groups are fancy unordered lists.

Class Name | Description
---------- | -----------
ul.list-group | unordered list of group of items
.list-group-item | items of the group
.list-group-item-`<primary \| secondary \| success \| info \| warning \| danger \| light \| dark>` | to have multi color group items
ul.list-group-flush | do not want border all around only at the bottom
.badge .badge-`<primary \| secondary \| success \| info \| warning \| danger \| light \| dark>`| to create a badge with a specific color.

#### Forms & Input

Class Name | Description
---------- | -----------
.form-group | to group one form for e.g. a label and an input field
.form-control | to make input/select/textarea look beautiful
.form-control-`< lg \| sm >` | to have form input/select/textare large or small
.form-control-file | to make input file type look better
.form-text | to have text with form items
.custom-file | to have a better looking file input
.custom-file-input | to have a better looking file input for `.custom-file`
.custom-file-label | to have a better looking file label for `.custom-file`
.custom-range | to have range look beautiful
form.form-inline | to have inline form for login or so
.form-check | to have a nice looking checkbox for e.g. remember me
.form-check-label | label for form check
.form-check-input | checkbox
input.is-valid | green border to the input
input.is-invalid & invalid-feedback | red border to the input to `invalid-feedback` show/hide the message depending on validation

#### Input Groups & Addons

To group input together with symbol or some addons.

Class Name | Description
---------- | -----------
div.input-group | to have a div for the input group that goes together
div.input-group-`<prepend \| append>` | to prepend/append something mostly its text or icon 
.input-group-text | to make the text look beautiful in an input group

```
<!-- BASIC INPUT GROUPS -->
    <div class="input-group mb-3">
        <div class="input-group-prepend">
            <span class="input-group-text">@</span>
        </div>
        <input class="form-control" type="text" placeholder="Username">
    </div>
```

#### Alerts & Progress Bars

Class Name | Description
---------- | -----------
.alert .alert-`<primary \| secondary \| success \| info \| warning \| danger \| light \| dark>` | to create an simple alert with specific color
.alert-dismissible | see the example how to use it
.progress | to create a progress bar
.progress-bar | to create and fill the bar see the code below
.progress-bar-stripped | to make stripped progress bar
.progress-bar-animated | to make progress bar animated

```
<!-- DISMISSABLE ALERT -->
    <div class="alert alert-success alert-dismissible">
        <button class="close" type="button" data-dismiss="alert">
            <span>&times;</span>
        </button>
        <strong>Dismissable</strong> Blog post added
    </div>
```

```
<!-- PROGRESS BAR -->
<div class="progress">
    <div class="progress-bar bg-sucess" style="width:35%;">35%</div>
</div>
```

#### Tables & Pagination

Class Name | Description
---------- | -----------
table.table | to create basic table
table.table-dark | to make dark table
thead.thead-dark | to make table head dark
table.table-`< stripped \| bordered \| borderless \| hover >` | to make table stripped/bordered/borderless/hover(row hovering)
tr.table-`<primary \| secondary \| success \| info \| warning \| danger \| light \| dark>` | to have colored row of the table
div.table-responsive | to add scrollbar on the div in which table would be there on smaller devices.
ul.pagination | to make a pagination see example below
li.page-item | to make a list of pagination items
a.page-link | to have page link

```
<!-- PAGINATION WITH ARROWS -->
<nav>
    <ul class="pagination">
        <li class="page-item disabled">
            <a class="page-link" href="#">
                <span>&laquo;</span>
                <span class="sr-only">Previous</span>
            </a>
        </li>
        <li class="page-item active">
            <a class="page-link" href="#">1</a>
        </li>
        <li class="page-item">
            <a class="page-link" href="#">2</a>
        </li>
        <li class="page-item">
            <a class="page-link" href="#">3</a>
        </li>
        <li class="page-item">
            <a class="page-link" href="#">
                <span>&raquo;</span>
                <span class="sr-only">Next</span>
            </a>
        </li>
    </ul>
</nav>
```

#### Cards

Class Name | Description
---------- | -----------
.card | to make a card wrapper
.card-header | to make a card header within `.card`
.card-body | to make a card text within `.card`
.card-title | to have a card title within `.card-body`
.card-subtitle | to have a card subtitle within `.card-body`
.card-text | to have a card text within `.card-body`
.card-img-top | to have image before the `.card-body` within `.card`
.card-footer | to make a card footer within `.card`

```
<!-- CARD WITH IMAGE -->
<div class="card">
    <img class="card-img-top" src="https://source.unsplash.com/random/300x200" alt="">
    <div class="card-body">
        <h4 class="card-title">Card Title</h4>
        <p class="card-text">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Illo, quas.</p>
        <a class="btn btn-success btn-block" href="#">Read More</a>
    </div>
</div>
```

```
<!-- HEADER, FOOTER, CENTERED -->
<div class="card text-center">
    <div class="card-header">
        My Card
    </div>
    <div class="card-body">
        <h4 class="card-title">Card Title</h4>
        <p class="card-text">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aut, perspiciatis.</p>
        <a class="btn btn-dark" href="#">Read More</a>
    </div>
    <div class="card-footer text-muted">
        2 Days Ago
    </div>
</div>
```

```        
<!-- CARD WITH NAV -->
<div class="card">
    <div class="card-header">
        <ul class="nav nav-tabs card-header-tabs">
            <li class="nav-item">
                <a class="nav-link active" href="#">Active</a>
            </li>
            <li class="nav-item">
                <a class="nav-link" href="#">Link</a>
            </li>
            <li class="nav-item">
                <a class="nav-link disabled" href="#">Disabled</a>
            </li>
        </ul>
    </div>
    <div class="card-body">
        <h4 class="card-title">Card Title</h4>
        <p class="card-text">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aut, perspiciatis.</p>
        <a class="btn btn-primary" href="#">Read More</a>
    </div>
</div>
```

#### Media Objects

Class Name | Description
---------- | -----------
.media | to make a div with image and text aligned next to each other
.media-body | to make a media body
img.align-self-`<start \| center \| end>` | to align image top/middle/bottom

#### Jumbotron

Class Name | Description
---------- | -----------
.jumbotron | to make the div more prominent
.jumbotron-fluid | to extend the div to the entire width

## Grid System and Flexbox

#### Grid System

Class Name | Description
---------- | -----------
.row | to create a row
.col-`<sm \| md \| lg \| xl>`-`<1-12>` | to make columns in the `.row`
.order-`<number>` | order the column depending upon how many columns are there
.offset-`<sm \| md \| lg \| xl>`-`<1-12>` | offset the column on how much you want to push

```
<!-- RESPONSIVE GRID -->
<div class="row">
    <div class="col-sm-6 col-md-8 col-lg-9 col-xl-10" style="border:1px solid #333">
    <ul>
        <li>6 column on small screens</li>
        <li>8 column on medium screen</li>
        <li>9 column on large screen</li>
        <li>10 column on xlarge screen</li>
    </ul>
    </div>
    <div class="col-sm-6 col-md-4 col-lg-3 col-xl-2" style="border:1px solid #333">
    <ul>
        <li>6 column on small screens</li>
        <li>4 column on medium screen</li>
        <li>3 column on large screen</li>
        <li>2 column on xlarge screen</li>
    </ul>
    </div>
</div>
```

#### Grid Alignment

Class Name | Description
---------- | -----------
div.row .align-items-`<start \| center \| end>` | align the text in top/middle/bottom
div.col .align-self-`<start \| center \| end>` | aling only the specific column to top/middle/bottom
.justify-content-`<start \| center \| end \| around \| between>` | to align column left/middle/right/to add spacing around the content/ to add the extra space in between
.no-gutters | to have no space among columns when they are not in same row

#### Flexbox

Class Name | Description
---------- | -----------
.d-flex | to make it flex
.flex-row-reverse | to reverse the order of the flex items
.d-flex .flex-column | to arrange in column

#### Auto Margins & Wrapping

Class Name | Description
---------- | -----------
`<ml \| mr \| mb \| mt >`-auto | to push items right/left (it's opposite) /bottom/top.
.flex-wrap | to wrap the flex items so that it doesn't go out of page