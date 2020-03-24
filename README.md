# ProjectGroup-16

Text severity analysis for Ethical and Legal compliance 
# Approved 
[Approval Comments]- Can you connect to box folder and scan all documents for this?

If yes, this will be an awesome project

Every organization has a ‘Legal Department’ which makes sure that the company is obeying all the legal laws and regulations. Nowadays, most companies include workplace ethics training so the employees get familiarised with the ethical stance of the company, including advice and instructions on reporting unethical behavior.
It's really important for an organization to 'listen' to their employees and the Legal Department of a ‘large’ organization receives hundreds of complaints every day. The process involves reading the complaints manually and assigning the severity of each complaint, so the HR department can take the action accordingly. Instead of manually reading the complaints, our solution(model) will classify each complaint based on severity (high, medium & low) priority using ‘Deep Learning - Natural Language Processing’ so that the legal department can quickly be alerted about ‘HIGH’ priority issues to take actions.

##### Example
###### Input: Text

* My coworker tried to bribe me - High severity
* My coworker came drunk to work - High Severity
* My coworker talked bad about me behind my back - Medium Severity 

###### Output

* High Priority Issue
* Medium Priority Issue
* Low Priority Issue

The solution uses seq2seq algorithm to build the model and after the trained model is ready we will deploy on the flask. 

### Technology Stack
* Client-side: React
* Server-side: Python, Flask
* Deep Learning - Natural Language Processing (seq2seq algorithm)
* Deployment: Google Cloud Functions / AWS Lambda
