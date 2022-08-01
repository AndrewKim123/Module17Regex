# Title (replace with your title)

Module 17: Computer Science for Javascript.

## Summary

We will be analyzing the regex: /^#?([a-f0-9]{6}|[a-f0-9]{3})$/

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [OR Operator](#or-operator)
- [Character Classes](#character-classes)
- [Flags](#flags)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)
- [Greedy and Lazy Match](#greedy-and-lazy-match)


## Regex Components

### Anchors
In this case, the two anchors are ^ and $. 
^ represents the introduction of a string or a line, while $ represents the end of a string or a line. For example, a string with abc$ will match any string that ends with abc.

### Quantifiers
In this case, the two quantifiers are ? and {n}.
? matches any previous character 0 or 1 times. In our case, since ? has a # prior, our expression will either be a string beginning with a # or not. 
{n} matches the previous character n-times. For example, {\a{6}} will match any string that has 6 consecutive digits. 

### OR Operator
In this case, the regex is divided by |. There are two expression split: [a-f0-9]{6} and [a-f0-9]{3}. This means that the regex will match either of those expressions. 

### Character Classes
In this case, the character class being repeated is: [a-f0-9]. A character class will match any character in the brackets. In our case, we have two ranges: a-f and 0-9. This means that it will match any character a - f and 0-9.

### Flags

### Grouping and Capturing
In this case, the regex expression is one big group: ([a-f0-9]{6}|[a-f0-9]{3}). This grouping is with the combtination of the OR Operator: |. 

### Bracket Expressions
Bracket Expressions is a regex that will match a certain pattern of characters within the brackets. For example: [a-z 1-9] means that the string must include at least 1 character that is between a-z or 1-9.

### Greedy and Lazy Match
Greedy means to match the longest possible string, while lazy means to match the shortest possible string. For example: h. + matches 'hell' in hello but the lazy h.+?l matches 'hel'.

## Author
My name is Andrew Kim. My main goal is to explore JavaScript, Node.js, MySQL, CSS, HTML, and more! My GitHub page has alot of projects so come check me out!
 GitHub: https://github.com/AndrewKim123 
