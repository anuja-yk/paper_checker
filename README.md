# Paper Checker

## Introduction
- Paper-Checker is a web application that evaluates answers given by the user to the questions asked, by comparing them with the model answers. Thus, this web app will assist teachers in evaluating answer sheets.
- For using this app, the teachers need to store the questions and their respective model answers in a csv (comma separated values)  file.
- The web app will represent questions one-by-one, will get answers from the user and then will compare those with the model answers finally, at the end, showing the total score obtained by the user in tabular format.

## Technologies Used
- The application is developed in the Python programming language (version 3.9) using an IDE (Integrated Development Environment) called ‘PyCharm’.
- The actual web page and the UI (User Interface) has been developed using a Python library called ‘Streamlit’.
- The source-code of the web app has been saved in a repository at Github.
- The comparison between the  model answers with the user’s answers and providing a score at the end, has been tried using the following libraries:
1. Difflib
2. SentenceTransformer
3. OpenAI (ChatGPT) like Large Language Model
- Currently SentenceTransformer has been selected as the final library.

## Demonstration
- User is presented with a question :
![pic1]("\images\demo1.png")
- User fills in the answer :
![pic2]("\images\demo2.png")
- User submits the answer, then the next question appears. This continues till all the questions are answered
- After the last question, a ‘ View Score ’ button appears on the screen.
![pic3]("\images\demo3.png")
- After clicking the ‘ View Score ’ button, the user score is computed in the background and appears in a tabular format with final score percentage.
![pic4]("\images\demo4.png")

## Acknowledgements
I would like to sincerely thank my mentor and father Dr. Yogesh Kulkarni for guiding me throughout this project. I also wish to thank my mother Anjali Kulkarni and my sister Anushka Kulkarni for resolving my queries. 


