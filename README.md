### Simple generic nextstrain build


Place your `sequences.fasta` and `metadata.tsv` in the directory `data` and run as
```
snakemake --cores 4
```


Input files can also be specified individually as
```
snakemake --cores 4 --config sequences=mysequences.fasta metadata=mymetadata.tsv
```

The output will be written to `auspice/tree.json` and can be viewed in [auspice.us](auspice.us).


