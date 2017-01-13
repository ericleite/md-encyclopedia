# text-indent

A CSS property that specifies the amount of indented space in a text block.

The text-indent property is used to change the style of text blocks by adding a specified amount of space before the first line of a paragraph of text. It results in an effect similar to most printed text where the first line of a paragraph is shifted to the right by a certain amount. The behavior can be changed from first-line paragraph indentation (default) to a hanging indent, or an "each-line" indent.

## Syntax

An example of CSS syntax is below:

```
text-indent: <length | percentage> && hanging? && each-line?;
```

### Values

#### `<length>`
Indentation is specified as an absolute length. Negative values are allowed. Possible units include `px`, `mm`, `q`, `cm`, `in`, `pt` or `pc`.

#### `<percentage>`
Indentation is a percentage of the containing block width. Possible units include `%`.

#### `each-line`
Indentation affects the first line of the block container as well as each line after a forced line break, but does not affect lines after a soft wrap break.

#### `hanging`
All lines except the first line will be indented.

## Example 1

This will indent the first line of a text block with 20px of white space.

```
text-indent: 20px;
```

## Example 2

This will indent the first line of a text block with white space that is 5% of the width of the bounding block.

```
text-indent: 5%;
```

## Example 3

This will indent every line but the first line of a text block with white space that is 10% of the width of the bounding block.

```
text-indent: 10% hanging;
```

## Browser Support

### Desktop

| Feature | FF | Chrome | Edge | IE | Opera | Safari |
|---------------|------------|------------|------------|------------|------------|------------|
| Basic Support | 1.0 | 1.0 | Yes | 3.0 | 3.5 | 1.0 |
| hanging | No support | No support | No support | No support | No support | No support |
| each-line | No support | No support | No support | No support | No support | No support |

### Mobile

| Feature | FF Mobile | Android | Edge | IE Phone | Opera Mobile | Safari Mobile |
|---------------|------------|------------|------|------------|--------------|---------------|
| Basic Support | 1.0 | ? | Yes | ? | ? | ? |
| hanging | No support | No support | ? | No support | No support | No support |
| each-line | No support | No support | ? | No support | No support | No support |
