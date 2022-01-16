# wordle_solver

Solves Wordle game (https://www.powerlanguage.co.uk/wordle/)

Required: Download Collins Scrabble words dictionary from following location:

https://drive.google.com/file/d/1oGDf1wjWp5RF_X9C7HoedhIWMh5uJs8s/view (Also available in github along with this notebook)


How to use:
* Launch the notebook in Jupyter or Google Colab, with the Dictionary file in same folder. 
* Enter the guess given by the notebook (starts from ln[7] in the notebook
* Based on the response from Wordle game, enter the response as a list of integers as following: Enter Wordle response as a list. Yellow = 1, Green = 2, Grey = 0. So for the word CARES, if you get C as yellow, A as green, and rest as grey, response would be [1,2,0,0,0]
* Run the cell no 8 after changing response. A new guess word is returned. Repeat this step as many times as required.
