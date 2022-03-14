# most-used-words-stackoverflow

The package was designed to extract the most common words from posts on StackOverflow.

The data was received on March 14 for the previous six months from [StackOverflow Query](https://data.stackexchange.com/stackoverflow/query/new).


The query:
```
SELECT Body
FROM Posts
WHERE CreationDate >= DATEADD(Month, -6, CURRENT_TIMESTAMP)
```

