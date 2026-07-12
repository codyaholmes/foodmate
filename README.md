# Intro

This is the intro paragraph. Below is a code block example.

```DAX
Some Measure :=
CALCULATE(
    [Total Sales],
    KEEPFILTERS( 'Some Table'[Col] = "Some value" )
)
```
