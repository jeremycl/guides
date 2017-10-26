---
title: Continue Statement
---

# Continue Statement

The `continue` statement proceeds to the next iteration of the current **while**, **do**, **for** or **foreach** statement.

## Example
```
for (int i = 0; i < 5; i++)
{
  if (i < 2)
  {
    continue;
  }
  
	Console.WriteLine(i);
}
```

## Output:
```
> 2
> 3
> 4
```
