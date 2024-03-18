REGEX TUTORIAL - Social Security
Regex, also known as regular expressions, are powerful tools used by developers. In this tutorial, we'll delve into the complexities of regular expressions by breaking down a regex pattern and explaining everythingin detail.

Summary
The regex pattern we'll be exploring is: /^\d{3}-\d{2}-\d{4}$/.

It is often used to validate Social Security Numbers (SSNs) in the format XXX-XX-XXXX, where X represents a digit from 0 to 9.

1. Table of Contents
2. Anchors (^ and $)
3. Quantifiers ({})
4. Character Classes (\d and -)
5. Author's Note

1. Anchors 

In the regex pattern /^\d{3}-\d{2}-\d{4}$/, the ^ and $ symbols are anchors.

The ^ symbol symbolizes the start of the string.
The $ symbol symbolizes the end of the string.
This ensures that the entire string matches the specified pattern, rather than just a part of it.

2. Quantifiers 

The {} culy brackets are called quantifiers & specify the exact number of occurrences of the preceding element.

\d{3} means its exactly three digits.
\d{2} means its exactly two digits.
\d{4} means its exactly four digits.

3. Character Classes 

\d is a shorthand for the digit character class [0-9]. It matches any digit from 0 to 9.
The - character is a literal hyphen.
when Combined, \d{3}-\d{2}-\d{4} matches a sequence of three digits followed by a hyphen, then two digits followed by another hyphen, and finally four digits.

4. Author

This tutorial was written by [Your Name], a passionate web development enthusiast dedicated to simplifying complex concepts for fellow learners. For more tutorials and projects, visit Your GitHub Profile.


gist link: https://gist.github.com/GxUniverse/ab50dbd034370222cc720cff554d2407