# camtrap-dp-query-test

Test querying different versions of the Camtrap DP model.

## Script

The [script](src/query.Rmd) aims to return the following result:

```
observationID,scientificName,minTimestamp,maxTimestamp,deploymentID
```

With a **single SQL query** for both image and sequence based data.

## Data

- [mediaGroupID](data/raw/mediaGroupID): both image and sequence based
- [parentMediaID](data/raw/parentMediaID): both image and sequence based
- [current model (v0.1.7)](data/raw/current)
