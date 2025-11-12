# Using JS Promises in React

### Code analyse questions

---

##### 1. What part of the code defines the window title?

The part of code that defines window title is the tag `<title>` in the `index.html`.

##### 2. Why is className used in the index file?

`className` is used to apply css stylization in an especific element in the page. In the `indicators-index.css` file, the className is used to call the div that has this element.

##### 3. What part of the code is responsible for making the white card appear centered on the page?

It's the `.card` element in the CSS, it styles the card to appear centered on the page by adjusting its width and using display flex.

##### 4. In which file are the colors, spacing, and fonts defined?

In the `indicators-index.css`, this file contains the stylization of the `IndicatorsIndexPage.jsx` and defines the colors spacing and fonts, before applying the render.

##### 5. What does the element th do?

Creates a table header for a new table, one th tags equals one header for the table.

##### 6. What does data.map do in the index file?

The `data.map` in the index file, receive rows and i as argument, i is a indentifier for the index of the data, for each unique id of data, it gets the row info and maps as a new element of the table, creating the rows of the table.

##### 7. What element represents a header cell within a table row?

The `name` element of a row of the table represents the header cells.

##### 8. What element represents a standard data cell within a table row?

The `dimension` element represents a standard data cell within a table row.

##### 9. If we wanted to display only one static row instead of multiple indicators, what part of the code could we remove or simplify?

We should simplify the `data.map` function, we get the index of the desirable object to display from the data array and pass this as argument on the map funcion.

##### 10. What CSS rule defines the background color of the entire page, and what variable is used for it?

The variable is --bg, the CSS rule that defines the background color of the entire page is `background`.

---
