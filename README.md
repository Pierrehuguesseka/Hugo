# a) Write a function that takes a list of words like this and joins it into a single string separated by spaces. Print the result.
words = ["I'm", "sorry", "Dave", "I", "can't", "do", "that."]
def print_string(wordlist):
    # TYPE YOUR CODE HERE.
    
    
    print_string(words)
     
     
     
b) How would you split this into separate data values using the comma? 
# Write a function that returns the list of strings.
csvstring = "34,fred  ,25,35.5,24,india"

def separate_words(string):
    # TYPE YOUR CODE HERE.
    
    
    separate_words(csvstring)
    
    
 c) Write a function that uses a for-loop to remove whitespace from around the words using strip, capitalizes the words, and prints the length of each of the strings in your words list above after doing those cleaning operations. Return a clean list of the same words, with caps and no spaces around each one.
 
 words = ['34', 'fred  ', '25', '35.5', '24', 'india']

def clean_words(wordlist):
    """ Takes a list of strings and capitalizes words, removes blank spaces around any of them.
    Returns a cleaned list."""
    # TYPE YOUR CODE HERE.
    
    
    # this should work for you and return the list of cleaned words:
clean_words(words)



d) How do you use index slicing to get the first 4 elements of the "words" list above?
# TYPE YOUR CODE HERE.
# Hugo
