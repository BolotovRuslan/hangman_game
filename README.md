# Console game Hangman
###### Writing language - Ruby
## Game description:
 The computer thinks out a word (from the list in the file) and shows how many letters there are.
 The player enters letters one at a time. If the letter is in the word, the computer shows how many times
 it is found in it and in what places. If there is no letter, the computer counts an error.
 If the word is correctly guessed, the player wins. After each mistake, the gallows is drawn.
 7 mistakes can be made in total
## Launching the game:
 To run it ,you need to have Ruby installed on your computer.

 Then copy the contents of the repository to your computer and run the following commands:
 ```
 bundle install
 bundle exec ruby main.rb
 ```
## To add new words to the game:
```
data/words.txt
```
## Example from the game:

```
Слово: К О __ О __ __
          _______
          |/
          |     ( )
          |      |
          |
          |
          |
          |
          |
        __|________
        |         |
Ошибки (2): Х, У
У вас осталось ошибок: 5
Введите следующую букву:
```
