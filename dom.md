# DOM (Document Object Model)

## [insertAdjacentHTML](https://developer.mozilla.org/en/docs/Web/API/Element/insertAdjacentHTML)
```js
element.insertAdjacentHTML(position, text);
```

## [createDocumentFragment](https://developer.mozilla.org/en/docs/Web/API/Document/createDocumentFragment)
```js
document.createDocumentFragment();
```

## [HTMLFormElement.elements](https://developer.mozilla.org/en-US/docs/Web/API/HTMLFormElement/elements)
Returns an HTMLFormControlsCollection of all the form controls contained in the FORM element, with the exception of input elements which have a type attribute of image.
```js
var inputs = document.getElementById("form").elements;
```

## [CSSStyleDeclaration.cssText](https://developer.mozilla.org/en-US/docs/Web/API/CSSStyleDeclaration/cssText)
Returns or sets the text of the element's inline style declaration.
```js
element.style.cssText = 'background-color: blue; font-size: 12px; border: 2px solid green;'
```

## Currently focused element
```js
document.activeElement
```
