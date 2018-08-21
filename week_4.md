# Week 4

## Summary:
Project proposal was finalised and submitted on Friday. Dylan and I then met up on Saturday and we experienmented with two possible libraries for vector space modelling, Gensim and fastText.

### Gensim
We got Gensim up and working with a Python virtual environment. 15 example sentences were written as a sample corpus containing 5 areas of topic, 3 sentences each. These sentences had their stop words removed in order to decrease the interference with analysing the input sentence. The input sentence is then ranked against the 15 example sentences to determine the intent. The analysis was fairly accurate with room for improvement.

### fastText
Same example sentences were also used on fastText however pre-processing of these sentences was required. Words are converted into lower-cases and a space is inserted before puntuations to ensure all words are recognisable by fastText. Overall fastText did a very good job on determining the topic of the input sentence based on the example sentences provided.

## Next week:
Continue exploring Gensim, fastText and some other libraries which we could potentially use to achieve semantic understanding. I'll also look into speech-to-text services to hopefully implement onto Dave in the coming weeks.
