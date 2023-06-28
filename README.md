# PassageProcessor

This project was completed as an assignment under Prof. Keerti Choudhary and Prof. Huzur Saran while pursuing COL106, a course on Data Structures & Algorithms taught at IIT Delhi, Delhi, India.

## Description

PassageProcessor is a Java program that implements a 2-3-4 tree data structure to process a paragraph and find various textual information related to it. The program provides functionalities to store and perform various operations on the stored data, such as finding the word with maximum frequency between 2 words and finding the cumulative frequency of words in the paassage between 2 words.

The program consists of two classes:

1. `Tree`: Implements the 2-3-4 tree data structure with methods for insertion, deletion, searching, and other operations. The class maintains a balanced tree structure and ensures efficient operations with a time complexity of O(log n).

2. `Application`: Extends the `Tree` class and includes additional methods to process English passages, store word frequencies, and answer specific queries. The `Application` class uses the 2-3-4 tree data structure to build a dictionary of words and their frequencies from an input file. It provides methods to insert words into the dictionary, increment the frequency of a word, and perform queries to determine the number of strings between two given strings and the string with the maximum frequency within a given range.
