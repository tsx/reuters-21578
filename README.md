# Reuters 21578 dataset

```reuters.json``` is a cleaned-up and converted to JSON Reuters 21578 dataset of classified categorized text.

This dataset is intended for machine learning purposes, especiall text classification tasks.

[Original dataset](https://archive.ics.uci.edu/ml/datasets/Reuters-21578+Text+Categorization+Collection) was distributed in SGML format and was not ready for direct consumption. I have cleaned it up and converted to JSON for super-easy loading.

# Example

```javascript
{
  "date" : "26-FEB-1987 15:17:11.20",
  "places" : [ "usa" ],
  "dateline" : "    ROCHESTER, N.Y., Feb 26 - ",
  "topics" : [ "earn" ],
  "cgisplit" : "TRAINING-SET",
  "id" : 9,
  "title" : "CHAMPION PRODUCTS <CH> APPROVES STOCK SPLIT",
  "body" : "Champion Products Inc said its\nboard of directors approved a two-for-one stock split of its\ncommon shares for shareholders of record as of April 1, 1987.\n    The company also said its board voted to recommend to\nshareholders at the annual meeting April 23 an increase in the\nauthorized capital stock from five mln to 25 mln shares.\n Reuter\n&#3;",
  "lewissplit" : "TRAIN"
}
```

# Licensing information

The copyright for the text of newswire articles and Reuters annotations in the Reuters-21578 collection resides with Reuters Ltd. Reuters Ltd. and Carnegie Group, Inc. have agreed to allow the free distribution of this data *for research purposes only*. 

If you publish results based on this data set, please acknowledge its use, refer to the data set by the name "Reuters-21578, Distribution 1.0", and inform your readers of the current location of the data set (see "Availability & Questions").
