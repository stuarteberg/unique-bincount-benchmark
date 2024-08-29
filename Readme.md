# Tiny benchmark for `unique()` and `bincount()`

Comparison of performance of `numpy`, `pandas`, and `vigra`.

## Contributing to this benchmark

Fork the repository, checkout a branch, create an environment, run the benchmark and open a PR to add your results.

## Create an environment

```
conda env create -n bench --file environment.yml
```

## Run the benchmark

```
conda activate bench
python bench-unique.py --hostname MyCoolComputer
```

This will add your results to the `results-unique.csv` table.

Please open a PR and contribute your results :)
