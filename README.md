# Awesome-HTML-Interview-Questions
A curated list of amazingly awesome HTML Interview Questions, resources and shiny things.

## Table of Contents

[HTML Basics](# HTML Basics)
1.  [HTML document](#html-document)
2.  [HTML head](#html-head)
3.  [HTML headings](#html-tags)
4.  [HTML paragraphs](#html-headings)
5.  [HTML links](#html-links)
6.  [HTML images](#html-images)
7.  [HTML buttons](#html-buttons)
8.  [HTML lists](#html-lists)


## HTML Basics

### HTML Document:
1. **What is HTML?**  
   HTML stands for Hypertext Markup Language. It is the standard markup language for creating web pages and web applications. HTML defines the structure and layout of a web document by using a variety of tags and attributes.

   [⬆ back to top](#table-of-contents)

2. **What is the full form of HTML?**  
   HTML stands for Hypertext Markup Language.

   [⬆ back to top](#table-of-contents)

3. **What is the current version of HTML?**  
   The current version of HTML is HTML5.

   [⬆ back to top](#table-of-contents)

4. **What is the purpose of HTML?**  
   The purpose of HTML is to structure the content of a web page, defining elements such as headings, paragraphs, links, images, and more. HTML provides the basic building blocks for creating web pages and defining their layout and appearance.

   [⬆ back to top](#table-of-contents)

5. **How do you create an HTML document?**  
   An HTML document is created by writing HTML code using a text editor and saving the file with a .html extension. The basic structure of an HTML document includes the doctype declaration, html, head, and body elements.

   [⬆ back to top](#table-of-contents)

6. **Explain the structure of an HTML document.**  
   An HTML document typically consists of the following structure:
   - Doctype declaration (`<!DOCTYPE html>`)
   - HTML element (`<html>`)
     - Head element (`<head>`)
       - Title element (`<title>`)
       - Meta elements (`<meta>`)
     - Body element (`<body>`)
       - Content (e.g., headings, paragraphs, images, links)

   [⬆ back to top](#table-of-contents)

7. **What is the doctype declaration in HTML?**  
   The doctype declaration (`<!DOCTYPE html>`) is an instruction to the web browser about the version of HTML in which the page is written. It ensures that the web page is displayed correctly and renders in standards mode.

   [⬆ back to top](#table-of-contents)

8. **What is the difference between HTML and XHTML?**  
   HTML (Hypertext Markup Language) and XHTML (Extensible Hypertext Markup Language) are both markup languages used for creating web pages. The main difference between the two is that XHTML is an XML-based markup language, which means it has stricter syntax rules and requires well-formed documents.

   [⬆ back to top](#table-of-contents)

9. **Can you have multiple <DOCTYPE> declarations in an HTML document?**  
   No, an HTML document should have only one doctype declaration, and it should be placed at the beginning of the document before any other content.

   [⬆ back to top](#table-of-contents)

10. **What happens if you don't include a doctype in your HTML document?**  
    If you don't include a doctype declaration in your HTML document, the browser may render the page in quirks mode, which can lead to inconsistencies in how the page is displayed across different browsers.

    [⬆ back to top](#table-of-contents)

11. **Why is it recommended to use a doctype declaration in HTML?**  
    It is recommended to use a doctype declaration in HTML to ensure that the web page is rendered in standards mode, which helps achieve consistent rendering across different browsers and devices.

    [⬆ back to top](#table-of-contents)

12. **What is the purpose of the <html> tag in HTML?**  
    The `<html>` tag is the root element of an HTML document. It wraps all the content of the document and defines it as an HTML document. All other elements are descendants of the `<html>` element.

    [⬆ back to top](#table-of-contents)


### HTML Head:

1. **What is the purpose of the <head> element in HTML?**  
   The `<head>` element in HTML is used to provide meta-information about the document, such as the document's title, character encoding, viewport settings, CSS stylesheets, and JavaScript code. It does not contain visible content but plays a crucial role in defining the document's structure and behavior.

   [⬆ back to top](#table-of-contents)

2. **Explain the role of the <body> element in HTML.**  
   The `<body>` element in HTML contains the content of the web page that is visible to the user, including text, images, links, forms, and other elements. It defines the main content area of the web page and is where most of the HTML elements are placed for display.

   [⬆ back to top](#table-of-contents)

3. **Can you have multiple <head> and <body> elements in an HTML document?**  
   No, an HTML document should have only one `<head>` element and one `<body>` element. These elements define the head and body sections of the document, respectively, and there should be only one of each in a valid HTML document.

   [⬆ back to top](#table-of-contents)

4. **What is the purpose of the <title> element in HTML?**  
   The `<title>` element in HTML is used to define the title of the web page, which appears in the browser's title bar or tab. It is also used as the default name when bookmarking the page. The title provides a brief description of the content or purpose of the web page.

   [⬆ back to top](#table-of-contents)

5. **How do you set the title of an HTML document?**  
   The title of an HTML document is set by placing the desired text within the `<title>` element, which is nested inside the `<head>` element. For example:
   ```html
   <head>
       <title>This is the Title of the Page</title>
   </head>
   ```
   [⬆ back to top](#table-of-contents)

6. **What is the viewport meta tag in HTML?**  
   The viewport meta tag (`<meta name="viewport" content="width=device-width, initial-scale=1.0">`) in HTML is used to control the layout and dimensions of the viewport on mobile devices. It ensures that the web page is displayed properly and scaled to fit the device's screen size.

   [⬆ back to top](#table-of-contents)

7. **How do you specify the character encoding of an HTML document?**  
   The character encoding of an HTML document is specified using the `<meta charset="charset">` tag within the `<head>` element. For example:
   ```html
   <head>
       <meta charset="UTF-8">
   </head>
   ```

   [⬆ back to top](#table-of-contents)

8. **Explain the difference between the `<meta charset="UTF-8">` and `<meta http-equiv="Content-Type" content="text/html; charset=UTF-8">` declarations.**  
   - `<meta charset="UTF-8">`: Specifies the character encoding of the HTML document directly within the meta tag. It is the preferred method for specifying character encoding.
   - `<meta http-equiv="Content-Type" content="text/html; charset=UTF-8">`: Specifies the character encoding of the HTML document using an HTTP header. It is an older method and is less commonly used now.

   [⬆ back to top](#table-of-contents)

9. **What is the purpose of the `<meta>` tag in HTML?**  
   The `<meta>` tag in HTML is used to provide meta-information about the document, such as character encoding, viewport settings, author information, keywords, and description. It is placed within the `<head>` element and does not contain visible content.

   [⬆ back to top](#table-of-contents)

10. **How do you include comments in an HTML document?**  
    Comments in HTML are included using the `<!-- -->` syntax. Anything placed between `<!--` and `-->` will be treated as a comment and will not be rendered by the browser. Comments are often used to add notes or descriptions to the code for better readability and understanding.
    ```html
    <!-- This is a comment -->
    ```
    [⬆ back to top](#table-of-contents)
