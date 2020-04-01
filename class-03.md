### class 03 reading - my cheatsheet 

### Ordered Lists : 
<ol></ol> - ordered list
<li></li> - lists
ie. recipe numbered instructions

### Unordered Lists :
<ul></ul> - bullet points
<li></li> - the lists go within the other elements such as <ul></ul> and <ol></ol>

### Definition Lists :
<dl></dl> - list is created and usually consists of a series of terms and their definitions.
<dt></dt> - usually found within the <dl> element
<dd></dd> - " "

Nested Lists : see ex. below

<ul>
    <li>
        <ul>
        <li>
        </li>
        </ul>
    </li>
</ul>

### Boxes: 
* controling size
* box models for borders, margin & padding
* displaying & hiding


### width, height - Box Dimensions
html + css 
pg. 303

<div>
    <p>
    </p>
</dev>

^as html, then into css below

div {
    height: 300px;
    width: 400px;
    background-color: #ee3e80;
}

p {
    height: 300px;
    width: 400px;
    background-color: #ee3e80;
}

### Limiting Width - min-width, max-width
html + css 
pg. 304

### Limiting Height - min-height, max-height
html + css 
pg. 305

### Overflowing Content - overflow
html + css 
pg. 306

### Border, Margin & Padding 
html + css 
pg. 307

### White Space & Vertical Margin
html + css 
pg. 308

### Borders - 
    border width : border-width 
    border style : border-style
    border color : border-color
    shorthand : border
html + css 
pg. 309 - 312

    padding : padding
    margin : margin
html + css 
pg. 313 - 314

    centering content : center
    IE6 box model 
    change inline/block : display
    hiding boxes : visibility
    Css3 border images : border-image
    Css3 box shadows : box-shadow
    Css3 rounded corners : border-radius
html + css 
pg. 315 - 322

### Decisions + Loops
    Evaluations => Decisions => Loops
    decision making 
    evaluation conditions & conditional statements
javascript
pg. 148 - 149

    comparison operators: evaluating conditions
    == : is equal to
    != : is not equal to
    === : strict equal to
    !== : strict NOT equal to
    > : greater than
    < : less than
    >= : greater than or equal to
    <= : less than or equal to
javascript
pg. 150 - 151

    structuring comparison operators
        ex. 
        (score >= pass)
        perand   operand
               |
        comparison operator
javascript
pg. 152

    using comparison operators - pg. 153
    using expressions with comparison operators - pg. 154 
    comparing two expressions - pg. 155
    logical operators - pg. 156 - 157
    && : logical AND 
    || : logical OR
    ! : logical NOT
    short-circuit evaluation
        false && anything = it has found a false
        true || anything = it has found a true
    using logical AND - pg. 158
    using logical OR & logical NOT - pg. 159
    
### if statements 
    using if statements
    if... else statements
    using if... else statements
javascript
pg. 158 - 163   

### switch statements
ex.
    switch (level) {
        case 'One':
        title = 'Level 1';
        break;

        case 'Two':
        title = 'Level 2';
        break;

        case 'Three':
        title = 'Level 3';
        break;

        default:
        title = 'Test';
        break;

    }

    using switch statements - pg. 164
    type coercion & weak typing - pg. 166
    truthy & falsy values - pg. 167    
    checking equality & existence - pg. 168
    short circuit values - pg. 169
### loops
    loop counters - pg. 171
    looping - pg. 172 - 173
    key looping concepts - pg. 174
    using # FOR loops - pg. 175
    using # WHILE loops - pg. 176
    using # DO while loops - pg. 177
    examples - pg. 179

