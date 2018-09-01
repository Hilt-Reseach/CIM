This folder comprises of the work which has been carried out as a part of the research for Computational Intelligence Magazine.

The Dataset folder comprises of the following files:

1) Followers_Clean.csv - The user id and their followers along with their relationships with the delimiter as -----
1) Followings_Clean.csv - The user id and their followings along with their relationships with the delimiter as -----

Example : robozear-----nirmsnanthgmai1,kathir_singaraj,SatheeshHritick,aravinth_4443,Shajansn,Diaz_Wellington,linoth001,hotcandy2-----NULL-----NULL-----nirmsnanthgmai2: NEIGHBOUR,om198:FACEBOOK FRIEND

In the example, robozear refers to the user, the names after the first delimiter (-----) correspond to the friends, the names after the second delimiter are the relatives, the names after the third delimiter are the colleagues, and finally we have the others category. For the others category the relationship with the user is mentioned explicitely after the colon (:).

To execute all the codes you need to extract the tweets of the users with the help of the crawler (which is available in the codes folder).

The codes folder comprises of most of the codes which are majorly used for the experimentation purpose.

HOMOPHILY ANALYSIS

This folder comprises of various classifiers that has been used as a part of this work - age, gender, personality, values and the codes are in the respective folders named after the classifiers.

The Twitter Data Crawler has been developed using Twitter4j (http://twitter4j.org/en/). The API keys has been removed for security reasons. Place your own security keys and tokens. Filename: Extract_Twitter_Data.java

COMMUNITY DETECTION

Python 2 has been used for community detection

The baseline code for community using CESNA which was used in the experiment is available in : https://github.com/snap-stanford/snap/tree/master/examples/cesna 

Filename: F1_communities.py

LINK PREDICTION

Model (ii) in the manuscript for link prediction can be done with the help of gephi api (https://gephi.org/
). Download the tool from http://linkpredictiontool.blogspot.com/2016/11/link-prediction-tool-10.html and add it to gephi so that you get a wide variety of operations which can be helpful in performing link prediction through gephi. 
 
Model (i) from the manuscript has been the implementation of Node2Vec Algorithm by Aditya-Grover (https://github.com/aditya-grover/node2vec). Filename: n2v.py NOTE: Comment the code which includes the node properties

Model (iii) is an extended version of the baseline Node2Vec model. Filename: n2v.py NOTE: Uncomment the code which includes the node properties
