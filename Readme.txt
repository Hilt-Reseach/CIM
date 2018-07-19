This folder comprises of the work which has been carried out as a part of the resear for Computational Intelligence Magazine.

The Dataset folder comprises of the following files:

1) Followers_Clean.csv - The user id and their followers along with their relationships.
1) Followings_Clean.csv - The user id and their followings along with their relationships.

Example : robozear-----nirmsnanthgmai1,kathir_singaraj,SatheeshHritick,aravinth_4443,Shajansn,Diaz_Wellington,linoth001,hotcandy2-----NULL-----NULL-----nirmsnanthgmai2: NEIGHBOUR,om198:FACEBOOK FRIEND

In the example, robozear refers to the user, the names after the first delimiter (-----) correspond to the friends, the names after the second delimiter are the relatives, the names after the third delimiter are the colleagues, and finally we have the others category. For the others category the relationship with the user is mentioned explicitely after the colon (:).

To execute all the codes you need to extract the tweets of the users with the help of the crawler (which is available in the codes folder).

The codes folder comprises of most of the codes which are majorly used for the experimentation purpose.

The baseline code for community using CESNA which was used in the experiment is available in : https://github.com/snap-stanford/snap/tree/master/examples/cesna

Model (i) in the manuscript for link prediction can be done with the help of gephi api. 
 