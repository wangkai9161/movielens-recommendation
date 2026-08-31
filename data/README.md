# Data

This project uses the MovieLens-1M dataset from GroupLens.

Download it from the official GroupLens page:

<https://grouplens.org/datasets/movielens/>

After downloading, extract the archive so that the files are available at:

```text
data/movielens/ml-1m/
|-- ratings.dat
|-- users.dat
`-- movies.dat
```

The raw dataset is intentionally excluded from Git because it is distributed
under the GroupLens dataset terms. The repository includes small sample files
inside the standalone recall and sequence demos for quick smoke tests.
