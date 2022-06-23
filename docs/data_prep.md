# Data Preparation stage

-convert my data into train and test.tsv in 70:30 ratio

```
data.xml
    |-train.tsv
    |-test.tsv
```
- We are choosing only three tags in the XML data -1. row ID, 2. title and body 3.Tags
(Stackoverflow tags specific to Python)

|Tags|features names|
|-|-|
|row Id|row ID|
|title and body|text|
|stackoverflow tags|Label - Python|