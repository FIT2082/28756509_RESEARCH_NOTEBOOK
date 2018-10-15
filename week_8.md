# Week 8

## Summary:
This week Dylan and I explored how by changing the weighting for each individual POS tags can impact the accuracy in determining the semantic similarity of sentences.

Currently the weighting for each word in a sentence is initialised with a 1.0 index. That means all words will have the same weighting when calculating the vector space average, which is not the most ideal way to extract semantic smilarity as the weighting of these POS tags can be manipulated to increase or decrease the impact of a certain word to the semantic similarity of a sentence.

I have created a simple for-loop Python script which intends to return the semantic similarity score each time 1 of the 37 POS tags changes in value, however due to set-up I was not able to get the script to work as the same accuracy score was returned for every iteration.

## Next week:
Continue exploring genetics and bruteforce approach in order to determine the most efficient way to achieve better semantic similarities.
