# Title (replace with your title)

Introductory paragraph (replace this with your text)

## Summary
```https?:\/\/(www\.)?[-a-zA-Z0-9@:%._\+~#=]{1,256}\.[a-zA-Z0-9()]{1,6}\b([-a-zA-Z0-9()!@:%_\+.~#?&\/\/=]*)```

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
```^``` this is the anchor tag that starts the line 
```$``` this is the anchor tag that ends the line.
### Quantifiers
```?``` match either one or none in our regex pattern the (www.) is opitional but if included can only be there one time. The same is true for the (s) in https.
```{n}``` match exactly n within whatever it follows. 
```{x,y}``` match a number betweeen x and y. In our regex pattern we have two range quantifiers, the first is {1,256} and the second is {1,6}.
### OR Operator
```|``` this indicates that you can conjoin two patterns and can pass either but not both.
### Character Classes
```a-z A-Z``` these are list of characters that can be matched.
### Flags
```-i, -g``` which would mean case sentitive and global. However, not found within the regex expression above.
### Grouping and Capturing
Groups are defined by () and we treat them as a unit ```(www\.)``` this group requires www. to be handled together. Second group holds a characterset.
### Bracket Expressions
```[]``` thesea are used to make list of characters or groups or literal characters that are acceptable or not. 
### Greedy and Lazy Match

### Boundaries

### Back-references

### Look-ahead and Look-behind
```(?!0{3})``` example of a look-ahead which cannot be used to match three 0's in this case. (npt found in my example above)    

    (?!) - negative lookahead
    (?=) - positive lookahead
    (?<=) - positive lookbehind
    (?<!) - negative lookbehind

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
