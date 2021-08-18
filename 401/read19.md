# Reading 19

## Regular Expression

Regular Expressions, often shortened as regex, are a sequence of characters used to check whether a pattern exists in a given text (string) or not. If you've ever used search engines, search and replace tools of word processors and text editors - you've already seen regular expressions in use. They are used at the server side to validate the format of email addresses or passwords during registration, used for parsing text data files to find, replace, or delete certain string, etc. They help in manipulating textual data, which is often a prerequisite for data science projects involving text mining.

## Grouping in Regular Expressions

The group feature of regular expression allows you to pick up parts of the matching text. Parts of a regular expression pattern bounded by parenthesis () are called groups. The parenthesis does not change what the expression matches, but rather forms groups within the matched sequence. You have been using the group() function all along in this tutorial's examples. The plain match. group() without any argument is still the whole matched text as usual.

- \w - Lowercase 'w'. Matches any single letter, digit, or underscore.

- \W - Uppercase 'W'. Matches any character not part of \w (lowercase w).

- \s - Lowercase 's'. Matches a single whitespace character like: space, newline, tab, return.

- \S - Uppercase 'S'. Matches any character not part of \s (lowercase s).

- \d - Lowercase d. Matches decimal digit 0-9.

- \D - Uppercase d. Matches any character that is not a decimal digit.

- The + symbol used after the \d in the example above is used for repetition. You will see this in some more detail in the repetition section later on...

- \t - Lowercase t. Matches tab.

- \n - Lowercase n. Matches newline.

- \r - Lowercase r. Matches return.

- \A - Uppercase a. Matches only at the start of the string. Works across multiple lines as well.

- \Z - Uppercase z. Matches only at the end of the string.

- \b - Lowercase b. Matches only the beginning or end of the word.

## shutil — High-level File Operations

#### Copying Files

copyfile() copies the contents of the source to the destination and raises IOError if it does not have permission to write to the destination file.
Copying File Metadata

By default when a new file is created under Unix, it receives permissions based on the umask of the current user. To copy the permissions from one file to another, use copymode().
