# END2_Assignment_5

# Data Augmentation
Data Augmentation is the process that enables us to increase the size of the training data without actually collecting the data.

![Data Augmentation](https://github.com/Aditya701/END2_Assignment_5/blob/main/Images/augmentation.png?raw=true)
# Different Approaches for Text Data Augmentation

- Back Translation
- Synonym Replacement
- Random Swap
- Random Deletion

## Back Translation

In this method, we translate the text data to some language and then translate it back to the original language. This can help to generate textual data with different words while preserving the context of the text data. 
Language translations APIs like google translate, Bing, Yandex are used to perform the translation. For example, given the sentence:

![Back Translation](https://github.com/Aditya701/END2_Assignment_5/blob/main/Images/back_translation.png?raw=true)
## Synonym Replacement

Randomly choose n words from the sentence that are not stop words. Replace each of these words with one of its synonyms chosen at random. 
For example, given the sentence:
This article will focus on summarizing data augmentation techniques in NLP.
The method randomly selects n words (say two), the words article and techniques, and replaces them with write-up and methods respectively.
This write-up will focus on summarizing data augmentation methods in NLP.
## Random Swap

Randomly choose two words in the sentence and swap their positions. Do this n times. 
For example, given the sentence
This article will focus on summarizing data augmentation techniques in NLP.
The method randomly selects n words (say two), the words article and techniques and swaps them to create a new sentence.
This techniques will focus on summarizing data augmentation article in NLP.
In this method, we translate the text data to some language and then translate it back to the original language. This can help to generate textual data with different words while preserving the context of the text data. 
## Random Deletion

Randomly remove each word in the sentence with probability p. 
For example, given the sentence
This article will focus on summarizing data augmentation techniques in NLP.
The method selects n words (say two), the words will and techniques, and removes them from the sentence.
This article focus on summarizing data augmentation in NLP.
You can go to this repository if you want to apply these techniques to your projects.

