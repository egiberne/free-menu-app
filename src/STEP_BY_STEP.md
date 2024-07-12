
# Learn Basic CSS by Building a Cafe Menu, Not started

## Step 1 | Create doctype and html element 
In this project, you will learn the basics of CSS (Cascading Style Sheets) by building a cafe menu. CSS is the language used to style an HTML document. It describes how *HTML* elements should be displayed on the screen.

As you learned in the last few steps of the Cat Photo App, there is a basic structure needed to start building your web page. Every HTML document should have a DOCTYPE declaration and `html` element. The DOCTYPE tells the browser which version of HTML the document is in. And the html element represents the root element which contains all other elements.

<details>
<summary>Code Snippet</summary>

```html
<!DOCTYPE html>
<html lang="en">
<!--all other elements go here-->
</html>
```
</details>

Add the `<!DOCTYPE html>` tag, and an `html` element with a `lang` attribute of `en`.


## Step 2 | Create a Title element
Add a `head` element within the `html` element, so you can add a `title` element. The `title` element's text should be `Cafe Menu`.

## Step 3 | Create Metadata element
The title is one of several elements that provide extra information not visible on the web page, but it is useful for search engines or how the page gets displayed.

Inside the `head` element, nest a `meta` element with an attribute named `charset` set to the value `utf-8` to tell the browser how to encode characters for the page. Note that `meta` elements are **self-closing**.

## Step 4 | Create a Body element
To prepare to create some actual content, add a `body` element below the head element.

## Step 5 | Create a Main element
It's time to add some menu content. Add a `main` element within the existing `body` element. It will eventually contain pricing information about coffee and desserts offered by the cafe.

## Step 6 | Create an Heading element
The *name* of the cafe is `CAMPER CAFE`. Add an `h1` element within your main element. Give it the *name* of the cafe in capitalized letters to make it stand out.

## Step 7 | Create a Paragraph element
To let visitors know the cafe was founded in **2021**, add a `p` element below the `h1` element with the text `Est. 2021`.

## Step 8 | Create two Sections element
There will be two *sections* on the menu, one for `coffees` and one for `desserts`. Add a section element within the `main` element so you have a place to put all the coffees available.

## Step 9 | Create a Subheading element
Create an `h2` element in the section element and give it the text Coffee.

## Step 10 | Create a Style element
Up until now, you have been limited regarding the presentation and appearance of the content you create. To start taking control, add a `style` element within the `head` element.


<p align="right">🔺<a href="#">Top</a></p>


## Step 11 | Create a Type Selector
You can add style to an element by specifying it in the style element and setting a property for it like this:

<details>
<summary>Code Snippet</summary>

```css
element {
 property: value;
}
```
</details>

Center the content of the h1 element by setting its text-align property to the value center.

## Step 12 | Create more Type Selectors
In the previous step, you used a *type selector* to style the `h1` element. Center the content of the `h2` and the `p` elements by adding a new `type selector` for each one to the existing style element.

## Step 13 | Create a Group of Selectors
You now have three type selectors with the exact same styling. You can add the same group of styles to many elements by creating a list of selectors. Each selector is separated with commas like this:

<details>
<summary>Code Snippet</summary>

```css
selector1, selector2 {
  property: value;
}
```
</details>

Delete the **3** existing type selectors and replace them with **1** selector list that centers the text for the `h1`, `h2`, and `p` elements.


## Step 14 | Create a file for the Styles
You have styled **3** elements by writing CSS inside the style tags. This works, but since there will be many more styles, it's best to put all the styles in a separate file and link to it.

We have created a separate `styles.css` file for you and switched the editor view to that file. You can change between files with the tabs at the top of the editor.

Start by rewriting the styles you have created into the `styles.css` file. Make sure to exclude the opening and closing `style` tags.

## Step 15 | Remove the Style element
Now that you have the CSS in the `styles.css` file, go ahead and remove the `style` element and all its content. Once it is removed, the text that was centered will shift back to the left.

## Step 16 | Create a Link element the Styles
Now you need to link the `styles.css` file, so the styles will be applied again. Inside the `head` element, add a `link` element. Give it a `rel` attribute with the value of `stylesheet` and a `href` attribute with the value of `styles.css`.

## Step 17 | Create settings for the viewport
For the styling of the page to look similar on mobile as it does on a desktop or laptop, you need to add a `meta` element with a special `content` attribute.

Add the following within the head element:

<details>
<summary>Code Snippet</summary>

```html
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
```
</details>


## Step 18 | Create a Background Color
The text is centered again so the link to the CSS file is working. Add another style to the file that changes the `background-color` property to brown for the `body` element.

<details>
<summary>Code Snippet</summary>

```css
body {
   background-color:gray;
}
```
</details>

