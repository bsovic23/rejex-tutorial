# Rejex Tutorial

## Project Description

This project ..

## Summary

Briefly summarize the regex you will be describing and what you will explain. Include a code snippet of the regex. Replace this text with your summary.

## Matching an Email

/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

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

* The ^ at the beginning of the rejex means it matches any string that starts with a specified component. Since the next part of the 
rejext is a parenthesis (grouping and capturing) the specific characteristics the string start must have is specified in the goruping and capturing portion of the rejex.

* Another anchor is located at the end ( $ ) . This differs than the ^ anchor tag in the way that it matches the end part of a string. The end part this rejex is looking for is enclosed in a grouping and capturing.

### Grouping and Capturing

* After the Anchor ( ^ ), the reject included a grouping and capturing to speficiy what the start of the rejex is looking for. Before the Grouping and Capturing portion of the rejext, there is a ^ (Anchor). So putting these two portions together means this portion of the rejext starts with ([a-z0-9_\.-]+). This is not a normal string word, so these are additional rejex properties.

After the @ there is another parenthesis ([\da-z\.-]+) which represents Grouping and Capturing.

And finally there is another grouping and capturing at the end after the dot -> ([a-z\.]{2,6}).

### Quantifiers

At the end, there is a {2,6}, which is a quantifier. The end matches a string in [a-z\.] that is at least 2 but no more than 6 in length. This represents the .com portion of the email.

### OR Operator

### Character Classes

### Flags



### Bracket Expressions

### Greedy and Lazy Match

### Boundaries

### Back-references

### Look-ahead and Look-behind

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)

My name is Brit Sovic, I conduct data analysis for the Infectious Diseases Department of Medicine at Columbia University Irving Medical Center.

You can look at my other coding work by visiting my GitHub profile at:  https://github.com/bsovic23
