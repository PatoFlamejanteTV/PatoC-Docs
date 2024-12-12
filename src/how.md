# but... How?
Simple:

`PatoC code -> "Compiler" -> Visual Basic (.NET) code`

``` mermaid
flowchart TD
    n1["PatoC Code"] -- Gets imported to Compiler --> n2@{ label: "PatoC 'Compiler'" }
    n2 -- Display final Visual Basic (.NET) code --> n3["Final code"]

    n1@{ shape: rect}
    n2@{ shape: rect}
    n3@{ shape: rect}
```

Very simple right?