## Step 19 | Create new the Background Color
That brown background makes it hard to read the text. Change the `body` element's background color to be `burlywood` so it has some color but you are still be able to read the text.

<details>
<summary>Code Snippet</summary>

```css
body {
   background-color:limegreen;
}
```
</details>


<p align="right">🔺<a href="#">Top</a></p>


## Step 20 | Create a div element
The `div` element is used mainly for design layout purposes unlike the other content elements you have used so far. Add a `div` element inside the `body` element and then move all the other elements inside the new `div`.

Inside the opening `div` tag, add the `id` attribute with a value of menu.

<details>
<summary>Code Snippet</summary>

```html
<div id=menu>
  <!-- all other elements go here -->
</div>
```
</details>

<p align="right">🔺<a href="#">Top</a></p>

## Step 21 | Create a selector id for the div element
The div element must cover a piece of the `viewport`. 
Limit the `width` of the div element to **350** *pixels* by creating style for the `#menu` selector.

<details>
<summary>Code Snippet</summary>

```css
#menu {
  width: 350px;
}
```
</details>

## Step 22 | Create a comment
To get back with a white backgroung, comment the code with the `background-color` property and value.

<details>
<summary>Code Snippet</summary>

```css
/*background-color:limegreen;*/
```
</details>


## Step 23 | Update the Background Color
Now use the existing `#menu` selector to set the *background color* of the `div` element to be `orangered`.

<details>
<summary>Code Snippet</summary>


```css
#menu {
  width:350px;
  background-color:orangered;
}
```
</details>

## Step 24 | Update the width property a selector class for the div

Update the `width` property value to make it **50%** of its `body` element `width`.

<details>
<summary>Code Snippet</summary>

```css
#menu {
  width:50%;
  background-color:orangered;
}
```
</details>

## Step 25 | Update the selector to center the div
Set `margin-left` and `margin-right` properties to `auto` for the `#menu` element within the `body` element.

<details>
<summary>Code Snippet</summary>

```css
#menu {
  width:50%;
  background-color:orangered;
  margin-left:auto;
  margin-right:auto;
}
```
</details>


## Step 26 | Update the id to the class selector
Use a class selector to style the `menu` element. Change the `#menu` selector to `.menu` in the `styles.css` file.

<details>
<summary>Code Snippet</summary>

```css
.menu {
  width:50%;
  background-color:orangered;
  margin-left:auto;
  margin-right:auto;
}
  ```
</details>

## Step 27 | Update the id attribut to class attribut
Change the `id` attribute of the `div` element to a `class` attribute with a value of `menu`.

 <details>
<summary>Code Snippet</summary>
  
  ```html
   <div class="menu">
  <!-- all other elements go here -->
</div>
  ```
</details>

## Step 28 | Update the background to an image
Use an image of pies for the background of the page.

<details>
<summary>Code Snippet</summary>

```css
body {
    /*background-color:limegreen;*/
    background-image:url("pies.png");
}
```
</details>

## Step 29 | Create a article element
Add an `article` element inside the `div` element

<details>
<summary>Code Snippet</summary>

```html
<div class="menu">
  <article>
    <!-- all other elements go here -->
  </article>
</div>
```
</details>

## Step 30 | Create paragraph elements
Add two `p` elements inside the `article` element. The first `p` element should contain the text `Veggie` and the second `p` element should contain the text `10.0`.

<details>
<summary>Code Snippet</summary>

```html
<div class="menu">
  <article>
    <p>Veggie</p>
    <p>10.0</p>
  </article>
</div>
```
</details>



<p align="right">🔺<a href="#">Top</a></p>




## Step 31 | Create other article elements

<details>
<summary> Code Snippet </summary>

```html
<div class="menu">
  <article>
    <p>Veggie</p>
    <p>10.0</p>
  </article>
  <article>
    <p>Ham</p>
    <p>10.0</p>
  </article>
  <article>
    <p>Pepperoni</p>
    <p>10.0</p>
  </article>
  <article>
    <p>Supreme</p>
    <p>10.0</p>
  </article>
</div>
```
</details>

## Step 32 | Create an attribute class for the p element

Add the `class` attribute named `taste` to the `p` elements.  This will allow you to style all the `p` elements with the `taste` class at once.
<details>
<summary> Code Snippet </summary>

```html
  <article>
    <p class="taste">Veggie</p>
  </article>
```
</details>



<p align="right">🔺<a href="#">Top</a></p>

## Step 33 | Create a selector class for the p element

Align the text to the left side.

<details>
<summary> Code Snippet </summary>

```css
.taste {
  text-align:left;
}
```
</details>

## Step 34 | Create another attribut the p element

Add the `class` attribute named `cost` to the `p` elements related to the price. This will allow you to style all the `p` elements with the `cost` class at once.

<detail>
<summary> Code Snippet </summary>

