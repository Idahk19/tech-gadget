# CSS Selection Challenge

## Project Overview

This project demonstrates the use of advanced CSS selectors, combinators, pseudo-classes, and responsive CSS units to style a product comparison layout without relying on excessive classes.

The design focuses on clean and efficient CSS targeting methods while creating a responsive and visually appealing product grid.

---

# Features Implemented

## Responsive Layout

* Used `max-width` with `rem` units for the main container.
* Used percentage widths `%` for product cards.
* Used `em` units for scalable spacing and padding.
* Applied responsive flexbox layout for the product grid.

---

# CSS Selectors & Combinators Used

## Universal Selector

```css
*{
    box-sizing: border-box;
}
```

Applies consistent sizing behavior across the entire page.

---

## Pseudo-class Selector

```css
article:first-of-type
```

Targets only the first product card and highlights it with a gold border.

---

## Descendant Combinator

```css
footer a
```

Styles all links placed inside the footer section.

---

## Child Combinator

```css
.price-tag > span
```

Styles only the direct span child inside the price tag container.

---

## Adjacent Sibling Combinator

```css
h2 + div
```

Targets a div that immediately follows a heading.

---

## Hover Pseudo-class

```css
button:hover
```

Changes button background color when hovered.

---

## Structural Selector

```css
.features li:nth-child(even)
```

Highlights every even row in the features list.

---

# Technologies Used

* HTML5
* CSS3

---

# Learning Objectives

This project helped practice:

* CSS combinators
* Structural pseudo-classes
* Responsive CSS units
* Layout styling with Flexbox
* Efficient element targeting without overusing classes

---

# Author

Idah Karwitha
