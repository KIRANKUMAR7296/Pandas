<p align=center><img src='Pandas.png' width=25%></p>

### Pandas vs SQL 

### 1. SELECT Columns

```SQL
SELECT Bill, Tip, Smoke, Meal
FROM Tips
LIMIT 5;
```

```Python
Tips[['Bill','Tip','Smoke','Meal']].head()
```

### 2. SELECT Columns and Calculate

```SQL
SELECT *, Tip / Bill as Rate
FROM Tips
LIMIT 5;
```

```Python
Tips.assign(Rate = Tips['Tip'] / Tips['Bill']).head()
```
