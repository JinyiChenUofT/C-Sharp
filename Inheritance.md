![](/images/Inher1.png)

## Implicit Conversion && Explicit Conversion
隐式转换无需调用特殊语法，并且可以在各种情况（例如，在赋值和方法调用中）下发生。 预定义的 C# 隐式转换始终成功，且永远不会引发异常。 用户定义隐式转换也应如此。 如果自定义转换可能会引发异常或丢失信息，请将其定义为显式转换。

public static implicit operator byte(Digit d) => d.digit;

public static explicit operator Digit(byte b) => new Digit(b);

Use the operator and implicit or explicit keywords to define an implicit or explicit conversion, respectively. The type that defines a conversion must be either a source type or a target type of that conversion. A conversion between two user-defined types can be defined in either of the two types.

## Constructors
![](/images/Inher2.png)

## ABSTRACT 

不能implement, 只提供override的一个名字
![](/images/Inher3.png)

![](/images/Inher4.png)
Abstract members cannot be private because derived classes would not be able to see them.
