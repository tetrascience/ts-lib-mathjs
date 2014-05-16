# Function tanh

Calculate the hyperbolic tangent of a value, defined as `tanh(x) = (exp(2 * x) - 1) / (exp(2 * x) + 1)`.

For matrices, the function is evaluated element wise.


## Syntax

```js
math.tanh(x)
```

### Parameters

Parameter | Type | Description
--------- | ---- | -----------
`x` | Number &#124; Boolean &#124; Complex &#124; Unit &#124; Array &#124; Matrix | Function input

### Returns

Type | Description
---- | -----------
Number &#124; Complex &#124; Array &#124; Matrix | Hyperbolic tangent of x


## Examples

```js
var math = mathjs();

// tanh(x) = sinh(x) / cosh(x) = 1 / coth(x)
math.tanh(0.5);                   // returns 0.46211715726000974
math.sinh(0.5) / math.cosh(0.5);  // returns 0.46211715726000974
1 / math.coth(0.5);               // returns 0.46211715726000974
```


## See also

[sinh](sinh.md),
[cosh](cosh.md),
[coth](coth.md)


<!-- Note: This file is automatically generated from source code comments. Changes made in this file will be overridden. -->