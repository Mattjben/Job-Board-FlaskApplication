# Job-Board-FlaskApplication
Flask application with NLP job classification model embedded within
- The machine learning classification model gives users suggested job categories after creating a job post
RUN ON: Python 3.10.6


Libraries to pip install: 
- flask 
- sqlalchemy 
- flask_login
- os 
- werkzeug
- flask_ckeditor
- nltk
- pickle 

To run make sure working directory contains:

- jobs.db : SQL database which contains all job and user information 
- templates folder: contains all html pages needed to run the flask app 
- static folder: contains all images and css files and models used to run the app
	MAKE sure the static folder contains:
		-  CountModel.pkl which contains the count vectoriser and linear regression model used in part I 
		- stopwords_en.txt
		- nlp.py : generates prediction using bag of words model 
		- style.css: css file used to style html 


**INTRO PAGE:** 
![image](https://user-images.githubusercontent.com/100833957/218224142-802e27a0-14ba-4fff-acce-b71e845de621.png) 
**Job Search:**  
![image](https://user-images.githubusercontent.com/100833957/218224223-83256d5c-bcf0-4e6a-9bd1-adb381f89552.png) 
![image](https://user-images.githubusercontent.com/100833957/218224246-70c8f46a-fe82-4715-917f-4cb602754ecc.png) 
**Sign in/Sign up:**   
![image](https://user-images.githubusercontent.com/100833957/218224270-52104efd-2976-40a8-935f-a13e94856a89.png)                                                        
**Profile**  
![image](https://user-images.githubusercontent.com/100833957/218224365-1084be15-7fc4-474a-ac61-42abd99e35fd.png) 
**Create Post**  
![image](https://user-images.githubusercontent.com/100833957/218224474-e9ca9d35-9ba0-439f-979d-9e30c0efc51d.png) 
**NLP MODEL SUGGESTION**  
![image](https://user-images.githubusercontent.com/100833957/218224455-34282158-45f8-499f-9b26-e3759b64f201.png) 

