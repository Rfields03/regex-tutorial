# Regex Tutorial

I am creating a tutorial that explains how a specific regular expression, or regex, functions by breaking down each part of the expression and describing what it does.

## Summary

Today I will be covering and breaking down the components of a regular expression used to match Hex Values. Hexadecimal code is a system by which any specific color can be described accurately to a computer, ensuring consistency and accuracy in an electronic display. A hexadecimal color value is a six-digit code preceded by a # sign; it defines a color that is used in a website or a computer program. /^#?([a-f0-9]{6}|[a-f0-9]{3})$/

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
/^#?([a-f0-9]{6}|[a-f0-9]{3})$/
Anchors include symbols like a caret and a dollar sign at the end of the string or \A letter to describe word boundaries or lack thereof. The \letter means being a or end of a string. About anchors, an example of an anchor would be a carrot a $. Anchors or a way of telling you where you are at, so basically, is it that start or the end? \A refers to the start of a string. It is probably important to note as we start to talk about anything to do with regex that regex can vary a little bit depending on which language you are looking at. Some characters are the same across multiple languages and have the same meaning, but that is not true for all of them, so it is to find good references. In the documentation I looked at, some symbols or characters or tokens had notes with them saying all engines except JavaScript, or this except for Ruby or all of these are the same depending on the language, so it is important to watch out for that. Quantifiers Examples of regular expressions quantifiers are *, +, ?, {3}, {4,7}, {5,}.

### Quantifiers
/^#?([a-f0-9]{6}|[a-f0-9]{3})$/
Quantifiers in regex include ?,*, +, and then items within curly braces/brackets. With quantifiers, you are basically trying to find how many times something happens or how many of certain things there are. In my research, I found that Quantifiers can also be eager reluctant possessive depending on how characters are placed together. As you hover over those different parts of the expression, it will tell you the purpose of those sets of letters or characters to help make up a particular expression. Then at the bottom of the page, they also have a nice little cheat sheet. For quantifiers, if you look at W3 schools, almost or all of the descriptions for what quantifiers start with “matches any string with” or “matches any string that.” And then in each of the examples they provide, it says more specifics, for example, matches any string with and end at the end of it or that is for the n $ example. Or it could say matches any string that is followed by a specific string, and that would be if you had a? Equals n. Basically, quantifiers tell you what to look for to match OR Operator

### OR Operator
/^#?([a-f0-9]{6}|[a-f0-9]{3})$/
Alternation is actually a simple OR, which is exhibited or declared with a vertical line, so for example, if you wanted to find three different things, a cat, a dog, and a bird, you would put cat|dog|bird. this would make it so that you were requesting to look for all three of those different items are groups at the same time yeah also individually

### Character Classes
/^#?([a-f0-9]{6}|[a-f0-9]{3})$/
Character Classes An example of character class would be a-z or A-Z - when you see this in a regular expression, it is not just talking about finding a time frame see it is saying find anything, or you can look through anything that falls in the alphabet, so anything between A-to-Z could be any one of those characters you could use this A-to-Z, or you could also think about numbers, that is a possibility with numbers as well

### Flags
In JavaScript, when we are talking about flags, there are only six flags that work with JavaScript and retro regular expressions; those are “I,” which is a flag that searches for casein sensitive. There is a G; this flag looks for anything without the specified request. M is multiline and makes it so that you can use a dot to match. Finally, the character U flag helps to process pairs correctly, and y is the sticky flag it looks for a particular position.

### Grouping and Capturing
Grouping and Capturing On capturing and grouping, an easy example would be to say that you have (cat). if you are thinking about grouping and capturing and what if we use the sixth sample of the word cat with him parentheses, then a regular expression is going to look at the screw cat and convert it or instead view it as individual characters so it would be viewed as C A T

### Bracket Expression
/^#?([a-f0-9]{6}|[a-f0-9]{3})$/
Brackets tell the viewer, user, or program to look at what is in between the brackets and see if any individual characters can match. With the curly braces, they do something a little bit different their job is to say or define a specific number of things to match. So, for example, you could say I want to match this one example precisely two times. And for parentheses, these are remembered matches, so the parentheses help anytime you want to do something with a particular part of a match you can refer back to a remembered match or remembered portion of a match that would you be useful to bring up at another time


### Greedy and Lazy Match
/^#?([a-f0-9]{6}|[a-f0-9]{3})$/
A greedy match tries to match an element as many times as possible. Whereas, a lazy match tries to match an element as few times as possible. In our example we have ? which signifies lazy quantifier. This is referred to a lazy quantifier because it causes the regular expression engine to match as few occurances as possible. We can simply turn this lazy match into a greedy one by adding a ?.

### Boundaries
Word boundary, exhibited with a (\b) it is equivalent to an anchor. It tells the user that this is a word boundary. It is a way to declare here a word/this is a word boundary. Example “fish” within the parenthesis is a word. If a particular regex declared, with anchors, “this is the first of a regex string,” using a ^ carrot, or the end of a string with the dollar sign, then a space or place is being declared. \b asks the programing language to look for that whole word. for example, if we said, please find the entire word “fish.” 

### Back-references
Back-references What does a back-reference look like? It is typically a \ followed by single-digit. Back-reference is a command, which refers to something that already happened or a previous part of a matched regular expression. You could make a better preference by name or number; basically, what you are doing is you are referencing a named group, and you would have a bag/and a K then the name of that group, for example.

### Look-ahead and Look-behind
Look ahead and look behinds allows how matches get handled when using regular expressions. I looked at the website regex buddy also says regular Dash expression .info, and Specifically, I looked at look-ahead and look-behind zero-length assertions on this website. Look ahead and look behinds, also known as look around assertions, are similar to a start and end of the line or anchors. However, look around can match characters, and then they return a result of either a match or no match.

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
