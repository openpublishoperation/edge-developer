---
ms.assetid: d8a774e1-5461-434f-b24c-edf0fa62c4a3
description: Learn how the Xpath API can be used to locate and process elements in an eml document.
title: Dev guide - Xpath
author: abbycar
ms.author: abigailc
ms.date: 02/08/2017
ms.topic: article
ms.prod: microsoft-edge
keywords: edge, web development, html, css, javascript, developer
---

# XPath API


The XPath API provides a way to locate and process elements in XML documents. As of Microsoft Edge, the [Document Object Model (DOM) Level 3 XPath Specification](http://go.microsoft.com/fwlink/p/?LinkId=524495) is supported which offers native support in the DOM for XPath navigation and searching in XML documents.

In older versions of Windows Internet Explorer, developers had to use 3rd party libraries or a MSXML hack to provide XPath functionality. With Microsoft Edge, XPath API code that has worked in other browsers should work seamlessly in Microsoft Edge too.


For more information about XPath, check out [Improving interoperability with DOM L3 XPath](http://blogs.windows.com/msedgedev/2015/03/19/improving-interoperability-with-dom-l3-xpath/) on the Microsoft Edge dev blog.

## Example
The code below demonstrates a use of the new XPath functionality. It delivers the same results across all major browsers: logging the appropriate numbers within the `span` elements to the developer [console](../../devtools-guide/console.md).

<div class="codepen-wrap"><p data-height="300" data-theme-id="23761" data-slug-hash="eZEjBN" data-default-tab="result" data-user="MSEdgeDev" data-embed-version="2" data-editable="true" class="codepen">See this example by <a href="https://codepen.io/MSEdgeDev">Microsoft Edge Docs</a> on <a href="https://codepen.io/MSEdgeDev/pen/eZEjBN">CodePen</a>.</p></div><script async src="//assets.codepen.io/assets/embed/ei.js"></script>



## Related topics
[Improving interoperability with DOM L3 XPath](http://blogs.windows.com/msedgedev/2015/03/19/improving-interoperability-with-dom-l3-xpath/)

## Specification
[Document Object Model (DOM) Level 3 XPath Specification](http://go.microsoft.com/fwlink/p/?LinkId=524495)


