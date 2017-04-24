# String.prototype.match()

A JavaScript prototype function that matches a string against a regular expression.

The match function is useful when you need to find a pattern within a string. It conveniently stores all matched results in an array-like object, so you can perform array operations on the list of results.

## Syntax
```
<string>.match(<regexp>);
```

### Parameters

#### `<regexp>` (required)
A regular expression object. If a non-RegExp object `obj` is provided, it will convert the input using `new RegExp(obj)`.

### Return Value
`<array> | null` - The match result array. If no input is provided, it will return `[""]`. If no matches were found, it will return `null`.

## Example 1

In the following example, `String.prototype.match()` is used to find the word `red` in a String.

```JavaScript
var poem = 'Roses are red, violets are blue...';
var pattern = /red/;
var matches = poem.match(pattern);

// matches takes the form of an array of matched results:
// [
//   0: "red"
//   index: 10
//   input: "Roses are red, violets are blue..."
//   length: 1
// ]
```

## Browser Support

### Desktop

| Feature | FF | Chrome | Edge | IE | Opera | Safari |
|---------------|------------|------------|------------|------------|------------|------------|
| Basic Support | Yes | Yes | Yes | Yes | Yes | Yes |

### Mobile

| Feature | FF Mobile | Android | Edge | IE Phone | Opera Mobile | Safari Mobile |
|---------------|------------|------------|------|------------|--------------|---------------|
| Basic Support | Yes | Yes | Yes | Yes | Yes | Yes |
