## Best Practices:  Vertical Spacing
     
- Indentation uses four spaces and does not use tabs.

### Sequence of assignments

Prefer to align on the `=`.

```julia
this  = that
these = those
```
```julia
this               = that
estimated_mean     = estimate_mean(data)
these              = those
estimated_variance = estimate_variance(data)
```
If the left-hand-side name lengths vary greatly in subgroups, align subgroups on the `=`.
```julia
this  = that
these = those
estimated_mean     = estimate_mean(data)
estimated_variance = estimate_variance(data)
```

### Type field declarations

Prefer to align on the `::`.

```julia
struct ExampleStruct    
    first_field  :: Int32    
    second_field :: String    
end    
```
If the field name lengths vary greatly, align subgroups on the `::`.
```julia
struct ExampleStruct    
    id    :: String    
    score :: Float64    
    this_is_the_third_field  :: Int32    
    this_is_the_fourth_field :: String    
end    
```
### Splitting Lines

Prefer to split a long line after `=`, `,`, `||`, `&&`. or `(`.

Indent the split parts of a long line equally.

- function definitions
  - :ok:&nbsp;&nbsp;&nbsp;&nbsp; good
  - :x:&nbsp;&nbsp;&nbsp;&nbsp;  avoid

### Alignment

Prefer aligning on

- statement
  - :ok:&nbsp;&nbsp;&nbsp;&nbsp; good
  - :x:&nbsp;&nbsp;&nbsp;&nbsp;  avoid
  
### note

- Lines should not end with whitespace.

