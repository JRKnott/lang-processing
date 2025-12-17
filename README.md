# Investment Analysis Advisor RAG Pipeline
<img width="3412" height="1651" alt="image" src="https://github.com/user-attachments/assets/3e014d4f-d25f-4ef9-8499-5a385fccf65a" />

## Domain Overview & Problem Statement:
The domain I wanted to focus on in this project is financial advice and how a RAG based agent can help investors by generating advise using a pre-selected set of data. I think this is interesting because currently AI is becoming used more by small-scale investors. As a Finance major, I want to learn a little bit more about Machine Learning applications and how they can be applied to investment services, and this project was a great opportunity for me to do so. 

## A Brief Overview of my Project Pipeline:

<img width="1315" height="748" alt="image" src="https://github.com/user-attachments/assets/8c8c1510-0b9a-4ffb-b897-d6f7303476dd" />

<img width="1338" height="750" alt="image" src="https://github.com/user-attachments/assets/8d210a78-2ab6-4366-b245-4276abf7dfe9" />

These two images display what my project pipeline looks like. The first starts with my data sources, and then moves towards my final output. The second looks at the User Input and the process of getting the output from the LLM Model (ChatGPT). This processed utilized preprocessing and generating chunks utilizing class code through google Colab, aswell as using CrewAI for creating my Agent, and DuckDB for creating my database.

## Data Used:

<img width="2698" height="1160" alt="image" src="https://github.com/user-attachments/assets/89b2b3af-75dc-4f89-8800-6d46a422dce3" />

For this project I utilized a variety of finance related news excerpts, analyst ratings, papers, reports. These sources were from varied creators, such as banks, DJIA, and researchers which was helpful in order ot testing a wide variety of datatypes. In all, although my dataset was limited, it was very helpful as it allowed me to see some flaws in my Agent as I was able to pinpoint problems easier.

## Agent Role and Task Classification:

<img width="2373" height="746" alt="image" src="https://github.com/user-attachments/assets/242ffddf-2519-4e53-a53b-7212318661ce" />

This above image shows the code I used to classify the role, goal, backstory, and task I used to create my Agent. I had some experience through my Generative AI class as to the important purpose of this step. I chose its role to be an Investment Analysis Advisor which is self-explanatory. I set its goal to 'Answer questions and provide advice about the current market situation and investments using the database' in order for it be clear as to what it goals will be. This was helpful in creating a more standard type of response. Finally I kept my Task the same, which was to create a comprehensive answer based off of the database content.

## Installation and setup instructions:
Local: Download Folder, Create own datasources or use own. 
run this: https://colab.research.google.com/drive/1a97iz9a4N8OzQ0_olHIXmvucVBY8GKRE?usp=sharing

## Streamlit APP Link:
https://lang-processing-8aeydrvcgk6m6zb6ej5vtv.streamlit.app/
