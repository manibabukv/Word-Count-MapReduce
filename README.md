Using the MapReduce concepts you are going to write a python program that will index a set of documents (Provided Below) and create a main function that takes input from a user to search the frequencies of the input (word(s)) in these documents. You are also provided a list of stopwords that you have to remove from each file. 

For example,

if a user inputs the word: "Hello"

the program should output: "The word Hello is repeated 10 times,

                                                  3 times in doc 1

                                                  5 times in doc 3

                                                  2 times in doc 5"

However, if the user inputs the words: "Hello World"
The program should output something like that: "Hello World is repeated 15 times
                                Hello: 3 in doc 1, 5 in doc 3, 2 doc 5
                                World: 2 in doc 1, 3 in doc 3" 

(The output can be as fancy as you want it to be as long as it does not deviate from the goal)
The program should only stop if the user inputs the letter 'q'. 

 

In summary, your program should:

Take a word or a set of words as input.
Create a list with words from each text file.
Remove the stopwords.
Score each document by summing the frequency of each word of the input in the document.
Print the total number of times a word is repeated and where they are located
