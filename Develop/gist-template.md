# Regex Tutorial

Matching an Email – /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/ Regex. There are some tricky concepts to understand, but regular expressions can do some pretty incredible things. Here we will look at a particular example that of matching an email using regular expression. Then we will move on to breaking down components of regular expressions.
## Summary

Regex Pal is an excellent tool if you are trying to break down the different bits and pieces. Regular expressions, at first, look scary or intimidating because it is a big extended group of letters, numbers, characters, tokens, dashes, slashes +’s. It is a lot to figure out right at first. However, a significant part about this is that not only can you hover over the different pieces of this expression (and it will help you break it down), but it also has the separate parts color-coded. So a viewer can say, this is part of this, this is a part of that, and here is how they fit together. So I found this tool particularly helpful. is that not only can you hover over the different pieces of this expression and it will help you break it down, but it also has the separate parts color-coded so that you can say, ok this is part of this, this is a part of that, and here is how they fit together and so I found this tool particularly helpful

Caret ^ - the beginning of a string () captures a group $ - end of string or line [] character set a-z matches a character between a-z 0-9 matches a character between 0-9 underscore = underscore . is an escape character = - dash = dash match one or more than one of the tokens
Matching an Email – /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

## Table of Contents

- [Anchors](#anchors)

Anchors include symbols like a caret and a dollar sign at the end of the string or \A letter to describe word boundaries or lack thereof. The \letter means being a or end of a string. About anchors, an example of an anchor would be a carrot a $. Anchors or a way of telling you where you are at, so basically, is it that start or the end? \A refers to the start of a string. It is probably important to note as we start to talk about anything to do with regex that regex can vary a little bit depending on which language you are looking at. Some characters are the same across multiple languages and have the same meaning, but that is not true for all of them, so it is to find good references. In the documentation I looked at, some symbols or characters or tokens had notes with them saying all engines except JavaScript, or this except for Ruby or all of these are the same depending on the language, so it is important to watch out for that. Quantifiers Examples of regular expressions quantifiers are *, +, ?, {3}, {4,7}, {5,}.

- [Quantifiers](#quantifiers)

Quantifiers in regex include ?,*, +, and then items within curly braces/brackets. With quantifiers, you are basically trying to find how many times something happens or how many of certain things there are. In my research, I found that Quantifiers can also be eager reluctant possessive depending on how characters are placed together. As you hover over those different parts of the expression, it will tell you the purpose of those sets of letters or characters to help make up a particular expression. Then at the bottom of the page, they also have a nice little cheat sheet. For quantifiers, if you look at W3 schools, almost or all of the descriptions for what quantifiers start with “matches any string with” or “matches any string that.” And then in each of the examples they provide, it says more specifics, for example, matches any string with and end at the end of it or that is for the n $ example. Or it could say matches any string that is followed by a specific string, and that would be if you had a? Equals n. Basically, quantifiers tell you what to look for to match OR Operator

- [OR Operator](#or-operator)

Alternation is actually a simple OR, which is exhibited or declared with a vertical line, so for example, if you wanted to find three different things, a cat, a dog, and a bird, you would put cat|dog|bird. this would make it so that you were requesting to look for all three of those different items are groups at the same time yeah also individually https://javascript.info/regexp-alternation

- [Character Classes](#character-classes)

Character Classes An example of character class would be a-z or A-Z - when you see this in a regular expression, it is not just talking about finding a time frame see it is saying find anything, or you can look through anything that falls in the alphabet, so anything between A-to-Z could be any one of those characters you could use this A-to-Z, or you could also think about numbers, that is a possibility with numbers as well

- [Flags](#flags)

In JavaScript, when we are talking about flags, there are only six flags that work with JavaScript and retro regular expressions; those are “I,” which is a flag that searches for casein sensitive. There is a G; this flag looks for anything without the specified request. M is multiline and makes it so that you can use a dot to match. Finally, the character U flag helps to process pairs correctly, and y is the sticky flag it looks for a particular position. https://javascript.info/regexp-introduction

- [Grouping and Capturing](#grouping-and-capturing)

Grouping and Capturing On capturing and grouping, an easy example would be to say that you have (cat). if you are thinking about grouping and capturing and what if we use the sixth sample of the word cat with him parentheses, then a regular expression is going to look at the screw cat and convert it or instead view it as individual characters so it would be viewed as C A T

- [Bracket Expressions](#bracket-expressions)

Bracket expressions, there is a great article I would suggest (link at the bottom of this section). In it, he breaks it down between square brackets, curly braces, and parentheses and what they each mean. Brackets tell the viewer, user, or program to look at what is in between the brackets and see if any individual characters can match. With the curly braces, they do something a little bit different their job is to say or define a specific number of things to match. So, for example, you could say I want to match this one example precisely two times. And for parentheses, these are remembered matches, so the parentheses help anytime you want to do something with a particular part of a match you can refer back to a remembered match or remembered portion of a match that would you be useful to bring up at another time https://javascript.plainenglish.io/regular-expressions-brackets-f2d6f69ffe13 https://javascript.plainenglish.io/regular-expressions-brackets-f2d6f69ffe13

- [Greedy and Lazy Match](#greedy-and-lazy-match)

Greedy and Lazy Match Greedy and lazy matches. One of the easiest to understand to describe greedy and lazy matches was from the answer to a stack overflow question. A greedy match will look for the longest possible string, but a lazy match will look for the shortest one. https://stackoverflow.com/questions/2301285/what-do-lazy-and-greedy-mean-in-the-context-of-regular-expressions https://javascript.info/regexp-greedy-and-lazy https://www.w3docs.com/learn-javascript/greedy-and-lazy-quantifiers.html



- [Boundaries](#boundaries)
- [Back-references](#back-references)
- [Look-ahead and Look-behind](#look-ahead-and-look-behind)

## Regex Components

### Anchors

### Quantifiers

### OR Operator

### Character Classes

### Flags

### Grouping and Capturing

### Bracket Expressions

### Greedy and Lazy Match

### Boundaries

### Back-references

### Look-ahead and Look-behind

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
