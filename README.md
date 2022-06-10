

 
ABSTRACT

Mental health is very important at every stage of our lives, from childhood and adolescence through adulthood. mental state includes our emotional, psychological, and social well-being. It affects how we expect, feel, and act. It also helps determine how we handle stress, relate to others, and make healthy choices. mental state is very important at every stage of life, from childhood and adolescence through adulthood.

Although the terms are often used interchangeably, poor psychological state and psychological illness don't seem to be the identical. someone can experience poor psychological state and not be diagnosed with a mental state. Likewise, an individual diagnosed with a psychopathy can experience periods of physical, mental, and social well-being.

There is no single cause for psychological state. variety of things can contribute to risk for psychological state, such as: early adverse life experiences, like trauma or a history of abuse (for example, abuse, statutory offence, witnessing violence, etc.), experiences
related to other ongoing (chronic) medical conditions, like cancer or diabetes, biological factors or chemical imbalances within the brain, use of alcohol or drugs, having feelings of loneliness or isolation, experiencing fear within the context of the COVID-19 pandemic and anxiety, stress, fear of failure/unemployment etc.

Our website aims at providing the users with a platform that may help them to be told the way to address these issues in a very healthy way.


















PROBLEM STATEMENT

To create a website for improving mental health which offers multiple features like relaxation The main feature will be a chat that will analyse the user’s texts and use sentiment analysis to predict their mood to offer resources as well as connect them to mental health professionals appropriately

Motivation

Fear, worry, and stress are normal responses to perceived or real threats, and now and then once we are faced with uncertainty or the unknown. So, it is normal and understandable that folks are experiencing fear within the context of the COVID-19 pandemic. Added to the fear of contracting the virus in a very pandemic like COVID-19 as a result it disturbs our smooth daily life and leads to slow down the spread of the virus. Faced with new realities of functioning from home, temporary unemployment, home-schooling of youngsters, and lack of physical contact with other relations, friends and colleagues, it's important that we glance after our mental, also as our physical, health. Our website aims at providing the users with a platform which will help them to be told the way to address stress, fear, anxiety and worry during a healthy way.


OBJECTIVES AND GOALS OF PROJECT

•	Accurately Analyze mood of users from the messages they sent 
•	Provide appropriate resources according to the calculated mood of the user
•	Have features that allow users to relax like listening to music, playing games, reading         motivational books
•	To successfully integrate sentiment analysis into the website chat
•	To store all the user data accurately in the database 
•	To Connect the Front end of the website to the database

CHALLENGES

•	Filtering repeated words
•	Filtering What and how questions 
•	Removing Special characters
•	Removing Emojis
•	Managing npm libraries
•	Creating socket between users in chat interface















 
Requirement specifications

Software Requirements / Stack used:

FRONT-END:

HTML
CSS
Bootstrap
JavaScript
Visual code studio

Technologies used at server side:

Node js
Express js

Packages used/libraries used from npm package manger:

Http
Path
Socket.io

Hardware Requirements:


Windows requirements	Linux requirements
Processor	Intel Pentium 4 or higher
Memory	2 GB minimum, 
4 GB recommended
Screen resolution	1280x1024 or larger
Application window size	1024x680 or larger

 

SYSTEM DESIGN/ARCHITECUTURE DESIGN

The user first logs in or registers to the website. They can then use the multiple features of the website such as reading books, playing games, listening to music, tools to meditate, read blogs or chat. If they want to chat with other users online, they will enter a chat username and choose a chatroom. After they leave the chat, a score will be calculated according to the mood reflected in their messages and they will receive their score. They will then be directed to a resource page to help them with their mental health according to the score calculated. If the score is greater than 8 they are directed to page for content users, If the score is between 6 and 8 they are directed to page for moderately distressed users and if the score is higher than 6 they are directed to page for extremely distressed user (Refer Fig1.1)

 
Fig 1.1



The HTML, CSS and JavaScript send requests and receive responses from the MongoDB database and Node.js server. For the sentiment analysis of the user messages, The messages are processed by filtering out repeated words, removing questions (questions that begin with what, where, why etc), excluding special characters and emojis. Then all the words are categorized and given a score. (Refer Fig 1.2.)

 




IMPLEMENTATION OF SYSTEM

The front end of the website is done using HTML, CSS, JavaScript. In the backend Node.js is used as well as MongodB for the database. • The user has to log in or register with appropriate details. When a user registers their details will be sent to a MongoDB database. For login the entered details will be compared to those in the database. • There are 7 main pages, a homepage, meditate page, music page, games page, book reading page, blog reading page and chatroom page • The homepage allows the user to access the various features of the website. It also contains a motivational quote of the day, link to blogs that are based on wellness and improving mental

