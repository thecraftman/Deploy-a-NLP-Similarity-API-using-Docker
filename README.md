# RESTful API For Similarity Check Using Natural Language Processing

## INTRODUCTION

- Build a Similarity check API using NLP, run and deploy using Docker & Docker-compose. 

-----------------

### Documents similarity
Document similarity (or distance between documents) is a one of the central themes in Information Retrieval. How humans usually define how similar are documents? Usually documents treated as similar if they are semantically close and describe similar concepts. On other hand “similarity” can be used in context of duplicate detection. We will review several common approaches.

![imageSimilarity](https://miro.medium.com/max/1838/1*l-BZLW3JUHd1MZbNq1MjQA.png)

----------------------

#### OBJECTIVE

`The objective of this API is to handle Similarity of text (PLAGIARISM CHECK) `

## API ARCHITECTURE
|RESOURCES |URL(PATH) |METHOD |PARAMETERS |STATUSCODE|
|----------|-------|--------|--------------|----------|
|Register a user | /register | POST | username, password | 200:OK,  301:INVALID USERNAME |
|Detect Similarity of docs | /detect | POST | username, password , text1 & text2 |200:OK RETURN SIMILARITY ,   301:INVALID USERNAME,    302:INVALID PASSWORD,    303:OUT OF TOKENS
|Refill | /refill | POST | username,  admin_pw,  refill_amount |  200:OK,  301:INVALID USERNAME , 304:INVALID ADMIN_PW

------------------


## REQUIREMENTS

- [spacy.io](https://spacy.io/models/en) is  an open-source software library for advanced Natural Language Processing, written in the programming languages Python, it is very easy python processing module. 

**Download the spacy model from [here](https://github.com/explosion/spacy-models/releases//tag/en_core_web_sm-2.1.0)**

- Flask framework, see how to install and run the flask framework [here](https://github.com/pallets/flask) , for more [details](https://www.fullstackpython.com/flask.html)

- pymongo, PyMongo is a Python distribution containing tools for working with MongoDB download and install pymongo from [here](https://api.mongodb.com/python/current/)

- [Docker](https://www.docker.com/)

- Docker-compose.yml

-----------------------

## Contributing 

 Please feel free to fork this package and contribute by submitting a pull request to enhance the functionalities.
 
 -------------------

## How can I thank you?

Why not star the github repo? I'd love the attention! Why not share the link for this repository on Twitter, Hackernews or Destructoid ? Spread the word! 

Don't forget to [follow me on twitter](https://twitter.com/thecraftman_)

Thanks! Ore-Aruwaji Tola. 



