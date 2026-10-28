Chapter 2: Grammar (nouns and verbs)


EVERYTHING in vim is basically noun + verb, just like languages.

Combines action (verb) with a movement or text to perform that verb on (a noun).

Common nouns:

h = go left, j = go down, k = go up, l = go right

LEFT DOWN UP RIGHT

<--  v  ^  -->

Word navigation:

w = go to start of next word (continuous blocks of characters, delimited by transitions from keywords to non-keywords and vice-versa)
keywords = characters, numbers, underscores
non-keywords = everything else

W = go to start of next WORD (similar, but everything is a keyword. delimited only by spaces)

b/B previous instead of next versions of w/W. 

e/E goes to END instead of start of next word/WORD.

^, $ is beginning of line, end of line.

gg, G is beginning of file, end of file.

Common verbs:

c = change, deletes everything and puts you in insert mode (to be discussed in further detail later)
d = delete, deletes and copies into Vim's buffer (clipboard)
y = yank, copy
p = paste

repeat verb to act on line, since this is so common! 

Complex nouns, but useful:

i + any of ( [ { < ' " w 

in [something].

for example, diw = delete in word, deletes the word you are in. yi( copies everything inside the ( ) block you are in.

int main(int argc, char *******argv) {}

you can repeat motions in separate ways:

big-long-repo-title second-big-long-repo-title 

prefix motions with numbers to repeat them

item1
item2
item3
item4
item5

miscellaneous actions:
r = replace
x = single char delete