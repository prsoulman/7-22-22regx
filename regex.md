# Regex Explanation for E-mail matching

The Gist dives into the regex expression for E-mail validators.

## Summary

The expression /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/ is for validating an email address. This perticular regex is used to matching email regex is used to validate an email address. For instance, if we would use this expression to validate a from the front end to the backend server.


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

### Anchors

Anchors match a position, and can be placed anywhere in the expression. The caret, ^ matches the position before the first character in the string, and the dollar symbol, $ matches after the last character of the string. for example in the expression above, the ^ and $ basically contain the parameters of the regex.

### Quantifiers
Quantifiers specify how many instances of a character, group, or character class must be present for a match to be found. In this case the + is used because it is meant to to match the email exactly.
### OR Operator
N/A
### Character Classes

### Flags
Expression flags change how the expression is interpreted. There are 6: i g m s u y 
### Grouping and Capturing

### Bracket Expressions
A bracket expression []  matches a specific set of single characters and multi-character collating elements, based on any set of list expressions in the bracket expression.
### Greedy and Lazy Match

### Boundaries
A word boundary in regex is a position between \w - \W, or ath the begininng or the ending of a string, if begins or ends with a word character.
### Back-references

### Look-ahead and Look-behind
A Postitive Lookahead matches a group after the main expression without including it in the result.A Negative Lookahead specifies a group that can not match after the main expression.
Positive Lookbehind - Matches a group without including it in the result.
Negative Lookbehind - Specifies a group that can not match before the main expression if there is a match it is discarded
## Author
#### <a href="https://www.github.com/prsoulman">David Rodriguez
