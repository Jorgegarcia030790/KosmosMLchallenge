# KosmosMLchallenge
API REST sencilla que recibe una lista de oraciones en español y devuelva una lista de las entidades nombradas identificadas en cada oración.
Requerimientos: 
Flask,
Flask-Markdown,
Spacy.




To install the various packages we will be using pip as below

pip install flask Flask-Markdown spacy
To work with spacy you will need a particular language model for the natural language processing. You can download the english model with the code below.

python -m spacy download es_core_news_sm
