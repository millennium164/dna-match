# dna-match
Take each STR (usually 2-6 long) declared in the first row of the DNA database (.csv file), starting from row[1:], and find it's longest consecutive repetition in the given DNA sequence (.txt file).
Append each "longest_run" in a python list, calles str[].
To every row of the DNA database (starting from the second one, the ones that contain the corresponding values of the first row keys), compare each of it's element (from row[1:] i.e. only the integers) to each element of str[].
If every element matches the other, until the end of the list, then we have a match in our DNA database.
