# 1_Creating, Reading and Writing

>References
> - https://www.kaggle.com/code/residentmario/creating-reading-and-writing

## Definitions
- DataFrame: A table. It contains an array of individual entries. And each entry has a certain value.
  - ![DataFrame_sample]('./DataFrame_sample.JPG')
  - Entry: "0, No" entry's value is 131.

## Code
- Make a DataFrame
``` python
pd.DataFrame({
  'David': ['I love you', 'How about you?'],
  'Rucy': ['I love you too!', 'HaHaHa']
})
```
  - output: ![make_a_dataframe]('./make_a_dataframe.jpg')
