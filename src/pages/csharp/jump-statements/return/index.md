---
title: Return Statement
---

# Return Statement

The 'return' statement terminates the execution of the current method and returns control to the calling method. It can also return a value.

If the 'return' statement is located inside a **try** block, the **finally** block will still execute (if it exists) before control is returned to the calling method.

## Example
```
static void Main()
{
  int one = 1;
  int two = 2;
  
  int result = Sum(one, two);
  
  Console.WriteLine(result);
}

static int Sum(int a, int b)
{
  int sum = a + b;
  
  return sum;
}
```

## Output
```
> 3
```
