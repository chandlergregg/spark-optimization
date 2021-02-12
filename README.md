# spark-optimization

This repo walks through optimization of a Spark job. The job loads data from a Stack Overflow-like website that has questions and corresponding answers. The Spark job outputs the number of answers per question per month.

The project is part of the Springboard Data Engineering curriculum.

### Files:
- `data` folder:
  - Contains two folders, `questions` and `answers` with Parquet files that are read as input by the Spark job
- `optimize.py`: original Spark job to be optimized
- `spark_optimization.ipynb`: Jupyter notebook that walks through the optimization of the Spark job

### Running locally:

To run locally, it's easiest to run Spark in a virtual environment.

Instructions:
- [Mac](https://www.youtube.com/watch?v=MLXOy-OhWRY)
- Windows: [Here](https://www.youtube.com/watch?v=XvbEADU0IPU) and [here](https://www.youtube.com/watch?v=e_QoFQjZwqc)

Once your virtual environment is set up, simply open the Jupyter notebook and run each step.
