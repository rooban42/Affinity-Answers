# Degree of Profanity Assignment for Internship

## Assumptions made:

* text data and profanity words data are cleaned(no special characters, lowercase).
* profane words used here are synonymous to racial slurs.
* degree of profanity in a sentence is calculated as the ratio of number of profane words and total number of words in the sentence.
* data in text files are properly structured(line by line for each sentence

## assignment.py

There are two functions 

*check_profanity(profane_words, data)*, A function to calculates and returns the degree of profanity for each line a dataset.

*get_data_from_file(path)*, A function to read and return data from text files.
