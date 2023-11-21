# JavaScript Naming Conventions (Google Style Guide)

## Variables

- **Use meaningful names:** Choose descriptive names that convey the purpose or content of the variable.
```javascript
  // Good
  const userCount = 10;

  // Avoid
  const x = 10;
```
- **Use camelCase:** Start variable names with a lowercase letter and capitalize the first letter of each subsequent concatenated word.
```javascript
  // Good
  const itemCount = 5;

  // Avoid
  const item_count = 5;
```
## Constants:
- **Use uppercase with underscores:** Constants should be in all uppercase letters with underscores between words.
 ```javascript

 // Good
const MAX_SIZE = 100;

// Avoid
const maxSize = 100;
```
## Functions
- **Use camelCase:** Same as variables, function names should use camelCase.

```javascript
// Good
function calculateTotal() {
  // function body
}

// Avoid
function calculate_total() {
  // function body
}
```
## Classes

- **Use PascalCase:** Class names should start with an uppercase letter, and each subsequent concatenated word should also begin with an uppercase letter.
```javscript
// Good
class Animal {
  // class body
}

// Avoid
class animal {
  // class body
}
```

## Objects
- **Use camelCase for keys:** When defining object properties, use camelCase for key names.
```javascript
// Good
const myObject = {
  keyName: 'value',
  anotherKey: 'anotherValue',
};

// Avoid
const myObject = {
  key_name: 'value',
  another_key: 'anotherValue',
};

```
## Acronyms and Initialisms
- **Treat as words:**  Treat acronyms and initialisms as words in names, and use camelCase.
```javascript
// Good
const xmlHttpRequest = new XMLHttpRequest();

// Avoid
const XMLHTTPRequest = new XMLHttpRequest();
