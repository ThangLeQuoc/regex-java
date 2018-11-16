# Regular Expression
## Concept
Regular Expression is a special text string for describing a search pattern
## Pattern Usage
### Simple Use
Letters: `abc`  
Digits: `123`  
Not Expression: `^`  
### Wildcard
In some card games, the Joker is a wildcard and can represent any card in the deck.  
Similarly, there is the concept of a wildcard, which is represented by the . (dot) metacharacter, and can match any single character (letter, digit, whitespace, everything).

`.`  
E.g:  
`...` can match `abc`, `234`, `3rZ`  
To escape a dot, (pattern match `.`), use backlash `\.`
### Character Range
`[abc]` : Only `a` or `b` or `c`  
`[^abc]`: Not `a` `b`, nor `c`

### Shorthand Character Classes
`\d` : digit  
`\D` : not digit  
`\w` : word  
`\W` : not word  
`\s` : space  
`\S` : not space  

https://www.regular-expressions.info/refshorthand.html

### Character Repetitions

### Capture Group
### Real case example
#### String validation
#### Quick replacement
We could use the above regular expression with a replacement pattern - $3$2$1$2$4 or \3\2\1\2\4.
### Using regular expression in Java

---
# References
[RegexOne - Learn Regular Expression with simple, interactive exercies](https://regexone.com/)  
[Regxr - Live, responsive tool to learn, build and test regex](https://regexr.com/)  
[Regex: Quantifiers](https://www.regular-expressions.info/refrepeat.html)  
[Regex: Capturing Groups and Backreferences](https://www.regular-expressions.info/refcapture.html)  
[Regex: Character Classes](https://www.regular-expressions.info/refcharclass.html)  
[Regex: Shorthand Character Classes](https://www.regular-expressions.info/refshorthand.html)  
[Some simple pattern](https://blog.patricktriest.com/you-should-learn-regex/)  
