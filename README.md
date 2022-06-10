
CSE1901 - Technical Answers to Real World Problems (TARP)

Project Report


Mental health wellness application with chatbot using sentimental analyzation of chat


    By

19BCE1876		M. Dheeraj Sai
19BCE1866           K. Manoj Kumar
19BCE1867           P. Suhas Reddy
19BCE1363           D.N.S. Kowshik
					
			
			B. Tech Computer Science and Engineering




Submitted to

Dr. Asnath Phamila Y

School of Computer Science and Engineering

 


April 2022


i

DECLARATION 


I hereby declare that the report titled “Mental health wellness application with chatbot using sentimental analyzation of chat” submitted by me to VIT Chennai is a record of bona-fide work undertaken by me under the supervision of Dr. Asnath Phamila Y, School of Computer Science and Engineering, Vellore Institute of Technology, Chennai.  


Signature of the Candidate

 
M. Dheeraj Sai
19BCE1876
 
K. Manoj Kumar
19BCE1866
 
P. Suhas Reddy
19BCE1867
 
D.N.S. Kowshik
19BCE1363



ii

CERTIFICATE


Certified that this project report entitled “Mental health wellness application with chatbot using sentimental analyzation of chat” is a bonafide work of M. Dheeraj Sai (19BCE1876), D.N.S. Kowshik (19BCE1313), K. Manoj Kumar (19BCE1866), P. Suhas Reddy (19BCE1867 and they carried out the Project work under my supervision and guidance for CSE1901 - Technical Answers to Real World Problems (TARP).







Dr. Asnath Phamila Y 
					                               SCOPE, VIT Chennai





















iii
ACKNOWLEDGMENT
Primarily, we would like to thank the almighty for all the blessings he showered over us to complete this project without any flaws.
The success and final outcome of this assignment required a lot of guidance and assistance from many people and we are extremely fortunate to have got this all along with the completion of our project. Whatever we have done is only due to such guidance and assistance by our faculty, Dr Asnath phamila, to whom we are really thankful for giving us an opportunity to do this project.
Last but not the least, we are grateful to all our fellow classmates and our friends for the suggestions and support given to us throughout the completion of our project.


 
M. Dheeraj Sai
19BCE1876

 
K. Manoj Kumar
19BCE1866

 
P. Suhas Reddy
19BCE1867

 
D.N.S. Kowshik
19BCE1363

iv
 
ABSTRACT

Mental health is very important at every stage of our lives, from childhood and adolescence through adulthood. mental state includes our emotional, psychological, and social well-being. It affects how we expect, feel, and act. It also helps determine how we handle stress, relate to others, and make healthy choices. mental state is very important at every stage of life, from childhood and adolescence through adulthood.

Although the terms are often used interchangeably, poor psychological state and psychological illness don't seem to be the identical. someone can experience poor psychological state and not be diagnosed with a mental state. Likewise, an individual diagnosed with a psychopathy can experience periods of physical, mental, and social well-being.

There is no single cause for psychological state. variety of things can contribute to risk for psychological state, such as: early adverse life experiences, like trauma or a history of abuse (for example, abuse, statutory offence, witnessing violence, etc.), experiences
related to other ongoing (chronic) medical conditions, like cancer or diabetes, biological factors or chemical imbalances within the brain, use of alcohol or drugs, having feelings of loneliness or isolation, experiencing fear within the context of the COVID-19 pandemic and anxiety, stress, fear of failure/unemployment etc.

Our website aims at providing the users with a platform that may help them to be told the way to address these issues in a very healthy way.

















iv

INDEX




SI
No.	CONTENT	PAGE No.
1.	ACKNOWLEDGMENT	
2.	ABSTRACT	
3.	(i)objectives and goals of project
(ii)problem statement
(iii)motivation
(iv)challenges	
	Literature survey	
4.	Requirements Specification
Hardware Requirements  
Software Requirements  	
5.	System Design		
6.	Implementation of System	
7.	Results & Discussion	
8.	CONCLUSION AND FUTURE
ENHANCEMENTS	
9.	References		
 
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












LITERATURE SURVEY


S.No	
Authors and Year (Reference)	
Title	
Implementation	
Gaps identified
1.	Chiara Zucco, Barbara Calabrese, Giuseppe Agapito, Pietro H. Guzzi, Mario Cannataro(2019,August)	Sentiment analysis for mining texts and social networks data: Methods and tools	
Sentiment analysis (SA) aims to extract sentiments, emotions or opinions from texts, made available by different data sources like SNs. This review presents a depth study relative to the methods and the main tools for SA. The analysis was performed by defining four criteria and several variables to compare 24 tools with objective criteria. Specifically, the tools have been analysed and tested to verify their usability, flexibility of use, and other specifications related to the type of analysis performed.	Doesn’t mention how tools react to shorter pieces of information fed one by one
2.	Ichiro Kawachi and Lisa F.
Berkman (September 2001)	Social Ties and Mental Health	
The conundrums of establishing the causal effects of social ties on mental health are best settled by randomized interventions. These interventions have taken the form of support group interventions, one-to-one support interventions, or interventions to enhance natural networks.	Work remains to be carried out, however, in elucidating the mechanisms by which specific aspects of ties lead to the maintenance or improvement of psychological wellbeing—and hence, refining the approach to effective intervention.
3.	Ronen Feldman (April 2013)	Techniques and Applications for Sentiment Analysis	
Document-level sentiment analysis; ˲ Sentence-level sentiment analysis; ˲ Aspect-based sentiment analysis; ˲ Comparative sentiment analysis; and, ˲ Sentiment lexicon acquisition.	Many of the commercial sentiment analysis systems still use simplistic techniques in order to avoid these open challenges and hence their performance leaves a lot to be desired.
4.	Rudy Prabowo, Mike Thelwall
(October 2013)	Comparing and Combining Sentiment Analysis Methods	
The Combined method analyses the harmonic mean of the precision and recall for all methods and gives different weights for them. The goal is first to achieve the highest coverage, and then to achieve a good agreement for a given dataset.	While combining all sentiment methods would yield the best coverage, there is a diminishing return effect, in that increasing the number of methods incurs only marginal gain in coverage after some point.
 

5.	Zhao, Shu & Xia, Xiao & Le, Jia. ((Sep 2013)	A Real-Time Web Application Solution Based on Node.js and WebSocket	
On the basis of in-depth study of WebSocket protocol in HTML5 standard, this paper proposes a new real- time web application solution based on Node.js and WebSocket, aiming to significantly enhance real-time performance, and more efficiently using the processing power of the server.
Finally, the new solution is applied in the game	The paper doesn’t mention how to connect the chat to a database and store the data
6.	Swanand Joshi,Amey Ruikar(August,2014)	Sentiment Analysis of Chat Application	
The proposed sentiment analysis system consists of two-phase – Recognition Phase and Distribution Phase. The recognition phase uses a set of features to perform sentiment classification. In the distribution phase, the application server sends out the updated contact lists of all other nodes with the latest evaluated sentiment. This second phase of the system uses PUSH Technology to distribute the result of the sentiment analysis over the network.	Doesn’t provide any security measures to ensure the authenticity of chats.
7.	Leandro Ungari Cayres, Bruno Santos de Lima Rogério Eduardo Garcia and Ronaldo Celso Messias Correia(January, 2020).	Analysis of Node.js Application Performance using MongoDB drivers	They conducted a comparative study of performance between Mongo Client and Mongoose, both solutions of database drivers to MongoDB
In Node.js applications.
The main difference between them is the redefinition of
schema, a factor which is not mandatory in the majority of NoSQL databases, and MongoDB too; but one of these drivers is required. In that way, this experimental study analyses the impact of each driver at CRUD (create, read, update, and delete) operations.	It should be noted that if any additional
resources provided by one of the options, such  as  data verification or ease of implementation, are relevant factors, the choice should be revaluated, however,
this study is quantitative and is not intended to measure the use of additional
resources. which may vary from context and application used.
8.	Hezbullah Shah & Tariq Rahim
Soomro(May 2017)	Node.js Challenges in Implementation	The result of the study concludes from a survey and from literature review the implementation areas and
challenges of the Node.js. Lastly, I will provide suggestions on how to improve to overcome the challenges.	At a developer level, there is a challenge which is seen from the survey results that they
are not feeling it easy to learn the database working and
using the JavaScript environment. And there also seems a lack of enough knowledge among the developers as from the survey results a reasonable
respondents to the questions on the important features
like event driven, non
blocking I/O and asynchronous processing is making the decision about this.
 

9.	Cornelia GYŐRÖDI, Robert GYŐRÖDI, George PECHERLE,
Andrada OLAH (June 2015)	A Comparative Study: MongoDB vs. MySQL	The authors presented us with a comparative
Study of non-relational databases and relational databases. They focused mainly on the implementation of the NoSQL database technology, namely MongoDB, and made a
comparison with another implementation of relational databases, namely MySQL, and thus justified why MongoDB is more
more efficient than MySQL.	Within the same application, sometimes each user is likely to need its own custom  settings and relational databases do not
allow total customization that is based solely on the needs of users. Thus, more and more applications are  beginning  to use a non-
relational database because they provide a  more  flexible structure that can shape after each user’ needs; they are designed  to  store  large amounts of data and they are denormalized databases, which increases performance.
10.	Azhi Faraj, Bilal Rashid, Twana Shareef	Comparative Study Of Relational And Non-
Relations Database Performances Using
Oracle And MongoDB Systems	This research compares the performance of relational and non-relational databases namely Oracle, and MongoDB by executing complex queries on a large set of data that is available in document-based mode and is converted to Oracle tables.	
The results show that data retrieval is significantly faster in MongoDB however some mathematical queries such as aggregation
functions(sum, count, AVG) are better suited to Oracle RDBMS.
11.	Sunil L. Bangare, S Gupta, M Dalal and A Inamdar	Using Node.js to Build High Speed and Scalable Backend Database Server	This paper aims to implement a framework for
application developers which include software bundles
like Node.js  and  MongoDB  and  create APIs  to  connect their application   with   their   database easily without worrying of the server- side coding. Also  this  APIs can be used to create drivers for various platforms like
Android, .Net, IOS etc.	This method is not very efficient and affordable for small-scale developers. Also  there  is  always a  concern  for  the  privacy  of  data as the data is not  stored  in our machines. In order to overcome this problem for the
developers, there needs to be a way for a developer
to build their application along with hosting their own local machine as a database serve
12.	Agrawal, Ameeta & An, Aijun.	
Unsupervised Emotion Detection from Text Using Semantic and Syntactic Relations	This paper proposes a novel unsupervised context-based approach to detecting emotion from text at the sentence level. The proposed methodology does not depend on any existing manually crafted affect lexicons such as Word Net-Affect, thereby rendering the model flexible enough to classify sentences beyond Ekman's model of six basic emotions. The method computes an emotion vector for each potential affect bearing word based on the semantic relatedness between words and various emotion concepts.
The scores are then fine tuned using the syntactic dependencies within the sentence structure	Does Not take into consideration that average semantic relatedness scores from multiple measures (e.g. Normalized Search Similarity or Spreading Activation) may be more accurate than semantic scores from individual measure alone
 
13.	Haryadi, Daniel & Putra, Gede	
Emotion Detection in Text using Nested Long
Short-Term Memory	In this paper, 7 emotions are classified such as anger, fear, joy, love, sadness, surprise, and thankfulness using deep learning techniques that are Long Short- Term Memory (LSTM) and Nested Long Short-Term Memory (Nested LSTM). The results are then compared with Support Vector Machine (SVM). Each model has been trained with 980,549 training data and tested with 144,160 testing data	LSTM and Nested LSTM isn't compared to more sophisticated deep learning models in a challenging dataset to find out the best method for emotion detections
14.	Hakak, Nida & Mohd, Mohsin & Kirmani, Mahira & Mohd, Mudasir.	
Emotion analysis: A survey	This paper summarizes the previous works done in the field of textual emotion analysis based on various emotional models and computational approaches used	Compares mostly models with datasets where the length of the text is large and continuous.
15.	Rui Xia, Zixiang Ding	
Emotion-Cause Pair Extraction: A New Task to Emotion Analysis in Texts	In this work, we propose a new task: emotion-cause pair extraction (ECPE), which aims to extract the potential pairs of emotions and corresponding causes in a document to overcome the shortcomings of emotion-cause extraction. We propose a 2-step approach to address this new ECPE task, which first performs individual emotion extraction and cause extraction via multi-task learning, and then conduct emotion-cause pairing and filtering.	Does not directly extract the emotion-cause pairs in an end-to- end fashion
16.	D. Inupakutika, M. Nadim,
G. R. Gunnam, S. Kaghyan,
D. Akopian; P. Chalela,
A. G. Ramirez;	Integration of NLP and Speech-to-text Applications with Chatbots	This paper presents a case study on integration of NLP techniques with a chatbot to understand human utterances and respond accordingly and make it more intelligent . In the case study chatbot integrated with Google DialogFlow and IBM Watson NLU services	Isn't tailored for functionality with deep neural network-based language
models such as LSTM and Transformer
17.	Nhan Cach Dang, ,María N. Moreno-García and Fernando De la Prieta	Sentiment Analysis Based on Deep Learning: A Comparative Study	The study of public opinion can provide us with valuable information. The analysis of sentiment on social networks, such as Twitter or Facebook, has become a powerful means of learning about the users’ opinions and has a wide range of applications.
However, the efficiency and accuracy of sentiment analysis is being hindered by the challenges encountered in natural language processing (NLP). In recent years, it has been demonstrated that deep learning models are a promising solution to the challenges of NLP. This paper reviews the latest studies that have employed deep learning to solve sentiment analysis problems, such as sentiment polarity.	In comparative studies presented in which were performed by using tweets or reviews datasets, the evaluation of results was made only in terms of accuracy, however the processing time was not considered. Regarding the continuously expanding size and complexity of big data in the future, it is crucial to consider both reliability and time, especially in critical systems requiring a fast response

 

18.	Ema Kusen , Giuseppe Cascavilla, Kathrin , Mauro Conti, Mark Strembec	Identifying Emotions in Social Media: Comparison of Word-Emotion Lexicons	In recent years, emotions expressed in social media messages have become a vivid research topic due to their influence on the spread of misinformation and online radicalization over online social networks. Thus, it is important to correctly identify emotions in order to make inferences from social media messages. In this paper, we report on the performance of three publicly available word-emotion lexicons (NRC, DepecheMood, EmoSenticNet) over a set of Facebook and Twitter messages. To this end, we designed and implemented an algorithm that applies natural language processing (NLP) techniques along with a number of heuristics that reflect the way humans naturally assess emotions in written texts. In order to evaluate the appropriateness of the obtained emotion scores, we conducted a questionnaire- based survey with human raters.	Moreover, the algorithm has shown to be suitable for studying the linguistic features of how users express emotions over OSNs, and not focused on analyzing the language of emotions that are characteristic for OSNs.
19.	Georg Groh, Jan Hauffa	Characterizing Social Relations Via NLP-based Sentiment Analysis	evaluate methods for the characterization of social relations from textual communication context, using email as an example. Social relations are intrinsically characterized by the Cartesian product of weights on various axes (we employ valuation and intensity as examples). The prediction of these characteristics is performed by application of unsupervised learning algorithms on meta-data, communication statistics, and the results of deep linguistic analysis of the message body. Classification of sentiment polarity is chosen as the means of linguistic analysis.	Observed distribution might be an artifact of the small number of datasets evaluated. A larger study of online communication is necessary to gain further insight.
20.	Doaa Mohey El-Din MohamedHussein



A survey on sentiment analysis challenges	A bulk of this writer generated content requires using the text mining techniques and sentiment analysis. But there are several challenges facing the sentiment analysis and evaluation process. These challenges become obstacles in analyzing the accurate meaning of sentiments and detecting the suitable sentiment polarity.
Stagnancy of the comparison circle larger with less research
 
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
