# Code Repository Scaffold (recommended)

```
repo/
  README.md
  LICENSE
  CITATION.cff
  environment/
    conda.yml
    requirements.txt
    dockerfile
  data/
    README.md           # what data is needed and how to obtain it
    raw/                # NEVER commit sensitive data
    processed/
  src/
  notebooks/
  experiments/
    experiment_log.md   # links to Experiment_Log.xlsx IDs
  results/
    figures/
    tables/
  paper/
    main.tex (or docx)
    references.bib
```

**Rules**
- Never publish secrets or private data.
- Every published figure/table must be regenerable from code in the repo.
