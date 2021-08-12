# CSS3 Tech

![CSS logo](https://cdn.pixabay.com/photo/2016/11/19/23/00/css3-1841590_960_720.png)
---

## Description

*What is CSS? CSS is the language for describing the presentation of Web pages, including colors, layout, and fonts. It allows one to adapt the presentation to different types of devices, such as large screens, small screens, or printers. CSS is independent of HTML and can be used with any XML-based markup language.*

### CSS Syntax:

![CSS Syntax](https://www.w3schools.com/css/img_selector.gif)

## Some of CSS Rules:
1. CSS Margins : The CSS margin properties are used to create space around elements, outside of any defined borders.

With CSS, you have full control over the margins. There are properties for setting the margin for each side of an element (top, right, bottom, and left).
#### Example

Set different margins for all four sides of a `<p>` element:
  
```CSS :
p {
  margin-top: 100px;
  margin-bottom: 100px;
  margin-right: 150px;
  margin-left: 80px;
}
```
---

2. CSS Borders : The CSS border properties allow you to specify the style, width, and color of an element's border.

#### Example

Demonstration of the different border styles:

```CSS :
p.dotted {border-style: dotted;
          border-style: solid;
          border-width: 5px;
          border-color: red;
          border-radius: 5px;
          }
```
---

3. CSS Padding : Padding is used to create space around an element's content, inside of any defined borders.

#### Example

Set different padding for all four sides of a ```<div>``` element:  
```CSS :
div {
  padding-top: 50px;
  padding-right: 30px;
  padding-bottom: 50px;
  padding-left: 80px;
}
```

---

4. CSS Height and Width :The CSS height and width properties are used to set the height and width of an element.

The CSS max-width property is used to set the maximum width of an element.

#### Example

Set the height and width of a ```<div>``` element:
  
  ```CSS : 
  div {
  height: 200px;
  width: 50%;
  background-color: powderblue;
}
  ```
  
  ---
  
  5. CSS Backgrounds : The CSS background properties are used to add background effects for elements.
  
  #### Example

The background color of a page is set like this:

```CSS :
body {
  background-color: lightblue;
}
```

---

6. CSS Links : With CSS, links can be styled in many different ways.

In addition, links can be styled differently depending on what state they are in.

The four links states are:

    - a:link  a normal, unvisited link
    - a:visited  a link the user has visited
    - a:hover  a link when the user mouses over it
    - a:active  a link the moment it is clicked

#### Example

```CSS :
 /* unvisited link */
a:link {
  color: red;
}

/* visited link */
a:visited {
  color: green;
}

/* mouse over link */
a:hover {
  color: hotpink;
}

/* selected link */
a:active {
  color: blue;
} 
```

---

7. CSS Layout - The position Property :The position property specifies the type of positioning method used for an element (static, relative, fixed, absolute or sticky).

#### The position Property

The position property specifies the type of positioning method used for an element.

There are five different position values:

    - static
    - relative
    - fixed
    - absolute
    - sticky

Elements are then positioned using the top, bottom, left, and right properties. However, these properties will not work unless the position property is set first. They also work differently depending on the position value.

#### Example

```CSS :
div.static {
  position: static;
}

div.relative {
  position: relative;
  }
  
  ```

---

8. CSS Opacity / Transparency : The opacity property specifies the opacity/transparency of an element.

The opacity property can take a value from 0.0 - 1.0. The lower value, the more transparent

#### Example

```CSS :
img {
  opacity: 0.5;
}
```

---

9. CSS Comments : CSS comments are not displayed in the browser, but they can help document your source code.

A CSS comment is placed inside the ```<style>``` element, and starts with ```/*``` and ends with ```*/```

#### Example

```CSS :
 /* This is a single-line comment */
p {
  color: red;
} 
```

---

10. CSS Colors: Colors are specified using predefined color names, or RGB, HEX, HSL, RGBA, HSLA values.

In CSS, a color can be specified by using a predefined color name:
- Tomato
- Orange
- DodgerBlue
- MediumSeaGreen
- Gray
- SlateBlue
- Violet
- LightGray

#### Example

```CSS :
<h1 style="background-color:DodgerBlue;">Hello World</h1>
<p style="background-color:Tomato;">Lorem ipsum...</p> 
```
