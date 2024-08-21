
- HTML describes the structure of a Web page
- HTML consists of a series of elements
- HTML elements tell the browser how to display the content
- HTML elements label pieces of content such as "this is a heading", "this is a paragraph", "this is a link", etc.

---

## A Simple HTML Document

```html
<!DOCTYPE html>  
<html>  
	<head>  
		<title>Page Title</title>  
	</head>  
	<body>  
		<h1>This is a heading</h1>  
		<p>This is a paragraph</p>
		<p>This is another paragraph</p>    
	</body>  
</html>
```

![[Pasted image 20240820113400.png]]

![[Pasted image 20240820114837.png]]

![[Pasted image 20240820120519.png]]
![[Pasted image 20240820120819.png]]
## What is an HTML Element?

An HTML element is defined by a start tag, some content, and an end tag:

The HTML **element** is everything from the start tag to the end tag:

| Start tag  | Element content     | End tag |
| ---------- | ------------------- | ------- |
| `<h1>`     | My First Heading    | `</h1>` |
| `<p>`      | My first paragraph. | `</p>`  |
| `<br>`<br> | _none_              | _none_  |

> **Note:** Some HTML elements have no content (like the` <br>` element). These elements are called empty elements. Empty elements do not have an end tag!

## HTML Attributes

HTML attributes provide additional information about HTML elements.

- Attributes provide **additional information** about elements
- Attributes are always specified in **the start tag**
- Attributes usually come in name/value pairs like: **name="value"**

### Example Explained

- The `<!DOCTYPE html>` declaration defines that this document is an HTML5 document
- The `<html>` element is the root element of an HTML page
- The `<head>` element contains meta information about the HTML page
- The `<title>` element specifies a title for the HTML page (which is shown in the browser's title bar or in the page's tab)
- The `<body>` element defines the document's body, and is a container for all the visible contents, such as headings, paragraphs, images, hyperlinks, tables, lists, etc.
- The `<h1>` element defines a large heading
- The `<p>` element defines a paragraph


