# Heading
### Subheading

---
Write your project description here.
- point1
- point2
- point3

Using star for bullet points:
* point1
* point2
* point3

def read_query(query):
    cursor.execute(query)
    rows=cursor.fetchall()
    df = pd.DataFrame(data=rows,columns=cursor.column_names)
    return df

***
