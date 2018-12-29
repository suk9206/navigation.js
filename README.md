# suk9206/navigation.js
**"suk9206/navigation.js"** is copies the skip break that matches the form set in **"suk9206/navigation.js"** from the specified element to the desired element.

## Example
https://suk9206.github.io/navigation.js/

## Usage
```
navigation({
    from: document.getElementById('main'), // Elements that you want to navigation.
    into: document.getElementById('nav'), // The location of the element from which you want to import the navigation data.
    descendent: ['h2', 'h3', 'h4', 'h5', 'h6'] // Specifies the array of element node names to be imported as additional child elements
});
```
