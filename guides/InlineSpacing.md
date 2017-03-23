## Best Practices

- Use one space before and after a single binary operator or a comparator.
  - :ok:&nbsp;&nbsp; this + that, this | that, a >= 0
  - :x:&nbsp;&nbsp;  this +that, this|that, a>=0

- Use one space before and after a short-circuiting conditional.
  - :ok:&nbsp;&nbsp; an_arg >= 0 || throw(DomainError())
  - :x:&nbsp;&nbsp;  an_arg>=0||throw(DomainError())
  
- Use a space after a comma
  - :ok:&nbsp;&nbsp; this, that = that :bullet:, this, these = (this, that), a = func(b, c)
  - :x:&nbsp;&nbsp;  this,that = that,this, these = (this,that), a= func(b,c)

- Do not use a space after a unary operator
  - :ok:&nbsp;&nbsp; a = -z, a = -(b * c)
  - :x:&nbsp;&nbsp;  a = - z, a=-(b*c)
  
 
