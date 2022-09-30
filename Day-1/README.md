# HTML - Hypertext Markup Language

**What is HTML?**
- HTML stands for Hyper Text Markup Language
- HTML is the standard markup language for creating Web pages
- HTML describes the structure of a Web page
- HTML consists of a series of elements
- HTML elements tell the browser how to display the content
- HTML elements label pieces of content such as "this is a heading", "this is a     paragraph", "this is a link", etc.

## HTML page

```
<!DOCTYPE html>
<html>
<head>
<title>Page Title</title>
</head>
<body>

<h1>This is a Heading</h1>
<p>This is a paragraph.</p>
<ul>
<li>One</li>
<li>Two</li>
<li>Three</li>
</ul>

<ul>
<ol>One</ol>
<ol>Two</ol>
<ol>Three</ol>
</ul>

<img src="image link" alt="image text" />

<a href="link">Home</a>

<hr />

<br />


</body>
</html>

```
![HTML Element](./images/1.png)

## Empty Element
Insert or Embed something in the document
`<input>, <img>, <br>, <hr>, <embed>, <meta>, <link>`

## Nesting
HTML elements can be nested

```
    <div class="list">
    <h2>My List: </h2>
    <ul>
        <li>Apple</li>
        <li>Mango</li>
        <li>Banana</li>
    </ul>
    </div>

```

## Attributes

Attributes contain extra information about the element that won't appear in the content

` <img src="https://images.unsplash.com/photo-1502082553048-f009c37129b9?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1170&q=80" width="100"/> `

- All HTML elements can have attributes
- Attributes provide additional information about elements
- Attributes are always specified in the start tag
- Attributes usually come in name/value pairs like: name="value"

## Boolean Attributes
- some attributes can be written without value eg. disabled is boolean attributes
` <button onclick="alert("button clicked") disabled="disabled">Button Click</button> `
` <button onclick="alert("button clicked") disabled >Button Click</button> `

## Most common HTML Elements
There are hundreds of HTML elements, most of the time we only use these elemets.

### Define a section: ` <header>, <footer>, <nav>, <main>, <section>, <div> `
### Define a text content: ` <h1> to <h6>, <p>, <span>, <ul>, <li>, <ol> `
### Define a form or a input: ` <form>, <input>, <button>, <lable>, <textarea> `
### Define a img or a link: ` <img>, <a> `
### Others: ` <hr >, <br> `

## Block-level vs inline elements

![Block-level vs inline elements](./images/2-block.png)

## Most common inline elements are colored.

![Most common inline elements](./images/3-block.png)

