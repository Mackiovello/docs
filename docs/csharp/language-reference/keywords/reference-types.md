---
title: "Reference types - C# Reference"
ms.custom: seodec18

ms.date: 07/20/2015
f1_keywords: 
  - "cs.referencetypes"
helpviewer_keywords: 
  - "reference types [C#]"
  - "C# language, reference types"
  - "types [C#], reference types"
ms.assetid: 801cf030-6e2d-4a0d-9daf-1431b0c31f47
---
# Reference types (C# Reference)

There are two kinds of types in C#: reference types and value types. Variables of reference types store references to their data (objects), while variables of value types directly contain their data. With reference types, two variables can reference the same object; therefore, operations on one variable can affect the object referenced by the other variable. With value types, each variable has its own copy of the data, and it is not possible for operations on one variable to affect the other (except in the case of in, ref and out parameter variables; see [in](in-parameter-modifier.md), [ref](ref.md) and [out](out-parameter-modifier.md) parameter modifier).

 The following keywords are used to declare reference types:

- [class](class.md)

- [interface](interface.md)

- [delegate](delegate.md)

 C# also provides the following built-in reference types:

- [dynamic](dynamic.md)

- [object](object.md)

- [string](string.md)

## See also

- [C# Reference](../../../csharp/language-reference/index.md)
- [C# Programming Guide](../../../csharp/programming-guide/index.md)
- [C# Keywords](index.md)
- [Types](types.md)
- [Value Types](value-types.md)
