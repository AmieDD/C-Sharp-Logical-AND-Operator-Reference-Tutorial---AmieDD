# C# && Operator Reference Tutorial
www.amiedd.com
Amiedd - Code, Cosplay and Games

```C# runnable
using System;

bool SecondOperand()
{
    Console.WriteLine("Second operand is evaluated.");
    return true;
}

bool a = false && SecondOperand();
Console.WriteLine(a);
// Output:
// False

bool b = true && SecondOperand();
Console.WriteLine(b);
// Output:
// Second operand is evaluated.
// True
```

# About C# && Operators

The logical AND operator & also caluclates the logical AND of its bool(true, false or 0, 1) operators, but always evaluates BOTH operators.
