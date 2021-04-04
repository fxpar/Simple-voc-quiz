![works also offline](https://img.shields.io/badge/Ready%20for%20Offline-100%25-green) ![Cognitive load](https://img.shields.io/badge/Minimum%20cognitive%20load-100%25-green) 

![Works on windows](https://img.shields.io/badge/Windows-100%25-blue?logo=Windows) ![Works on android](https://img.shields.io/badge/Android-100%25-blue?logo=Android) ![Works on Mac](https://img.shields.io/badge/Mac-100%25-blue?logo=Apple)

# The most simple flashcard

**just paste from a table**
1. Simply paste vocabulary from a spreadsheet (Excel, LibreOffice, Number, Google Sheet...)
1. Click the update buton
1. That's it 😉

**needs just a browser**  
It is just a web page, so you just have to open it in a browser  

**doesn't require internet**   
you can play anywhere as long as your device / browser accepts to open local html files.

**designed for best memorization**  
The minimalistic interface is intended to avoid distraction, and focus on learning.

![simple voc quiz écran](https://github.com/fxpar/Simple-voc-quiz/blob/main/simple-voc-quiz.png)

![écran vocabulaire](https://github.com/fxpar/Simple-voc-quiz/blob/main/simple-voc-quiz-2.png)

# Additional features


## start where you want
to start your training at the 10 row of your vocabulary, just type "10" in the box for the start question

## decide how many questions you want
you want to learn a set of 7 words at a time? no problem, just type 7 in the box for the number of questions

## change the columns of the question and expected answer
If you have multiple columns in your vocabulary, you can change at any time, which column will be the question, and on which column you will be interrogated.
1. just change the number of the column for question and answer below the vocabulary
2. click the update button

## Go to next set when it is memorized
You can tell the quiz to go to the next set of questions after a certain number of rounds. 
By default, it goes to the next level after three stars ⭐⭐⭐

## Force feed your brain
You want it hard? You can set the "force feed mode", so that each mistakes shows you the correct answer... and goes back at the beginning of the set.  
Very good for maximum repetition and for discovery mode, one new word at a time.

## Internationalization
The quiz includes a french and an english interface.  
You can easily add your own language at the bottom of the script.

![more settings](https://github.com/fxpar/Simple-voc-quiz/blob/main/simple-voc-quiz-settings.png)

# Note for teachers
You don't need to have a column with the number of the questions (like the "id" column in the exemple).  
But it is a good idea to include one if you have a long list of vocabulary: easier to set the start at exact place you want... 

# Features
* [x] paste from Excel / LibreOffice (detect "tab" separators)
* [x] use first column as question
* [x] expect second column as answer
* [x] other columns are not used
* [x] show second column header as question label
* [x] show correction on error
* [x] passes to next question on success
* [x] show success / failures as dashes in top bar
* [x] starts again after vocabulary list is over
* [x] responsive width adapt for 600px device
* [x] do not go up of the page when submitting answer
* [x] don't care about lower / upper case (for mobile and tablet with auto capitalization)
* [ ] strip empty rows in vocabulary
* [x] choose which column is used as question
* [x] choose which column is used as expected answer
* [x] filter a long list of vocabulary by start / end question
* [ ] randomize the set of questions
* [ ] filter vocabulary by a "tag" column


# Demo
On github:  
https://fxpar.github.io/Simple-voc-quiz/refactored/?#

On my pedagogy blog:  
https://www.fxparlant.net/quiz-de-revision-du-vocabulaire/
