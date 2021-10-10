# OR Operator Regex
Here below will be a explanation of OR Operator and how it functions

## Summary

The OR operator is a Boolean operator which would return the value TRUE or Boolean value of 1 if either or both of the operands are TRUE or have Boolean value of 1. The OR operator is considered one of the basic logical operators along with AND and NOT in Boolean algebra. It is widely used in programming languages which support logical and comparison operators.

The OR operator can also be used in combination with other logical operators.


![Xnip2021-10-10_12-17-57](https://user-images.githubusercontent.com/84043453/136704359-5e15047a-29e8-4904-834c-0c147e1cb908.jpg)


## Table of Contents

- [Syntax](#syntax)
- [Description](#description-of-syntax)
- [Short circuit](#short-circuit-evaluation)
- [Operator precedence](#operator-precedence)
- [Examples](#examples)



### Syntax
![Xnip2021-10-10_12-16-15](https://user-images.githubusercontent.com/84043453/136704308-58e8a3b9-4341-454d-9fa6-495dc77d7d31.jpg)


### Description of Syntax
![Xnip2021-10-10_11-48-13](https://user-images.githubusercontent.com/84043453/136703282-3168bec0-67b9-485f-b5e4-837670689203.jpg)


### Short circuit evaluation
The logical OR expression is evaluated left to right, it is tested for possible "short-circuit" evaluation using the following rule:

(some truthy expression) || expr is short-circuit evaluated to the truthy expression.

Short circuit means that the expr part above is not evaluated, hence any side effects of doing so do not take effect (e.g., if expr is a function call, the calling never takes place). This happens because the value of the operator is already determined after the evaluation of the first operand.

![Xnip2021-10-10_12-22-08](https://user-images.githubusercontent.com/84043453/136704573-dac40cf3-c249-4de0-9fe4-4126dc0fb97f.jpg)


### Operator precedence
The following expressions might seem equivalent, but they are not, because the && operator is executed before the || operator


![Xnip2021-10-10_12-24-40](https://user-images.githubusercontent.com/84043453/136704650-8f832d5d-c66a-42d7-b18e-0b232d77d12c.jpg)


### Examples
![Xnip2021-10-10_11-48-13](https://user-images.githubusercontent.com/84043453/136704674-453a9cf5-086f-45a1-b892-acf3f3300e43.jpg)


## Author

New to coding, yet have been able to use my available resources to succeed in my tasks 

https://github.com/micahlanham


## Sources
First description from:
https://www.techopedia.com/definition/3486/or-operator

Descriptions & Code snippets from:
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Logical_OR
