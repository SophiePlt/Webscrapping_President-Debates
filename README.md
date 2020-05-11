# Webscrapping_President-Debates
I scraped Presidential Debates from the Commission of Presidential Debates and created a Data Frame with some statistics.

First, I scraped the title of each link and use that as the column name in my Data Frame.
I counted how long the transcript of the debate is (as in the number of characters in transcription string).

Then, I counted how many times the word "war" was used in the different debates. To do so, I converted the text in a "smart" way; 
to not count the word warranty for example, but counting war., war!, war, or War etc.

I also scraped the most common used word in the debate, and wrote how many times it was used. 

