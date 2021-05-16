# CollectionsExercise
A Java program that reads a text file, specified by the first command line argument, into a List.
The program should then print random lines from the file, the number of lines printed to be 
specified by the second command line argument. Write the program so that a correctly sized
collection is allocated all at once, instead of being gradually expanded as the file is read in.
Hint: To determine the number of lines in the file, use java.io.File.length to obtain the size of the file,
then divide by an assumed size of an average line.
