# Regex Tutorial
 
Welcome to my Regular Expression (Regex) tutorial. This tutorial was created to help you understand and define the sequence of special characters. A Regex is a sequence of characters that defines a specific search pattern.

## Summary

The regex featured in this tutorial is /^[\w.-]+@[a-zA-Z_-]+?(?:\.[a-zA-Z]{2,})+$/, which I have created to match an email address.


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
/^  $/
Anchors represent the start and end of the string or regular expression. In the case of this tutorial, my regex is a an email address and it starts and ends with the characters above.
### Quantifiers
[\w.-]+
Quantifiers specify the quantity or repetition of a preceding element. They allow you to match patterns based on the number of occurrences of a specific character, group, or character class. This part represents all the local characters before the @ symbol in the email address.

### OR Operator
The OR Operator or 'or' operator is represented by the | symbol. The OR operator allows you to define multiple alternatives and the regular expression will match if any of the alternatives are found in the input string. For example /cats|dogs/ and /apple|grapes|oranges/. This tutorial doesn't have an example of OR Operators.

### Character Classes
[]
Character Classes are always represented by the square brackets. They allow you to define a set of characters to match. For this tutorial the Character Classes defined are a-zA-Z_-], which represents Uppercase and Lowercase characters from A-Z, an underscore '_' and a hyphen '-'. For example: Website, web-store, and my_domain

### Flags

### Grouping and Capturing

### Bracket Expressions

### Greedy and Lazy Match

### Boundaries

### Back-references

### Look-ahead and Look-behind

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
