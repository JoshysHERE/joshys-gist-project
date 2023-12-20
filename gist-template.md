# Joshy's GIST HTML TAG Tutorial!
This will be a tutorial for the regex expression matching an HTML tag. Regex expressions are used to sort through documentation and find matches to a wide variety of queries. These are not exact expressions but they are sets of characters which represent a range of items we want to isolate in a file.

## Summary
Regex: /^<([a-z]+)([^<]+)*(?:>(.*)<\/\1>|\s+\/>)$/


## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [OR Operator](#or-operator)
- [Character Classes](#character-classes)
- [Flags](#flags)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)
- [Greedy and Lazy Match](#greedy-and-lazy-match)
- [Boundaries](#boundaries)
- [Back-references](#back-references)
- [Look-ahead and Look-behind](#look-ahead-and-look-behind)

## Regex Components
Regex are literals. That mean they must be wrapped in the / characters. If we use a regex constructor function, we need to enclose it in quotation marks as such: let regex = new RegExp('ab+d', 'i').

### Anchors
Some examples of anchors for regex include ^ and $ which begin and end the expression.

### Quantifiers

### OR Operator
OR Operators are indicated with | which is applied to [abc] searches for a or b or c. there is one 'or' in the regex which means look for /1 or white space.
### Character Classes

### Flags

### Grouping and Capturing
Portions of a regex delineated by parentheses() where text inside is considered a sub-expression. In the current regex, [a-z]+, [^<]+, ?:>(.*)<\/\1>|\s+\/> are all sub-expressions.
### Bracket Expressions
The range of characters we want to match in the regex. examples of this are a-z and <

### Greedy and Lazy Match

### Boundaries

### Back-references

### Look-ahead and Look-behind

## Author
Hey guys! My name is Joshua Soto. Im from the east coast but i have lived here in San Antonio for 7 years now. I started taking this course with the hopes of becoming a full stack web dev. I am a huge Philadelphia eagles fan and i love my family. In my spare time i like to play with my dog, go on walks and spend time in my garden! 




You can find me on github under the nickname JoshysHERE or click this for my profile -> https://github.com/JoshysHERE