```html
  <article>
    <p class="taste"> pizza</p>
    <p class="cost">10.0</p>
  </article>
```
</details>

## step 35 | Create a selector class for the p element

Align the text related to the price to the right side.

<details>
<summary> Code Snippet </summary>

```css
.cost {
  text-align:right;
}
```
</details>

## Step 36 | Create a class for the article element

Add the `class` attribute named `product` to the `article` elements. This will allow you to style all the `article` elements with the `product` class at once.

<details>
<summary> Code Snippet </summary>

```html
  <article class="product">
    <p class="taste"> pizza</p>
    <p class="cost">10.0</p>
  </article>
```
</details>


## Step 37 | Update the display attribut of the p element

The `article` elements are displayed as block elements by default. Change the `display` property of the `menu-item` class selector to `inline-block` to display the `article` elements in a row.

<details>
<summary> Code Snippet </summary>

```css
.menu-item {
  display:inline-block;
}
```
</details>


## Step 38 | Update the width property of the class selectors

Set a width of **50%** for the `cost` and `taste` class selector.
<details>
<summary> Code Snippet </summary>

```css
.tasted {
  width:50%;
}

.cost {
  width:50%;
}
```
</details>

## Step 39 | Update the width property of the class selectors

Set a width of **49%** for the `taste` and `cost` class selector.

<details>
<summary> Code Snippet </summary>

```css
.taste {
  width:49%;
}

.cost {
  width:49%;
}
``` 
</details>

## Step 40 | Remove the newline betweeen the paragraph elements

Set the `p` elements to the same line in order to have no space between them.

<details>
<summary> Code Snippet </summary>

```html
  <article class="product">
    <p class="taste"> pizza</p><p class="cost">10.0</p>
  </article>
```
</details>


<p align="right">🔺<a href="#">Top</a></p>

## Step 41 | Update the width property of the class selectors

Set a width of **50%** for the `taste` and `cost` class selector.

<details>
<summary> Code Snippet </summary>

```css
.taste {
  width:50%;
}

.cost {
  width:50%;
}
```
</details>

## Step 42 | Update the class attribut of all article elements

Add the `class` attribute named `product` to the `article` elements. This will allow you to style all the `article` elements with the `product` class at once.

<details>
<summary> Code Snippet </summary>

```html
  <article class="product">
    <p class="taste"> pizza</p><p class="cost">10.0</p>
  </article>
```
</details>

## Step 43 | Remove the space between all paragraph elements

Set the `p` elements to the same line in order to have no space between them.

<details>
<summary> Code Snippet </summary>

```html
  <article class="product">
    <p class="taste"> pizza</p><p class="cost">10.0</p>
  </article>
```
</details>

## Step 44 | Update the property of all paragraph class selectors

Set the class attribut `taste` and  `cost` for the p elements accordingly.

<details>
<summary> Code Snippet </summary>
  
  ```html
  <article class="product">
    <p class="taste"> pizza</p><p class="cost">10.0</p>
  </article>
  ```
</details>


## Step 45 | Update the width property of the class selectors, taste and cost

Set a width of **80%** for the `taste` and **20%** `cost` class selector.


<details>
<summary> Code Snippet </summary>

```css
.taste {
  width:80%;
}

.cost {
  width:20%;
}
```
</details>

## Step 46 | Create a new section element

Add a `section` element inside the `div` element.

<details> 
<summary> Code Snippet </summary>

```html
<div class="menu">
  <section>
    <!-- all other elements go here -->
  </section>
</div>
```
</details>

## Step 47 | Create a h2 element

Add an `h2` element inside the `section` element with the text `Pizza`.

Repeat this step for a 3rd section element, but with the text `Desserts`.

<details>
<summary> Code Snippet </summary>

```html
<div class="menu">
  <section>
    <h2>Pizza</h2>
  </section>
</div>
```
</details>

## Step 48 | Create a new article element

Add an `article` element inside the new `section` element.

Repeat this step for the 3rd section element.


<details>
<summary> Code Snippet </summary>

```html
<div class="menu">
  <section>
    <h2>Pizza</h2>
    <article>
      <!-- all other elements go here -->
    </article>
  </section>
</div>
```
</details>

## Step 49 | Create a p element

Add a `p` element inside the new `article` element with the text `4 Cheeses`.
Add another `p` element with the text `10.0` at the same line as the first `p` element.

Repeat this step for the 3rd section element.

<details>
<summary> Code Snippet </summary>

```html
<div class="menu">
  <section>
    <h2>Pizza</h2>
    <article>
      <p>4 Cheeses</p> <p>10.0</p>
    </article>
  </section>  
</div>
```
</details>


## Step 50 | Update the class attribut of the p elements

Add the `class` attribute named `pizza`, `sweet` to the first `p` element and the `class` attribute named `cost` to the second `p` element.







<p align="right">🔺<a href="#">Top</a></p>