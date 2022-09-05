# AWS_Major_Project
The files included in this project all are important to run the chatbot. 
The sherlock.txt file is utf-8 ext file of the e-book of The Sherlock Holmes.
This text file is used to get phrases which we can translate in any of the provided language in the chatbot.
The sript.py file is run on pc within the same directory as sherlck file, and this script gives us trainingText.zip file, which has reduced sentences without 
special characters and only words that are important to translate. 
The lambdaFucntion.py is used in the backend for the bot to translate the text in the provided language by the user input. This function basically translates
the given phrase into the target language provided by the user.
