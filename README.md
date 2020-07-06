# Find the most used php functions in your code

## Intro 
Requirement : `gawk`

This count only OOP functions call. Ex : foo->bar()

If you want to catch all the functions you can adapt the regex to `/\w+\(/`. But you will probably need to add a ban list since it will catch all the basics php functions (`if()` , `__contruct()` , etc ...)

## Usage
Set permission:
```bash
chmod +x php_top_functions 
```


Command : 
```bash
./php_top_functions [[folder]] [[max results / optional - default 10]]
```
