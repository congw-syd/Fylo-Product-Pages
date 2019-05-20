# Fylo-Product-Pages
Practice HTML, CSS to design responsive pages.

## Tricks learned
### Box Sizing
to manage responsive pages
```css
*, *:before, *:after {
  box-sizing: border-box;
}
```
### Table Technique
to make an element in the absolute center of the screen 
```html
<!-- HTML -->
<table id="wrapper">
  <tr>
    <td><img src="logo.png" alt="" /></td>
  </tr>
</table>
```
```css
/* CSS */
html, body, #wrapper {
   height:100%;
   width: 100%;
   margin: 0;
   padding: 0;
   border: 0;
}
#wrapper td {
   vertical-align: middle;
   text-align: center;
}
```
