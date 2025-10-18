# covconv
A viral new operator 


## Quick start

1. Download [`covconv.sty`](covconv.sty) into your project folder.
2. Add in your preamble:

```latex
   \usepackage{covconv}
```

Then, use in math or inline math:
```latex
$$ f \conv g $$ 
```

You can also replace the * operator temporarily:
```
\EnableCoronaAsterisk
  $$ (f * g)(t) $$
\DisableCoronaAsterisk
```
