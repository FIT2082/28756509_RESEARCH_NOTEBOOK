# Week 9

## Summary:
In this week, I've fixed the issue of same semantic similarity accuracy score returned by wrapping the whole function with a for-loop. I have also changed the way the loop iterates by starting the loop with 1 initialised for all POS tags, and if the accuracy increases when the first POS tag's weighting is changed to 2.0, the second POS tag weighting is changed to 2.0 too and so on. This way by the end of the loop the finally accuracy score returned would be the best possible score with possible POS tag weighting being either 1.0 or 2.0. However this method does not take into account of all different combinations of 1.0s and 2.0s, and the fact only 1.0 and 2.0 is used really limits the results we are able to obtain.

## Next week:
Collect more surveys from people with little to none machine learning background on five topics: object, date/time, paint, event and news, in order to broaden the test sample and improve the response accuracy of Dave.
