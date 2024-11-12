# GST FAQ Bot 
Set of scripts to build a chatbot which will answer FAQ about Goods and Services Tax (GST) India.

## Scripts:
* app.py: Chatbot UI built using Flask, using templates/*.html
* engine.py: Chatbot core logic as well as knowledgebase.
* config.json: Rasa NLU settings for training as well as executing intent extraction
* run_training: Windows batch file to build trained modeling
* run_server: Windows batch file to execute Rasa-NLU server.

## Dependencies:
* Needs Python 3.5
