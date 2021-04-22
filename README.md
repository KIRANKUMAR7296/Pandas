<p align=center><img src='Pandas.png' width=25%></p>

<h1 align=center>Pandas vs SQL</h1>

### SELECT

```SQL
SELECT Bill, Tip, Smoke, Meal
FROM Tips
LIMIT 5;
```

```Python
Tips[['Bill','Tip','Smoke','Meal']].head()
```

