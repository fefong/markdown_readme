# Markdown - Extras


## Image Align

### Image Align - Middle _(default)_

Aenean eu euismod ante. Phasellus finibus nec est eget euismod.<img src="right-arrow.svg" width="42" height="42"> Duis pharetra sapien dolor, nec euismod nunc maximus ut. Fusce elementum tellus ac lacus ultrices, vel efficitur metus faucibus. Etiam sed egestas risus. Fusce quis ex lorem. Nullam aliquet ante vel mi ultrices, vel pretium nibh pretium. lobortis.

```html
<img src="right-arrow.svg" width="42" height="42">
```

### Image Align - Left

Lorem ipsum dolor sit amet, consectetur adipiscing elit.<img src="left-arrow.svg" alt="left face" align="left" width="42" height="42"> Fusce semper libero ligula, vel varius enim sagittis quis. Aenean sed massa velit. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia Curae; Cras faucibus consequat est eu varius. Nam vitae dignissim velit. 

```html
<img src="left-arrow.svg" alt="left face" align="left" width="42" height="42"> 
```

### Image Align - Right

Aenean eu euismod ante. Phasellus finibus nec est eget euismod.<img src="right-arrow.svg" alt="right" align="right" width="42" height="42"> Duis pharetra sapien dolor, nec euismod nunc maximus ut. Fusce elementum tellus ac lacus ultrices, vel efficitur metus faucibus. Etiam sed egestas risus. Fusce quis ex lorem. Nullam aliquet ante vel mi ultrices, vel pretium nibh pretium.

```html
<img src="right-arrow.svg" alt="right" align="right" width="42" height="42">
```

## Style Text


### keyboard input

<kbd>ALT + F4</kbd> 
```
<kbd>ALT + F4</kbd> 
```

### subscripted
normal text <sub>subscripted</sub> normal text
```
normal text <sub>subscripted</sub> normal text
```

### superscripted
normal text <sup>superscripted</sup> normal text
```
normal text <sup>superscripted</sup> normal text
```

## Table

### Table - _rowspan_
<table>
  <tr>
    <th>column 1</th>
    <th>column 2</th>
    <th>column 3</th>
  </tr>
  <tr>
    <td>row 1 - column 1</td>
    <td>row 1 - column 2</td>
    <td rowspan="2" align="center">row 1 & 2 - column 3</td>
  </tr>
  <tr>
    <td>row 2 - column 1</td>
    <td>row 2 - column 2</td>
  </tr>
</table>

```html
<table>
  <tr>
    <th>column 1</th>
    <th>column 2</th>
    <th>column 3</th>
  </tr>
  <tr>
    <td>row 1 - column 1</td>
    <td>row 1 - column 2</td>
    <td rowspan="2" align="center">row 1 & 2 - column 3</td>
  </tr>
  <tr>
    <td>row 2 - column 1</td>
    <td>row 2 - column 2</td>
  </tr>
</table>
```

### Table - _colspan_
<table>
  <tr>
    <th>column 1</th>
    <th>column 2</th>
    <th>column 3</th>
  </tr>
  <tr>
    <td>row 1 - column 1</td>
    <td colspan="2" align="center">row 1 - column 2 & 3</td>
  </tr>
  <tr>
    <td>row 2 - column 1</td>
    <td>row 2 - column 2</td>
    <td>row 2 - column 3</td>
  </tr>
</table>

```html
<table>
  <tr>
    <th>column 1</th>
    <th>column 2</th>
    <th>column 3</th>
  </tr>
  <tr>
    <td>row 1 - column 1</td>
    <td colspan="2" align="center">row 1 - column 2 & 3</td>
  </tr>
  <tr>
    <td>row 2 - column 1</td>
    <td>row 2 - column 2</td>
    <td>row 2 - column 3</td>
  </tr>
</table>
```
