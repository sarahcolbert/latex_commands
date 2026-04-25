# Helpful code for latex


## CITATIONS

### How to use find to search for bracketed citations

```
\[\d+(?:,\s*\d+)*\]
```

### How to use find to search for abstract/keywords

find and replace with nothing:
```
abstract\s*=\s*"(.|\n)*?",
```

then find:
```
\n[ \t]*\n
```
replace:
```
\n
```
