# Title (replace with your title)

My name is Yvette Carbajal in the code i will be doing a Regex tutorial explaining the matchingan email Regex

## Summary

This tutorial, the regular expression (regex) localed below. The regex component in this document include: anchors,quantifiers, grouping constructs, bracket expressions, character classes, the OR operator, flags and character escapes. 

The Regex:
Matching an Email – (/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/)

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

Matching an Email – /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

### Anchors

Regex are powerful tools for matching patterns in text. Anchors are special characters in Regex. They play a essential role in defining the postion of the pattern within the string. In the context of email validation like in the this string /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/ 

anchors come in 2 types:
start anchor ^: this means that the pattern must match the start of the string 
end anchor $: this means that the pattern must match the end of the string 


### Quantifiers

In regex the quantifiers are used to specify how many times a pattern should match. Quantifiers are placed after a character, character class, or qroup, in order to determine the minimum or maximum number of times preceding pattern occur.

the + quantifier is used after the pattern [a-z0-9\.-] in the first group ([a-z0-9_\.-]+) this means that the pattern should occurat least once but it can also occur multipe times.

same in the second grouping 

the third grouping {2,6} quantifier is used after the character class ([a-z\.]{2,6}) this group matches a sequence of 2 to 6 lowercase letters or dot this mean the email address must end with a two to six letter top level domain such as .com or .edu ect

### OR Operator

used to specify alternative patterns among regex

crucial for functoning with regular expressions the OR operator allows the creation of flexible and adaptable patterns

### Character Classes

character classes know as character sets are a short and more concise regex that represents specific sets of characters

character classes:
the email regex uses 2 primary character classes: \d and .. character sets are defined within square brackets such as [a-z], [0-9], and [.-]

### Flags

flags are modifiers which affect the behavior of regex by enabling or disabling certain features and are appended to the end of the regex pattern outside the slashes /

/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/ doesn't not use flags 

### Grouping and Capturing

grouping constructs in regex are used to group together one or more characters or sub-expressions and treat them as a single unit within the expressions

applying quantifiers to the group of characters
caputring the designated part of the match for later use
creating backreference for previously match group
applying alteration to group of characters

### Bracket Expressions

the bracket expressions are a fundamental concept in regex used to define a set of characters that can be matched within a single positon in a text string

### Greedy and Lazy Match


### Boundaries

### Back-references

### Look-ahead and Look-behind

## Author

My name is Yvette Carbajal my Github is https://github.com/YvetteCarbajal/yvette-s-regex-tutorial

