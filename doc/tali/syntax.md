# Syntax

- Expressions
	- Integers
	- Floats
	- Strings
	- Booleans
	- Words
	- Quotations
- Stack effects
- Functions
- Types

## Expressions

The expression is the basic building block of all Tali programs, representing values and actions.

### Integers

Type name `int`

- No sign


### Floats

Type name `flt`

- No sign
- Leading or trailing digits optional, either side needs to be present

Examples

```
11.0 
11. 
.0
```

### Strings

Type name `str`

- Single-line
- Delimited by `"`
- Escape codes `[\"abfnrtv]`

Examples
```
"Hello World"
"Tali's counterpart Geth"
"And he said \"Go forth\" and I complied"
```

### Booleans

Type name `bool`

- Represented by the literals `true` or `false`

### Words

No type name

- Lowercase
- Allowed characters `[a-zA-Z@?!*-]`

### Quotations

Tye name refers to stack effect of quotation and is encased in parentheses `()`

- Encased within box brackets `[]`

Examples
```
[11 11 +]
[2 mul]
```


## Stack Effects

Represented by type names of before and after stacks

Examples
```
(int, int -- int)
(int, (int -- bool) -- str)
```

## Functions

Functions begin with the `def` keyword, followed by its stack effect and is closed with the `end` keyword

Examples
```
def add-eleven(int -- int) 
    11 +
end
```

## Types

TBW
