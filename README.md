# Document_Similarity
Code to compare how similar two .txt files are.

I assumed the words in the files to be the elements of a n-dimensional space with each word representing a different axis. Taking vectors from origin to that point in space and adding them up effectively gives us all the words in the file. As it did not seem possible to check for relativistic positions of words, comparing the words themselves seemed to be a fair comparision. 

So the code in a nutshell; It calculates the angle between the two file vectors using dot product method and return the cosine of the angle. Higher the value, higher the similarity with 1.00 being the highest rate of similarity and 0.00 being the lowest.

To use the application:
Run the code.
The file asks for the name of the files.
Enter the entire path of the files.
The code then returns a value which depicts the similarity.
