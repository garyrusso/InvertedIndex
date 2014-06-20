Inverted Index
==============

Builds an Index that maps words to specific input file and to specific list within the file.

Command line to run accepts a word to search and then a list of files to index.

###Run Command:###

java -jar InvertedIndex-1.0-SNAPSHOT.jar word file1 file2 file3 file4

###Example 1:###

java -jar InvertedIndex-1.0-SNAPSHOT.jar Radiohead C:/temp/items1.txt

###Example 2:###

java -jar InvertedIndex-1.0-SNAPSHOT.jar Radiohead C:/temp/items1.txt C:/temp/items2.txt C:/temp/items3.txt


### Maven Command to build: ###

mvn package



