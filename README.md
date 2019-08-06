# RESTFULAPI-FOR-SIMILARITYCHECK-USING-NATURAL-LANGUAGE-PROCESSING

## INTRODUCTION
### Documents similarity
Document similarity (or distance between documents) is a one of the central themes in Information Retrieval. How humans usually define how similar are documents? Usually documents treated as similar if they are semantically close and describe similar concepts. On other hand “similarity” can be used in context of duplicate detection. We will review several common approaches.

![imageSimilarity](https://miro.medium.com/max/1838/1*l-BZLW3JUHd1MZbNq1MjQA.png)


#### OBJECTIVE
The objective of this API is to handle Similarity of text (PLAGIARISM CHECK) 

## API ARCHITECTURE
|RESOURCES |URL(PATH) |METHOD |PARAMETERS |STATUSCODE|
|----------|-------|--------|--------------|----------|
|Register a user | /register | POST | username, password | 200:OK,  301:INVALID USERNAME |
|Detect Similarity of docs | /detect | POST | username, password , text1 & text2 |200:OK RETURN SIMILARITY ,              301:INVALID USERNAME, 302:INVALID PASSWORD, 303:OUT OF TOKENS


