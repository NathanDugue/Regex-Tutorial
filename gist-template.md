# REGEX Tutorial Challenge
# By Nathan Dugue

A Regex is a set of characters that together make a pattern. They can by used inside of code or algorithms to locate, or even locate and replace if that's what you desire, specific patterns inside of a string. An example I will be introducing is a email address that will display 
a regex.

## Summary

The regex that will be displaying an examplified email address is: \b([a-zA-Z0-9_.+-]+)@[a-zA-Z0-9_.+-]+\.\'[a-zA-Z0-9_.+-]i

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
[a-zA-Z0-9_.+-]+ is a component that matches any upper/lower case letter and any number. brackets. The + outside of the bracket is here to show how 
if any username is inputted that it will be validated.

The \.\', component is simply the dot before the extension(com,gov,ca, etc.,).

The plus (+) which is alternatively known as the qualifier, is primarily after the closing bracket which states that any of those characters before it can occur one time or more than one which allows those characters to be validated.

Each bracket validated a email which specifically shows (example@gmail.com). This example email shows that the regex is broken down into very selected components.
### Anchors
An anchor that is shown in this regex component is the \'. (string anchor). Matches at the end of the string the regex pattern is applied to.
Anchors are a different breed. They do not match any character at all. Instead, they match a position before, after, or between characters. They can be used to anchor the regex match at a certain position. 

### Quantifiers
The + is part of that group, which states that the previous item(the collection of characters) can be repeated multiple times. They are also known as a "greedy quantifier" due to the fact that an item can be matched multiple times.

 
### Character Classes
When you see [a-z], that states that any character between a and z will match. It is validated that any upper/lower case will match with the i flag at the end. 

### Flags
The flag that was examplified was i. That flag is to prevent user from typing the whole entire regex components out and to validate it as is. 
Example, [a-zA-Z0-9_.+-]i.

### Bracket Expressions
Brackets are easy and simple, these [] define the character class. 
### Greedy and Lazy Match
The valid concept of greedy and lazy quantifiers is related to the usage of quantifiers and what is being matched. A greedy quantifier matches as many items as it likes, such as the + used above. A lazy match will try to match a Regex pattern just once.
### Boundaries
\b at the start Regex indicates that a match will only occur if the string is matched in isolation.

## Author

Nathan Dugue has taken the time to look into this REGEX code. Nathan has definetly found some interesting information about this REGEX code that simply is an example of a gmail account. My GitHub is: http://www.github.com/NathanDugue. Please don't hesitate to ask questions about my the REGEX Code. This example of a regex code was by author Tobi Sam, wh currently has no Github account.
