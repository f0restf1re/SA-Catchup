## Basic HTML Elements
HTML is the standard markup language for creating web pages. HTML stands for Hyper Text Markup Language. HTML describes the structure of Web pages using markup. HTML elements are the building blocks of HTML pages, and are represented by tags. Browsers do not display the HTML tags, but use them to render the content of the page. Attributes are additional information in the HTML element, provided in key-value pairs. 

## Useful links:
https://www.w3schools.com/tags/ref_attributes.asp
https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes


### 1. `<html></html>`
- The `<html>` tag tells the browser that this is an HTML document. The `<html>` tag represents the root of an HTML document, and container for all other HTL elements (except for the `<!DOCTYPE>` tag). Default CSS values: 

```css
html {
	display: block;
}
```
### 2. `<head></head>`
- The `<head>` element is a container for all the head elements. The `<head>` element can inlcude a title for the document, scripts, styles, meta information, and more. Default CSS values:

```css
head {
	display: none;
}
```

### 3. `<body></body>`
- The `<body>` tag defines the document body. The `<body>` element contains all the contents of an HTML document, such as text, hyperlinks, images, tables, lists, etc. Default CSS values: 

```css
body {
	display: block;
	margin: 8px;
}
```

### 4. `<div></div>`
- The `<div>` tag defines a division or section in an HTML document. The `<div>` tag is used to group block-elements to format them in CSS. The `<div>` element is very often used together with CSS, to layout a web page. Default CSS values:

```css
div {
	display: block;
}
```
### 5. `<p></p>`
- The `<p>` tag defines a paragraph. Browsers automatically add some space (margin) before and after each `<p>` element. The margins can be modified with CSS (with the margin properties). Default CSS values:

```css
p {
	display: block;
	margin: 1em 0 1em 0;
}
```
### 6. `<h1></h1>` to `<h6></h6>`
- The `<h1>` to `<h6>` tags are used to define HTML headings. `<h1>` defines the most important heading, `<h6>` defines the least important heading. Default CSS values for `<h1>`:

```css
h1 {
	display: block;
	font-size: 2em;
	margin: 0.67em 0 0.67em 0;
	font-weight: bold;
}
```
### 7. `<span></span>`
- The `<span>` tag is used to group inline-elements in a document. The `<span>` tag provides no visual change by itself. The `<span>` tag provides a way to hook to a part of a text or a part of a document. There are no default CSS settings for `<span>`.

### 8. `<a></a>`
- The `<a>` tag defines a hyperlink, which is used to link from one page to another. The most important attribute of the `<a>` element is the `href` attribute, which attributes the link's destination. A linked page is normally displayed in the current browser window, unless you specify another target. Note that `internal value` refers to the browser-specific default values. Default CSS values:

```css
a:link, a:visited {
	color: (internal value);
	text-decoration: underline;
	cursor: auto;
}

a:link:active, a:visited:active {
	color: (internal value);
}
```
### 9. `<img>`
- The `<img>` tag defines an image in an HTML page. The `<img>` tag has two required attributes: `src` and `alt`. Images are not technically inserted into an HTML page, images are linked to HTML pages. The `<img>` tag creates a holding space for the referenced image. To link an image to another document, simply nest `<ig>` tag inside `<a>` tags. In HTML, the `<img>` tags has no end tag. Default CSS values:

```css
img {
	display: inline-block;
}
```
### 10. `<ol></ol>`, `<ul></ul>`, and `<li></li>`
- The `<ol>` tag defines a defines an ordered list, while `<ul>` tag defines an unordered list. `<li>` tag is used for individual list items in lists. Default CSS values:

```css
ol, ul {
	display: block;
	list-style-type: decimal;
	margin: 1em 0 1em 0;
	padding-left: 40px;
}
```
### 11. `<button></button>`
- The `<button>` tag defines a clickable button. Inside a `<button>` element you can put content, like text or images. This is the difference between this element and buttons created with the `<input>` element. For compatibility reasons, always specify the type of attribute for a `<button>` element. There are no default CSS settings for `<span>`.

### 12. `<form></form>`
- The `<form>` tag is used to create an HTML form for user input. Example of form elements that you can place inside a HTML form, are like text fields, checkboxes, radio buttons, submit buttons, and more. Forms generally have the `action` attribute to define the action to be performed when the form is submitted using a button. Normally the form data is sent to a web page on the server when the user clicks on the submit button. The value for the `action` attribute should be the path that your server is pre-configured to accept POST requests and returns a response. Default CSS values:

```css
form {
	display: block;
	margin-top: 0em;
}
```
### 13. `<input>`
- The `<input>` tag specifies an input field where the user can enter data. `<input>` elements are used within a `<form>` element to declare input controls that allow users to input data. An input field can vary in many ways, the following are two of the many. Default CSS values:

```css
div {
	display: block;
}
```

- `<input type='text'>` defines a simple one-line text input field. The `type` attribute here defines the type of input here. The next most commonly used attribute is `name`. The `name` attribute defines the key to hold user's input value for when the form is submitted. 
- `<input type='submit'>` defines a button for submitting form data to a form-handler. As mentioned earlier, a form-handler is typically a server page with script for processing input data. The form handler is specified in the container form's `action` attribute. Note that pressing this button will send a POST request to the form-handler. 


<!--<div>
<div style="width: 50.7%; outline: 1px solid black; padding: 20%; font-size: 10em; background-color: yellow; color: black; border: 40px solid red;">HELLO</div>
<div style="width: 100%; outline: 1px solid black; background-color: yellow; color: black; height: 600px"></div>
</div>-->

