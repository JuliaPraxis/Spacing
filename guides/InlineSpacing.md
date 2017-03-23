## Best Practices

- Use one space before and after a single binary operator or a comparator.
  - :ok: x + y, x | y, a >= 0
  - :x:  x +y, a|b, a>=0

- Use one space before and after a short-circuiting conditional.
  - :ok: a >= 0 || throw(DomainError())
  - :x:  a>=0||throw(DomainError())
  
- Do not use a space after a unary operator
  - :ok: a = -z
  - :x:  a = - z
  
 
