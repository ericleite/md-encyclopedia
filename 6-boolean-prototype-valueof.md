# Boolean.prototype.valueOf()

A JavaScript prototype function that returns the primitive value of a Boolean object.

It converts an object representation into a primitive value representation of the given object.

## Syntax
```
<bool>.valueOf();
```

### Parameters
None, this is a "getter" function.

### Return Value
`<true | false>` - The primitive value of the Boolean object it was called on.

## Example 1

This will return the primitive `true` from a Boolean object instance with a value of `true`.

```
var boolean = new Boolean(true);
boolean.valueOf();
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
