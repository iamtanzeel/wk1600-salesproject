# Heading
### Subheading

The dataset was taken from [Kaggle](https://www.kaggle.com/datasets/trainingdatapro/bald-women).

Thanks to WILLIAN OLIVEIRA GIBIN for the [dataset](https://www.kaggle.com/datasets/willianoliveiragibin/flying-commercial)
---
Write your project description here.
- point1
- point2
- point3

Using star for bullet points:
* point1
* point2
* point3
  
_The following code in [sql_query.py](https://github.com/iamtanzeel/wk1600-salesproject/blob/main/sql_query.py) file is for reading the query and converting the output to DataFrame_
```python
def read_query(query):
    cursor.execute(query)
    rows=cursor.fetchall()
    df = pd.DataFrame(data=rows,columns=cursor.column_names)
    return df
```


```mysql
SELECT * FROM salesdata;
```
***
![image](https://media.istockphoto.com/id/1314210006/photo/grocery-store-shop-in-vintage-style-with-fruit-and-vegetables-crates-on-the-street.jpg?s=612x612&w=0&k=20&c=UFL3bRQkWH7dt6EMLswvM4u8-1sPQU9T5IFHXuBbClU=)
![BestSubCategories](https://github.com/iamtanzeel/wk1600-salesproject/assets/125236453/5ae212d0-179b-4a86-9743-fe46256f93f0)


| column 1 | column 2|
|----------|---------|
| value 1 | value 2 |
| value 3 | value 4|

_Conflict resolved_
