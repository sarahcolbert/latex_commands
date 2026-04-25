# Helpful code for latex


## CITATIONS

### How to use find to search for bracketed citations

```
\[\d+\]
```

### How to use find to search for abstract/keywords

```
abstract\s*=\s*"(.|\n)*?",
```

### How to remove empty lines
find:
```
\n[ \t]*\n
```
replace:
```
\n
```
