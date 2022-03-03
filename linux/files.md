# unique words

Reads file and finds the line that only occurs once.

`cat file1.txt | sort | uniq -u` 


# binary files

Read human-readable strings from a binary file:

`string file1.txt`


# base 64

Decoding

`base64 -d data.txt`


# rot 13

where all lowercase (a-z) and uppercase (A-Z) letters have been rotated by 13 positions

`cat data.txt | tr 'A-Za-z' 'N-ZA-Mn-za-m'`


# hex / hexdump

which is a hexdump of a file that has been repeatedly compressed

```
xxd -r file.txt > newfile

#check file type

file newfile

#change extension to gunzip

mv newfile newfile.gz

#repeat...
```
