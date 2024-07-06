
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