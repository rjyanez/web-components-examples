# web-components-examples
A series of web components examples, related to the MDN web components documentation at https://developer.mozilla.org/en-US/docs/Web/Web_Components.

The following examples are available:

* element-details — <code>&lt;element-details&gt;</code>. Displays a box containing an HTML element name and description. Provides an example of an autonomous custom element that gets its structure from a <code>&lt;template&gt;</code> element (that also has its own styling defined), and also contains <code>&lt;slot&gt;</code> elements populated at runtime.
* expanding-list-web-component — <code>&lt;ul is="expanding-list"&gt;</code>. Creates an unordered list with expandable/collapsible children. Provides an example of a customized built-in element (the class inherits from <code>HTMLUListElement</code> rather than <code>HTMLElement</code>).
* popup-info-box-web-component — <code>&lt;popup-info img="" text=""&gt;</code>. Creates an info icon that when focused displays a popup info box. Provides an example of an autonomous custom element that takes information from its attributes, and defines structure and basic style in an attached shadow DOM.
* word-count-web-component — <code>&lt;word-count&gt;</code>. When added to an element, counts all the words inside that element and displays them inside an attached shadow DOM. It also contains an interval that periodically updates the word count as it changes. Provides an example of a customized built-in element (the class inherits from <code>HTMLParagraphElement</code> rather than <code>HTMLElement</code>).
