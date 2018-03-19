# English-Dictionary
This file contains about 140,000 English words,and you can use some commands to find any word what you want,such as grep.

For instance, you are not sure one word is an English word, so you can just search it from this file.

Actually, I just use it to play a game named "Wordalot". I have not enough vocabularies, and somethings I was stucked. So I just find this way to solve it. Such as,there is a word, it has seven alphabets, the second alphabet is U, and the last alphabet is S, you have M/T/S/N/R/E/B to fill the others. So I use a command,just like 
grep -n "^[mtsnreb]u[mtsnreb]\{4\}s$" English_dictionary
.
It is funny, right?
