## Best Practices

- Use one space before and after a single binary operator or a comparator.
  - :ok:&nbsp;&nbsp; this + that &nbsp;&SmallCircle;&nbsp; this | that &nbsp;&SmallCircle;&nbsp; a >= 0n
  - :x:&nbsp;&nbsp;  this +that &nbsp;&SmallCircle;&nbsp; this|that &nbsp;&SmallCircle;&nbsp; a>=0

- Use one space before and after a short-circuiting conditional.
  - :ok:&nbsp;&nbsp; an_arg >= 0 || throw(DomainError())
  - :x:&nbsp;&nbsp;  an_arg>=0||throw(DomainError())
  
- Use a space after a comma
  - :ok:&nbsp;&nbsp; this, that = that &nbsp;&SmallCircle;&nbsp; this, these = (this, that) &nbsp;&SmallCircle;&nbsp; a = func(b, c)
  - :x:&nbsp;&nbsp;  this,that = that,this &nbsp;&SmallCircle;&nbsp; these = (this,that) &nbsp;&SmallCircle;&nbsp; a= func(b,c)

- Do not use a space after a unary operator
  - :ok:&nbsp;&nbsp; a = -z &nbsp;&SmallCircle;&nbsp; a = -(b * c)
  - :x:&nbsp;&nbsp;  a = - z &nbsp;&SmallCircle;&nbsp; a=-(b*c)
  
 
