R installed with conda seems not trivial to remove:

```
conda remove `conda list | grep '^r-' |  cut -f1 -d' '`
```
