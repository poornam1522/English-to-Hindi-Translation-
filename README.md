# English-to-Hindi-Translation-
This code using 'googletrans' module from the python.
here is the code to instal the module : pip install googletrans==3.1.0a0
What & Why am I doing via this code?
The aim of the code is to translate in a better way so that the output should be in a language that we talk in daily basis which is a mix of local language + english ( hindi + eng in this case). 
​
If this translation is sucessfull, we can impliement this using AI for the auto caption generation in the social media sites that use video streaming. 
​
I know we are annoyed by the hindi captions on the english video that fetches words we doesnt even know and words we dont use in daily basis even though they are hindi words.
I am trying two different codes here with an aim to convert english to any of the local languages of India ( its hindi in this case) such that the translation should not be creepy with pure word to word meaning derived sentences. 
How does the code-1 work?
Lets
The code uses python which has a wide range lof rich libraries that comes handy while developing programs.
Here I am using the 'googletrans' module which provides a simple API for translating text between languages. 
​
Lets define a function called translate_sentence(), which takes an English sentence as input and returns the translated sentence in Hindi. 
​
The function uses the Translator() class from the googletrans module to do the translation.
​
Lets add a try-except block to the translate_sentence() function. The try block tries to translate the sentence and return the translated sentence. 
​
This step is to return the english word as it is if the function cant find any exact hindi meaning for a word. for example, DEMO should return as it is. This is because the googletrans module does not have a translation for the word "demo" in Hindi. In this case, the program will simply return the English word as it is.
​
The except block catches any exceptions that are raised, and it returns the original English sentence.
​
The main function of the program prompts the user to enter an English sentence. It then calls the translate_sentence() function to translate the sentence and prints the translated sentence.
How does the code 2 work?
hindi word
This code works the same as the previous code, but it adds a few more checks to the translate_sentence() function.
​
First, it checks if the translation is not None and not empty, that is if it fails to find an exact translated word or not. 
​
If the translation is None or empty that is, if it failed to find the exact hindi word, then the function returns the English word.
​
Second, the function checks if there is an error. If there is an error, then the function also returns the English word.
​
This ensures that the function will always return the English word if the Googletrans module cannot find an exact Hindi meaning for the word.
