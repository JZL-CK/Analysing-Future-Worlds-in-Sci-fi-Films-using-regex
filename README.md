# Analysing-Future-Worlds-in-Sci-fi-Films-using-regex

The project looks at the futuristic worlds portrayed in sci-fi films via their scripts using regular expressions and analyse the tone in their descriptions via sentiment analyses. 
Initially, movie scripts of 'sci-fi movies' genre was downloaded from studio binnder. 
Then a comprehensive list of terms that is associated with 'future world' was prepared - eg: AI, cybernetics, megacity, hologram etc. 
These terms were then used to extract descriptions in scripts (500 characters before and after the keywords) using regex. 
These sets of characters then underwent sentiment analysis extract positive, neutral and negative scores. 
Out of the 40 movie scripts analysed, 4 were neutral, 23 were negative, and 13 were positive, indicating a more sombre depiction of the future world in movies.

Further analyses- suggestions:

Scrape details of the movies involved and collect metadata including date of release, sub genre, etc. Then see if there are variations with respect to these variables. 
Conduct sentiment analyses on the whole script and see if there is a conflict with the scores on future worlds. 
