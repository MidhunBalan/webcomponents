# Webcomponents example

This repository severs all the examples available in webcomponent. 

## Notes

3 main building blocks of web component:
1. Custom elements
2. Shadow DOM
3. HTML Templates

##### Customer Elements Life Cycle Methods:
 - constructor: Called when an instance of an object is created or upgraded.

 - connectedCallback: called every time when the element is inserted into the DOM

 - disconnectedCallback: called every time when element is removed from the DOM

 - attributeChangedCallback(attributeName, oldValue, newValue): called when an attribute is added, removed, updated or replaced.

##### Shadow DOM
Used for self contained components
Encapsulate styles and markup
Create with element.attachShadow({mode:'open'})
Creates a shadowRoot that we can reference and interacted with.

##### HTML Templates
Define encapsulated markup for our web component.
Template tag stores markup on page.
Include both HTML and CSS in templates.
Use slots to add custom text.

## Examples

- Beginner
    [introduction](https://github.com/MidhunBalan/webcomponents/tree/master/examples/introduction)




