---
title: Goto Statement
---

# Goto Statement

The `goto` statement continues execution of the program at a labelled statement.

A common use of the 'goto' statement is within a **switch** statement to continue execution at a **case** or **default** label.

## Example
```
int score = 0;

switch(x)
{
  case 1:
    score += 5;
    break;
    
   case 2:
    score += 10;
    break;
    
   case 3:
    score += 15;
    goto case 1;
    
   default:
    break;
}
```


Another common use of the 'goto' statement is break out of nested **loops**.

## Example:
```
for (int i = 0; i < 100; i++)
{
  for (int j = 0; j < 200; j++)
  {
    if (i == 20 && j == 50)
    {
      goto EndOfLoop;
    }
  }
}

EndOfLoop:
  Console.WriteLine("Complete!");
```
