# Regular Expression

## base format
/[tT]he/gm

## rule
- []
- {}
- + * ?
- `\d` `\w` `\W` `\s` `\S`
- () (?<name>)
- `?:`
- `?<=` `?<!` `?=`
- `g` `i` `m`

## phone number match
```
(?:(\+1)[ -])?\(?(\d{3})\)?[ -]?(\d{3})[ -]?(\d{4})

1234567890
123-456-7890
123 456 7890
(123) 456-7890
+1 123 456 7890

```


