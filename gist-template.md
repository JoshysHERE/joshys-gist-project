# Joshy's GIST HTML TAG Tutorial!
This will be a tutorial for the regex expression matching an HTML tag. Regex expressions are used to sort through documentation and find matches to a wide variety of queries. These are not exact expressions but they are sets of characters which represent a range of items we want to isolate in a file.

## Summary
Regex: /^<([a-z]+)([^<]+)*(?:>(.*)<\/\1>|\s+\/>)$/

From left to right we have forward slashes wrapping around left to right. ^ and $ are the anchors. ^ means that this is the beginning of the string and $ represents the end of it. The < character has to match the exact character < and the brackets will need to include the range of lowercase letters from a to z. the + character matches its previous token between 1 and ∞ number of times. this may also be known as a greedy symbol. If we repeat this entire regex, we would be able to interpret it as searching for elements from a-z and for the < sign. 

RegEx uses a regular expression pattern to match all <p> tags in the HTML document and extracts the text within each tag using a non-greedy quantifier.


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
- n+	Matches any string that contains at least one n
- n*	Matches any string that contains zero or more occurrences of n
- n?	Matches any string that contains zero or one occurrences of n
- n{X}	Matches any string that contains a sequence of X n's
- n{X,Y}	Matches any string that contains a sequence of X to Y n's
- n{X,}	Matches any string that contains a sequence of at least X n's
- n$	Matches any string with n at the end of it
- ^n	Matches any string with n at the beginning of it
- ?=n	Matches any string that is followed by a specific string n
- ?!n	Matches any string that is not followed by a specific string n

### OR Operator
OR Operators are indicated with | which is applied to [abc] searches for a or b or c. there is one 'or' in the regex which means look for /1 or white space.

### Character Classes
Character classes define a set of characters, including sets of brackets, ., \d (to match any Arabic number), \w (to match any alphanumeric Latin character), and \s. In our regex, these include a-z, \s, and <.
### Flags
These will be found at the end of the regex after the second dash. There are six flags that include g, i, and m for global searches, case sensitive searches and multi-line searches. none of these are in our regex.
### Grouping and Capturing
Portions of a regex delineated by parentheses() where text inside is considered a sub-expression. In the current regex, [a-z]+, [^<]+, ?:>(.*)<\/\1>|\s+\/> are all sub-expressions.
### Bracket Expressions
The range of characters we want to match in the regex. examples of this are a-z and <

### Greedy and Lazy Match

#### Greedy
- atom?
- atom*
- atom+
- atom{count}
- atom{min,}
- atom{min,max}

#### Non-greedy
- atom??
- atom*?
- atom+?
- atom{count}?
- atom{min,}?
- atom{min,max}?


## Author
Hey guys! My name is Joshua Soto. Im from the east coast but i have lived here in San Antonio for 7 years now. I started taking this course with the hopes of becoming a full stack web dev. I am a huge Philadelphia eagles fan and i love my family. In my spare time i like to play with my dog, go on walks and spend time in my garden! 




You can find me on github under the nickname JoshysHERE or click this for my profile -> https://github.com/JoshysHERE

### Github Gist
https://gist.github.com/5527e38bf3c0c18b3467c3b13b82a007.git

### Github Repo
https://github.com/JoshysHERE/joshys-gist-project
