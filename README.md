# Type '{ x: number; y: number; }' is not assignable to type 'number'

This TypeScript bug demonstrates a common type error: assigning a simpler type to a more complex type.  The function `printCoord` expects an object with `x` and `y` properties, but the incorrect call passes a number instead.

The solution shows how to provide the correctly typed object to resolve the error.