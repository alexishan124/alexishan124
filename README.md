
<!--
**alexishan124/alexishan124** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

# Welcome!

As a junior studying Data Science and Cognitive Science at UC Berkeley, I am interested in the intersection between data, technology, and human cognition-- specifically, the fields of ethical human-computer interaction and artificial intelligence for the public good. Currently, I am working on polishing my data analysis skills using Python Numpy, Pandas, Matplotlib as well as SQL! 

A fun fact about me is that I spent all of my childhood in Russia :)

## Basic set-up of a script 
- REPO
  - directory of the same name
    - scripts (directory)
      - the_main_script.py
      - __init__.py
    - tests (directory)
      - test_the_main_script.py
      - __init__.py
    - data (directory)

## How do Webhooks work?
An HTTP callback, when triggered at an application/website, collects the relevant data and sends it over to the URL specified via the form of an HTTP request; then the predefined action is performed on that request. 

Fundamentally, API calls work on request-based output mechanisms while webhooks work on event-based output mechanisms. 

need: webhook service - accepts and returns JSON object

helpful for: 
- knowledge that a certain event has taken place
- ensure data is synced across multiple web applications
- customize responses
- connect 2+ apps so that one event triggers responses across multiple apps at the same time 

## How do DialogFlow Webhook Fulfillments work?
Fulfillments allow for more dynamic responses to intents that have been matched.
-> each intent has a setting to enable webhook fulfillment
-> when such an intent is matched, DialogFlow sends a request to your specified webhook service

the full overview:
1. The end-user types or speaks an expression.
2. DF matches the end-user expression to a certain intent and extracts according parameters.
3. DF sends a webhook request message to your webhook service. This message contains information about the matched intent, action, parameters, and the response defined for the intent. 
4. Your service performs actions as necessary i.e. database queries or external API calls
5. Your service sends a webhook request message to DF. This message contains the response that should be sent to the end-user.
6. DF sends the response to end-user.
7. The end-user sees or hears the response. 

## How to allow for multiple personas/responses for a single DialogFlow Agent using In-Line Editor
Fulfillments can be used with something like AWS lambda functions or with the in-line editor with webhooks to dynamically automate multiple responses/personas without having to create multiple DialogFlow Agents.

Specifically with in-line editors, you can write code in javascript to create specific functions to denote variations in response as well as keep a map of corresponding intent maps and specified functions.


# Things I have learned this semester :)

## Machine Learning Taxonomy
- labeled data
  - supervised learning
    - regression (quantitative responses)
      - linear regression
      - multiple linear regression
      - least squares regression
      - logistic regression
    - classification (categorical responses)
      - binary classification
      - multiclass classification
- unlabeled data
  - unsupervised learning
    - dimensionality reduction
      - Principal Components Analysis
    - clustering
      - K-means clustering
      - agglomerative clustering



