# SnehVora_IITB_ML_Internship_Assignment_Dec2022

Problem-4 (NLP: Panel discussion summarization)

Context:

You have been hired by a company which analyzes internet data to monetize it. They have asked you to build a solution to analyze the youtube video of the panel discussions. Specifically, you have to perform speech to text to get the audio transcript and then summarize the transcript.
Technical details

Input: Youtube URL of a panel discussion

Output: Textual summary of the discussion


<h3>Required Libraries :</h3>

--> !pip install SpeechRecognition            // converting from audio to text

--> !pip install youtube_dl                  // downloading audio file of youtube video

--> !pip install pydub                      // to convert the mp3 file to wav format

--> !pip install os                          // saving the mp3 format and to raname it or to delete it

--> !pip3 install git+https://github.com/ernie-mlg/rpunct.git.      // to add punctuation

--> !pip install gensim                     // to summarize the whole text 


<h3>How to run the code : </h3>

--> Export this file to google colab and run each shell
