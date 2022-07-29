# Fuzzy-match-algorithm

Applications of fuzzy-matching
1. Spell checker
2. Deduplication of records
3. Master data management
4. Plagiarism detection
5. Bioinformatics and DNA sequencing
6. Spam filtering
7. Content search

Fuzzy-matching algorithms
1. Edit distance metric - quantifies how dissimilar two strings are by counting the minimum number of operations required to transform one string into the other
i) Levenshtein distance
ii) Damerau–Levenshtein distance
2. Bitap algorithm - tells whether a given text contains a substring which is "approximately equal" (defined in terms of Levenshtein distance) to a given pattern
3. n-gram - predicts next item in a sequence of text (in form of a Markov model)

LEVENSHTEIN DISTANCE
Levenshtein distance has the following properties:

1. It is zero if and only if the strings are equal.
2. It is at least the difference of the sizes of the two strings.
3. It is at most the length of the longer string.
4. Triangle inequality: The Levenshtein distance between two strings is no greater than the sum of their Levenshtein distances from a third string.

BITAP ALGORITHM
-It is also known as the shift-or, shift-and or Baeza-Yates–Gonnet algorithm
-It states whether a given text contains a substring which is "approximately equal" (defined by Levenshtein distance) to a given pattern.

Input:

Text: womenwhocode

Pattern: code

Output: Pattern found at index: 8

Input:

Text: youareawesome

Pattern: youareamazing

Output: No Match

N-GRAM ALGORITHM
1. n-gram: set of values generated from a string by pairing sequentially occurring ‘n’ characters/words
2. Goal: compute probability of a sequence of characters/words or sentence
3. It predicts next item in a sequence of text (in form of a Markov model)
