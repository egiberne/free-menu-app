
# Learn Basic CSS by Building a Cafe Menu, Not started

## Step 1 | Add doctype and html element 
In this project, you will learn the basics of CSS (Cascading Style Sheets) by building a cafe menu. CSS is the language used to style an HTML document. It describes how *HTML* elements should be displayed on the screen.

As you learned in the last few steps of the Cat Photo App, there is a basic structure needed to start building your web page. Every HTML document should have a DOCTYPE declaration and `html` element. The DOCTYPE tells the browser which version of HTML the document is in. And the html element represents the root element which contains all other elements.

<details>
<summary>Example Code</summary>

```html
<!DOCTYPE html>
<html lang="en">
<!--all other elements go here-->
</html>
```
</details>

Add the `<!DOCTYPE html>` tag, and an `html` element with a `lang` attribute of `en`.


## Step 2 | Add a Title element
Add a `head` element within the `html` element, so you can add a `title` element. The `title` element's text should be `Cafe Menu`.

## Step 3 | Add Metadata element
The title is one of several elements that provide extra information not visible on the web page, but it is useful for search engines or how the page gets displayed.

Inside the `head` element, nest a `meta` element with an attribute named `charset` set to the value `utf-8` to tell the browser how to encode characters for the page. Note that `meta` elements are **self-closing**.

## Step 4 | Add a Body element
To prepare to create some actual content, add a `body` element below the head element.

## Step 5 | Add a Main element
It's time to add some menu content. Add a `main` element within the existing `body` element. It will eventually contain pricing information about coffee and desserts offered by the cafe.

## Step 6 | Add an Heading element
The *name* of the cafe is `CAMPER CAFE`. Add an `h1` element within your main element. Give it the *name* of the cafe in capitalized letters to make it stand out.

## Step 7 | Add a Paragraph element
To let visitors know the cafe was founded in **2021**, add a `p` element below the `h1` element with the text `Est. 2021`.

## Step 8 | Add two Sections element
There will be two *sections* on the menu, one for `coffees` and one for `desserts`. Add a section element within the `main` element so you have a place to put all the coffees available.

## Step 9 | Add a Subheading element
Create an `h2` element in the section element and give it the text Coffee.

## Step 10 | Add a Style element
Up until now, you have been limited regarding the presentation and appearance of the content you create. To start taking control, add a `style` element within the `head` element.

## Step 11 | Add a Type Selector
You can add style to an element by specifying it in the style element and setting a property for it like this:

<details>
<summary>Example Code</summary>

```css
element {
 property: value;
}
```
</details>

Center the content of the h1 element by setting its text-align property to the value center.

## Step 12 | Add more Type Selectors
In the previous step, you used a *type selector* to style the `h1` element. Center the content of the `h2` and the `p` elements by adding a new `type selector` for each one to the existing style element.

## Step 13 | Add a Group of Selectors
You now have three type selectors with the exact same styling. You can add the same group of styles to many elements by creating a list of selectors. Each selector is separated with commas like this:

<details>
<summary>Example Code</summary>

```css
selector1, selector2 {
  property: value;
}
```
</details>

Delete the **3** existing type selectors and replace them with **1** selector list that centers the text for the `h1`, `h2`, and `p` elements.


## Step 14 | Add a file for the Styles
You have styled **3** elements by writing CSS inside the style tags. This works, but since there will be many more styles, it's best to put all the styles in a separate file and link to it.

We have created a separate `styles.css` file for you and switched the editor view to that file. You can change between files with the tabs at the top of the editor.

Start by rewriting the styles you have created into the `styles.css` file. Make sure to exclude the opening and closing `style` tags.

## Step 15 | Remove the Style element
Now that you have the CSS in the `styles.css` file, go ahead and remove the `style` element and all its content. Once it is removed, the text that was centered will shift back to the left.

## Step 16 | Add a Link element the Styles
Now you need to link the `styles.css` file, so the styles will be applied again. Inside the `head` element, add a `link` element. Give it a `rel` attribute with the value of `stylesheet` and a `href` attribute with the value of `styles.css`.

## Step 17 | Add settings for the viewport
For the styling of the page to look similar on mobile as it does on a desktop or laptop, you need to add a `meta` element with a special `content` attribute.

Add the following within the head element:

Example Code
<meta name="viewport" content="width=device-width, initial-scale=1.0" />