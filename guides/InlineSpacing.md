## Best Practices:  Inline Spacing

     
- Indentation uses four spaces and does not use tabs.

- Use one space before and after a single binary operator or a comparator.
  - :ok:&nbsp;&nbsp;&nbsp;&nbsp; `this + that` &nbsp;&nbsp; `this | that` &nbsp;&nbsp; `a >= 0`
  - :x:&nbsp;&nbsp;&nbsp;&nbsp;  `this +that`  &nbsp;&nbsp;&nbsp;&nbsp; `this|that`  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; `a>=0`
  
- Use one space before and after a short-circuiting conditional.
  - :ok:&nbsp;&nbsp;&nbsp;&nbsp; `an_arg >= 0 || throw(DomainError())`
  - :x:&nbsp;&nbsp;&nbsp;&nbsp;  `an_arg>=0||throw(DomainError())`
  
- Use a space after a comma
  - :ok:&nbsp;&nbsp;&nbsp;&nbsp; `this, that = that, this`  &nbsp;&nbsp; `these = (this, that)` &nbsp;&nbsp; `a = func(b, c)`
  - :x:&nbsp;&nbsp;&nbsp;&nbsp;  `this,that = that,this` &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; `these = (this,that)`  &nbsp;&nbsp;&nbsp;&nbsp; `a=func(b,c)`
  
- Do not use a space after a unary operator
  - :ok:&nbsp;&nbsp;&nbsp;&nbsp; `a = -z` &nbsp;&nbsp;&nbsp; `a = -(b * c)`
  - :x:&nbsp;&nbsp;&nbsp;&nbsp;  `a = - z` &nbsp;&nbsp;&nbsp; `a=-(b*c)`

- Do not use a space after a double colon `::` 
  - :ok:&nbsp;&nbsp;&nbsp;&nbsp; `first_name::String`
  
>  ```julia
struct ExampleStruct    
    first_field  ::Int32    
    second_field ::String    
end
```

  - :x:&nbsp;&nbsp;&nbsp;&nbsp;  `first_name:: String`

```julia
struct ExampleStruct    
    first_field  :: Int32    
    second_field :: String    
end    
```

 #### note
 
 - Function calls have no space between the function name and the opening parenthesis.
