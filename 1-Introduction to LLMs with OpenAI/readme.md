In this first section of the course, we will learn to work with the OpenAI API by creating two small projects. We'll delve into OpenAI's roles and how to provide the necessary instructions to the model through the prompt to make it behave as we desire.

The first project is a restaurant chatbot where the model will take customer orders. Building upon this project, we will construct an SQL statement generator. Here, we'll attempt to create a secure prompt that only accepts SQL creation commands and nothing else.
### Create Your First Chatbot Using GPT 3.5, OpenAI, Python and Panel.
We will be utilizing OpenAI GPT-3.5 and Panel to develop a straightforward Chatbot tailored for a fast food restaurant. During the course, we will explore the fundamentals of prompt engineering, including understanding the various OpenAI roles, manipulating temperature settings, and how to avoid Prompt Injections. 
* Article: https://medium.com/towards-artificial-intelligence/create-your-first-chatbot-using-gpt-3-5-openai-python-and-panel-7ec180b9d7f2
* Notebook: https://github.com/peremartra/Large-Language-Model-Notebooks-Course/blob/main/1-Introduction%20to%20LLMs%20with%20OpenAI/Vertical%20Chat.ipynb

### How to Create a Natural Language to SQL Translator Using OpenAI API.
Following the same framework utilized in the previous article to create the ChatBot, we made a few modifications to develop a Natural Language to SQL translator. In this case, the Model needs to be provided with the table structures, and adjustments were made to the prompt to ensure smooth functionality and avoid any potential malfunctions.

With these modifications in place, the translator is capable of converting natural language queries into SQL queries. 
* Article: https://pub.towardsai.net/how-to-create-a-natural-language-to-sql-translator-using-openai-api-e1b1f72ac35a
* Notebook: https://github.com/peremartra/Large-Language-Model-Notebooks-Course/blob/main/1-Introduction%20to%20LLMs%20with%20OpenAI/nl2sql.ipynb