health. It also contains a form to contact the website admin • The meditate page has options to play nature sounds like rain, wind and a timer for different values to help the user meditate peacefully • The music page links the user to the Spotify music where they can listen to the music of their choice and relax • The game page has a short memory game, it allows the user to concentrate and improve their memory as well as creating a distraction from their problems • The book reading page contains many online versions of motivational and self-help books that will allow the user to introspect and self-improve • The blog reading page contains links to specially curated blog posts that relates to mental health and wellness that will help the user • The chatroom page directs the user to enter a chat username and choose a chatroom. Then the user exchanges messages with anybody online in the chat room and discusses whatever they want. After they finish exchanging messages, sentiment analysis of their messages is performed. Using Node.js keywords that relate to feelings, emotion, wellness etc. are given a individual score according to their valence. A total score is calculated by adding all of them and a comparative score is then calculated and a score for their mood is generated. This score then presented to them and they are directed to page containing resources to improve their mental health and wellness according to their score. There are 3 pages that contain resources one page for content users which has links for a simple yoga video, online journaling, link to guided meditation videos and others that are all just simple tools to reduce daily stress, improve concentration and increase general wellbeing. The second page is for moderately distressed users and it contains link to incredible ted talk that is about dealing with depression and anxiety, a link to a website that allows users to discuss their problems with a willing listeners and other links that provide support to those who aren’t in a great mental state. The third page us for extremely distressed users it contains links on information for mental health hotlines, link to an online therapy website ,a website to screen mental illness to get a preliminary diagnosis and other helpful tools to help an individual who is need of more immediate help.The score is stored in the database attached to the user.





Modules - 

Home - 




A home page is the default or front page of a site. It is the first page that visitors see when they load a URL. It contains a header part which has links to all the main modules of the application. It contains explore division where users can navigate form home to different parts of the website and contains contact information at the end of the page. It will also contain a motivational quote of the day, link to blogs that are based on wellness and improving mental health.

 
 

 

 

























Socialize – 

This module is a type of login module where the user can select a specific chat room along with his username to join the chat room and use the features of the chat module.
 

Chat – 

This is the core part of the website in which the user chats with the system by giving his input and the inputs are given to the analysis module. It contains a chat bot which provides a human like conversation with the user.
 














Analysis – 

The system performs the sentiment analysis using various NLP techniques on the given input and gives the user with a mental status score and based on the score the user will be redirected to the suitable webpages for his metal status.
  

Books – 

In this module we will suggest some great books which help in improving and maintaining a good mental status and develop a healthy mental lifestyle and links to that book.
 












Meditate – 

In this module we will provide a webpage where a user a set a timer to meditate and contains relaxing background music.
 


Contact – 

The Contact module allows site visitors to send emails to other authenticated users and to the site administrator.


 
















Games –


The game module contains a puzzle game where user has to choose the pair of cards with same content and a timer will be monitoring the time period in which the user is solving the puzzle.

 


Sentiment Analysis:

We’ve used a Node.js module sentiment.

Sentiment is a module that uses the AFINN- 165 wordlist and Emoji Sentiment Ranking to perform sentiment analysis on arbitrary blocks of input text.

AFINN is a list of words that we used which is rated for valence with an integer between minus five (negative) and plus five (positive). We performed the sentimental analysis by cross-checking the string tokens (words, emojis) with the AFINN list and getting their respective scores. For example, love has a value of 3 where allergic has value of -2.

The total score is the sum of each word’s individual score.

Algorithm:

Returned Objects
Score: The sentiment ratings of recognized words are added together to provide a score.
Comparative: The input string's score is compared.
Calculation:  A list of words with a negative or positive valence, together with their AFINN scores.
Token: All tokens discovered in the input string, such as words or emojis.
Words: A list of words retrieved in the AFINN list from the input string.
Positive: A list of positive words identified in the input string in the AFINN list.
Negative: A list of negative terms detected in the input text in the AFINN list

![image](https://user-images.githubusercontent.com/66869358/173076183-074e39e8-1029-4371-acac-9f47c9e1c0e2.png)
![image](https://user-images.githubusercontent.com/66869358/173076231-b201181f-c572-4731-a6d3-a9161ce2fd73.png)
![image](https://user-images.githubusercontent.com/66869358/173076293-9dfc35e3-07c4-414f-b0d8-b1cfa04e0f68.png)
![image](https://user-images.githubusercontent.com/66869358/173076322-fc818fe2-4c44-4c31-9ef0-d08c471da985.png)
![image](https://user-images.githubusercontent.com/66869358/173076402-d23e6261-d523-45c0-b910-c2e8d20996ce.png)
![image](https://user-images.githubusercontent.com/66869358/173076496-ba6f75f8-cfc6-47ae-93ee-38a818bd5fd9.png)
![image](https://user-images.githubusercontent.com/66869358/173076526-4a49caa4-2899-4a8c-9115-6f555bc205c7.png)
![image](https://user-images.githubusercontent.com/66869358/173076592-9ec77605-818c-4abc-b3fa-1bfb73b5a0f0.png)
![image](https://user-images.githubusercontent.com/66869358/173076613-061062bb-595b-4cc0-952a-c86b7a832d0b.png)










Calculations:

(max positive score * number of tokens) / number of tokens
Once the user leave the chat we call on the sentiment analysis function from the module and calculate the score by adding the valence of each key word which is present in the AFFIN dataset that is in their messages ,a comparitive score is also calculated .

Then the score is checked if it is greater than 8 the user is sent to the page with resources for content users ,if it is less than 8 and greater than 6 they are sent to the page with resources for moderatley distressed users and if the score is less than 6 they are sent to the page with resources for extremely distressed users

DATASET

The sentiment analysis uses AFINN-165 wordlist and Emoji Sentiment Ranking AFINN -is a list of words rated for the sentiment analysed from it with an integer between minus five (negative) and plus five (positive). Emoji Sentiment Ranking -Is a list of the sentiments of the emojis is computed from the sentiment of the tweets in which they occur.









































RESULTS AND DISCUSSION

For the chatbot feature in our project. The chatbot should read the texts in the chatroom and once the user leaves the chat and it should perform the sentiment analysis of the conversation and direct the user to the appropriate web page for resources that includes a page for content users, a page for moderately distressed users and a page for extremely distressed users according to their state of mind To test the sentiment analysis feature of the website. We carried out 20 different conversations in various chat rooms with in different moods that correspond to to a particular resource page and then we compared the expected output to the output we get from the website.


Conversation Index Number	Expected Page	Output Page	Accurate
Conversation 1	Page for moderately distressed user	Page for moderately distressed user	Yes
Conversation 2	Page for extremely distressed user	Page for extremely distressed user	Yes
Conversation 3	Page for content user	Page for content user	Yes
Conversation 4	Page for extremely distressed user	Page for extremely distressed user	Yes
Conversation 5	Page for moderately distressed user	Page for extremely distressed user	No
Conversation 6	Page for content user	Page for content user	Yes
Conversation 7	Page for moderately distressed user	Page for extremely distressed user	No
Conversation 8	Page for extremely distressed user	Page for extremely distressed user	Yes
Conversation 9	Page for content user	Page for content user	Yes
Conversation 10	Page for moderately distressed user	Page for moderately distressed user	Yes
Conversation 11	Page for content user	Page for content user	Yes
Conversation 12	Page for extremely distressed user	Page for extremely distressed user	Yes

Conversation 13	
Page for moderately distressed user	
Page for moderately distressed user	
Yes
Conversation 14	Page for content user	Page for moderately distressed user	No
Conversation 15	Page for extremely distressed user	Page for extremely distressed user	Yes
Conversation 16	Page for moderately distressed user	Page for moderately distressed user	Yes
Conversation 17	Page for moderately distressed user	Page for moderately distressed user	Yes
Conversation 18	Page for content user	Page for extremely distressed user	No
Conversation 19	Page for content user	Page for content user	Yes
Conversation 20	Page for moderately distressed user	Page for moderately distressed user	Yes

After analyzing the results from Table  it is noted that the sentient analysis has a 75% accuracy








CONCLUSION AND FUTURE
ENHANCEMENTS

A website to improve mental health has been created in HTML, CSS, MongoDB and Node.js. The website is easily navigable and clear for the users. Features that allow user to read books, play games, meditate, listen to music, read blogs have been added to allow the users to relax, focus on improving themselves and to create a calming influence on them. A chat bot that uses sentiment analysis to understand the readers major mood has been created so that through the act of chatting with other users, the bot can detect the sentiment and provide appropriate resources to improve the mental health of the user. The website helps users cope with stress and helps create a positive outlet for them

In the future we will work on adding extra features such as ability to connect with therapists and medical professionals	directly,location-based helpline numbers etc., to provide an even better experience to the user. The website can be improved by perfecting the reactivity of the site on different screens. In the case of the sentiment analysis there is work to be done in helping the chat to better understand context of the words, sarcasm, jokes, double negatives to help improve its accuracy.
