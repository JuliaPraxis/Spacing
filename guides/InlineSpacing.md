## Best Practices

- Use one space before and after a single binary operator, a comparator or short-circuiting conditionals.
  - :ok: x + y, x | y, a >= 0 || throw(DomainError())
  - :x:  x +y, a|b, a>=0||throw(DomainError())
  
- Do not use a space after a unary operator
  - :ok: a = -z
  - :x:  a = - z
  
 
