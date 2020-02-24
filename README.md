# ProjectGroup-16

## Project Idea 1: Natural Language to SQL Analytics

Our project will allow a business user with no SQL knowledge to directly ask analytical questions from a business’s Current/Legacy SQL database. Data should be accessible beyond the dashboards and beyond analysts, thus our goal is to allow you to talk to your data directly using natural language.

Our proposal is to train a deep Neural-net on WikiSQL dataset (Gold standard) with state-of-the-art methods and then parse our SQL dataset to then have NL to SQL translation.

### Abstract
* In the recent trend of chatbot development, it is important to translate human language into the query language. The trend of “data democratization” is forcing us to leverage existing technology in new ways.
* Currently, ~70% of DB’s data is stored in SQL form.
* It’s paramount that we find a way to analyze this data without new users having SQL knowledge & understanding of the schema.
* As Digital Assistants are on a rise, we must find a way to parse our legacy datasets for them to understand.
* At the moment data for Digital Assistants must be kept in a specialized format that cannot be used in operation.

### Technology Stack
Client-side: React
Server-side: Python, flask
Database: PostgreSQL / MemSQL
Deployment: Google cloud Functions / AWS Lambda



## Project Idea 2: Text severity analysis for Ethical and Legal compliance 

Every organization has a ‘Legal Department’ which makes sure that the company is obeying all the legal laws and regulations. Nowadays, most companies include workplace ethics training so the employees get familiarised with the ethical stance of the company, including advice and instructions on reporting unethical behavior.
It's really important for an organization to 'listen' to their employees and the Legal Department of a ‘large’ organization receives hundreds of complaints every day. The process involves reading the complaints manually and assigning the severity of each complaint, so the HR department can take the action accordingly. Instead of manually reading the complaints, our solution(model) will classify each complaint based on severity (high, medium & low) priority using ‘Deep Learning - Natural Language Processing’ so that the legal department can quickly be alerted about ‘HIGH’ priority issues to take actions.

Example:
Input: Text
My coworker tried to bribe me - High severity
My coworker came drunk to work - High Severity
My coworker talked bad about me behind my back - Medium Severity 

Output:
High Priority Issue
Medium Priority Issue
Low Priority Issue

The solution uses seq2seq algorithm to build the model and after the trained model is ready we will deploy on the flask. 

### Technology Stack
Client-side: React
Server-side: Python, Flask
Deep Learning - Natural Language Processing (seq2seq algorithm)
Deployment: Google Cloud Functions / AWS Lambda



## Project Idea 3: Disease Spreading Prediction

### Abstract
This project is about using existing data about viruses or disease and how they spread to predict how future viruses will spread based on their starting location. Using the current infected people’s information like their location, travel history, information from social media, friends, and relatives we try to estimate the likely spread of the virus in its incubation period. This information can be used by the government to stop the virus from spreading further. 
We would depend on there being existing data, open for us to use on a machine learning model to train. We want to use that knowledge and convey it in a simple to use front-end that the people in the medical field can use. By providing this kind of application, we hope to speed up the process of containing and preventing the new diseases from spreading too far.

### Goal
Provide medical professionals with a tool to help predict and contain the spread of disease.

### Technology Stack
Client-Side: React
Python
* Machine Learning (sklearn)
