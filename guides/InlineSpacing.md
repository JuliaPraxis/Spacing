## Best Practices

- Use one space before and after a single binary operator or a comparator.
  - :ok:&nbsp;&nbsp; x + y, x | y, a >= 0
  - :x:&nbsp;&nbsp;  x +y, a|b, a>=0

- Use one space before and after a short-circuiting conditional.
  - :ok:&nbsp;&nbsp; a >= 0 || throw(DomainError())
  - :x:&nbsp;&nbsp;  a>=0||throw(DomainError())
  
- Do not use a space after a unary operator
  - :ok:&nbsp;&nbsp; a = -z, a = -(b * c)
  - :x:&nbsp;&nbsp;  a = - z, a=-(b*c)
  
 
