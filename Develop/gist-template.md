# Rejex Tutorial

## Project Description

I will be analyzing an email matching rejex.

## Summary

In this project, I will be describing the rejex for matching an email. The project will analyze each individual piece of the rejext and describe what the funciton/purpose of it is. The email rejex code that will be analyzed is listed below.

## Matching an Email

/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

## Table of Contents

- [Anchors](#anchors)
- [Grouping and Capturing](#grouping-and-capturing)
- [Quantifiers](#quantifiers)
- [Character Classes](#character-classes)
- [Bracket Expressions](#bracket-expressions)
- [Greedy and Lazy Match](#greedy-and-lazy-match)

## Regex Components

### Anchors

* The ^ at the beginning of the rejex means it matches any string that starts with a specified component. Since the next part of the 
rejext is a parenthesis (grouping and capturing) the specific characteristics the string start must have is specified in the goruping and capturing portion of the rejex.

* Another anchor is located at the end ( $ ) . This differs than the ^ anchor tag in the way that it matches the end part of a string. The end part this rejex is looking for is enclosed in a grouping and capturing.

### Grouping and Capturing

* After the Anchor ( ^ ), the reject included a grouping and capturing to speficiy what the start of the rejex is looking for. Before the Grouping and Capturing portion of the rejext, there is a ^ (Anchor). So putting these two portions together means this portion of the rejext starts with ([a-z0-9_\.-]+). This is not a normal string word, so these are additional rejex properties.

* After the @ there is another parenthesis ([\da-z\.-]+) which represents Grouping and Capturing.

* And finally there is another grouping and capturing at the end after the dot -> ([a-z\.]{2,6}).

### Quantifiers

* At the end, there is a {2,6}, which is a quantifier. The end matches a string in [a-z\.] that is at least 2 but no more than 6 in length. This represents the .com portion of the email.

### Character Classes

* There \d is the character class. This means that this part will only match a non digit character.


### Bracket Expressions

* The Bracket Expressions are used within the grouping and capturing to capture the different character or numbers that could be included in an email string.


### Greedy and Lazy Match

* The + sign is a greedy and lazy match. This is for the part of the rejex after the character classes that basically extends the character as many times as necessary before the ( . ). This means that it can handle any length email.


## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)

My name is Brit Sovic, I conduct data analysis and database creation for the Infectious Diseases Department of Medicine at Columbia University Irving Medical Center.

You can look at my other coding work by visiting my GitHub profile at:  https://github.com/bsovic23
