## Best Practices:  Inline Spacing

     
- Indentation uses four spaces and does not use tabs.

- Use one space before and after a single binary operator or a comparator.
  - :ok:&nbsp;&nbsp;&nbsp;&nbsp; `this + that` &nbsp;&nbsp; `this | that` &nbsp;&nbsp; `a >= 0`
  - :x:&nbsp;&nbsp;&nbsp;&nbsp;  `this +that`  &nbsp;&nbsp;&nbsp;&nbsp; `this|that`  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; `a>=0`

  - Spacing around `^` is optional.

- Use one space before and after a short-circuiting conditional.
  - :ok:&nbsp;&nbsp;&nbsp;&nbsp; `an_arg >= 0 || throw(DomainError())`
  - :x:&nbsp;&nbsp;&nbsp;&nbsp;  `an_arg>=0||throw(DomainError())`
  
- Use a space after a comma
  - :ok:&nbsp;&nbsp;&nbsp;&nbsp; `this, that = that, this`  &nbsp;&nbsp; `these = (this, that)` &nbsp;&nbsp; `a = func(b, c)`
  - :x:&nbsp;&nbsp;&nbsp;&nbsp;  `this,that = that,this` &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; `these = (this,that)`  &nbsp;&nbsp;&nbsp;&nbsp; `a=func(b,c)`
  
- Do not use a space after a unary operator or `%` when used to force a type.
  - :ok:&nbsp;&nbsp;&nbsp;&nbsp; `a = -z` &nbsp;&nbsp;&nbsp; `a = -(b * c)`&nbsp;&nbsp;&nbsp; `a = b%Int32`
  - :x:&nbsp;&nbsp;&nbsp;&nbsp;  `a = - z` &nbsp;&nbsp;&nbsp; `a=-(b*c)`&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; `a = b % Int32`

- Do not use a space after a double colon `::` 
  - :ok:&nbsp;&nbsp;&nbsp;&nbsp; `first_name::String`
  - :x:&nbsp;&nbsp;&nbsp;&nbsp;  `first_name:: String`

  -  :ok:&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;:x:
```julia
newname(name::String)                  newname(name:: String)

struct ExampleStruct                   struct ExampleStruct
    first_field::Int32                     first_field:: Int32
    second_field::String                   second_field:: String
end                                    end

struct ExampleStruct                   struct ExampleStruct
    first_field  ::Int32                   first_field  :: Int32
    second_field ::String                  second_field :: String
end                                    end
```


 #### note
 
 - Function calls have no space between the function name and the opening parenthesis.
