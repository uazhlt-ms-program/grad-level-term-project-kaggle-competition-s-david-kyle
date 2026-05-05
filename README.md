# How to Run

## Build the Docker container

```bash
docker build -t ling539 .
```

## Run the Jupyter notebook

```bash
docker run -p 8888:9999 -v $(pwd):/app ling539
```

Then open your browser to `http://127.0.0.1:8888` and open `Kaggle_competition.ipynb`.

## Run all cells

Run all cells in order. The final cell will generate `submission.csv`.
