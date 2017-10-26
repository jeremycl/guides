---
title: Break Statement
---

# Break Statement

The `break` statement terminates the current iteration or **switch** statement. Execution continues on the next statement following the terminated statement (if any).

## Example
```
for (int i = 0; i < 5; i++)
{
  if (i == 2)
  {
    break;
  }
  
	Console.WriteLine(i);
}

Console.WriteLine("Complete!");
```

## Output:
```
> 0
> 1
> Complete!
```
