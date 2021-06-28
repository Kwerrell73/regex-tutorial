# Regex Tutorial

Introductory paragraph (replace this with your text)

## Summary

Briefly summarize the regex you will be describing and what you will explain. Include a code snippet of the regex. Replace this text with your summary.

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
Anchors are characters within the regular expression that allow the user to match strings that begins or ends with certain characters (or both). 

### Quantifiers

### OR Operator

### Character Classes

### Flags
The flags property returns a string consisting of the flags of the current regular expression object.
Flags are also called modifiers because they modify the output of a regular
expression and can be used in any order or combination.

|Flag|Description|
|:----:|----|
|d|Generate indices for substring matches.|
|g|Global Search: Match all instances, not just the first.|
|i|Case insensitive: Match will be case-insensitive.|
|s|Allows . to match newline characters.|
|m|Multiline: Anchor meta characters work on each line.|
|y|Perform a "sticky" search that matches starting at the current position in the target string.|
|u|Unicode: Treat a pattern as a sequence of unicode code points.|


### Grouping and Capturing

### Bracket Expressions

### Greedy and Lazy Match

### Boundaries

### Back-references

### Look-ahead and Look-behind
Lookbehinds and lookaheads (also called lookarounds) are specific types of non-capturing groups (used to match a pattern but without including it in the matching list). Lookarounds are used when a pattern must be preceded or followed by another pattern. For example, imagine we want to get all numbers that are preceded by the $ character from the string $4.44 and $10.88. We will use the following regular expression (?<=\$)[0-9\.]* which means: get all the numbers which contain the . character and are preceded by the $ character. These are the lookarounds that are used in regular expressions:

|Symbol|Description|
|:----:|----|
|?=|Positive Lookahead: Asserts that that value given will immediately follow the current position in the string.|
|?!|Negative Lookahead: Asserts that the value given will NOT follow the current position in the string. |
|?<=|Positive Lookbehind: Asserts that that value given will immediately precede the current position in the string. |
|?<!|Negative Lookbehind: Asserts that that value given will NOT immediately precede the current position in the string.|

|Examples|Description|
|:----:|----|
|(?=foo)|What immediately follows the current position in the string is foo.|
|(?<=foo)|What immediately precedes the current position in the string is foo.|
|(?!foo)|What immediately follows the current position in the string is not foo|
|(?<!foo)|What immediately precedes the current position in the string is not foo|

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
