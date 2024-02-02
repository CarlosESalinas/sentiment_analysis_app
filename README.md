# Sentiment Analysis Web Application using Watson NLP Library

### Overview

This project involves developing and deploying an AI-based web application for sentiment analysis using the Watson NLP library. The application will be built using Flask framework, and the sentiment analysis will be performed using Watson's embeddable NLP library.

### Project Guidelines

To successfully complete this project, follow the tasks outlined below:

1. **Clone the Project Repository**
   - Repository URL: [https://github.com/ibm-developer-skills-network/zzrjt-practice-project-emb-ai.git](https://github.com/ibm-developer-skills-network/zzrjt-practice-project-emb-ai.git)

2. **Create a Sentiment Analysis Application using Watson NLP Library**
   - Use the pre-deployed Watson NLP library on the Cloud IDE server.
   - Use a sample code for the application, which involves sending a POST request to the relevant model with the required text.
   - Test the application using a Python shell.

3. **Format the Output of the Application**
   - Convert the text-based output into a dictionary using the `json` library.
   - Extract relevant information such as label and score from the formatted response.

4. **Package the Application**
   - Create a package named "SentimentAnalysis" with the application code.
   - Structure the package with the application module and an `__init__.py` file.

5. **Run Unit Tests on Your Application**
   - Create a new file, `test_sentiment_analysis.py`, to run unit tests on the sentiment analysis function.
   - Define unit tests for positive, negative, and neutral sentiments.

6. **Deploy as a Web Application using Flask**
   - Utilize provided files (`index.html`, `mywebscript.js`, and `server.py`) for deploying the application on the web.
   - Set up Flask app, import necessary libraries, and define functions to handle GET requests.

7. **Incorporate Error Handling**
   - Modify the `sentiment_analyzer()` function to handle invalid text entries.
   - Update the `sent_analyzer` function in `server.py` to print an appropriate message for invalid inputs.

8. **Run Static Code Analysis**
   - Install the PyLint library and use it to run static code analysis on `server.py`.
   - Ensure adherence to PEP8 guidelines.

The result is shown below:

