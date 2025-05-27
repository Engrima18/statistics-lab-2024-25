# statistics-lab-2024-25
Hands-on session on Python basics for Statistics for the course of Probability and Statistics for Engineering @ Sapienza (a.y. 2024/25)


## 📂 Repository structure


```bash
statistics-lab-2024-25/
│
├── images/
│
├── numpy/
│ ├── data/
│ ├── figures/
│ ├── 01-Introduction-to-numpy.ipynb
│ ├── 02-Understanding-types.ipynb
│ ├── 03-Basics-of-numpy-array.ipynb
│ ├── 04-Computation-on-numpy-arrays.ipynb
│ ├── 05-Computation-on-arrays-aggregates.ipynb
│ ├── 06-Computation-on-arrays-broadcasting.ipynb
│ ├── 07-Boolean-arrays-and-masks.ipynb
│ └── 08-Fancy-indexing.ipynb
│
├── statistics/
│ ├── data/
│ ├── 01-Exploratory-data-analysis.ipynb
│ ├── 02-Expectation.ipynb
│ ├── 03-Inequalities.ipynb
│ ├── 04-Estimating-the-CDF-and-statistical-functionals.ipynb
│ ├── 00-Examples-of-sampling-distributions.ipynb
│
├── main.py
├── pyproject.toml
└── README.md
```

## 📓 Notebooks

Below are the available Jupyter notebooks. Click the badge to launch each one directly in Google Colab.

### Numpy tutorial

1. **NumPy Intro** [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Engrima18/statistics-lab-2024-25/blob/main/numpy/01-numpy_basics.ipynb)

2. **Numpy Basics and Types** [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Engrima18/statistics-lab-2024-25/blob/main/numpy/02-Understanding-types.ipynb)

3. **Numpy Arrays** [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Engrima18/statistics-lab-2024-25/blob/main/numpy/03-Basics-of-numpy-array.ipynb)

4. **Computations with Arrays 1** [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Engrima18/statistics-lab-2024-25/blob/main/numpy/04-Computation-on-numpy-arrays.ipynb)

5. **Computations with Arrays 2** [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Engrima18/statistics-lab-2024-25/blob/main/numpy/05-Computation-on-arrays-aggregates.ipynb)

6. **Computations with Arrays 3** [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Engrima18/statistics-lab-2024-25/blob/main/numpy/06-Computation-on-arrays-broadcasting.ipynb)

7. **Masking Arrays** [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Engrima18/statistics-lab-2024-25/blob/main/numpy/07-Boolean-arrays-and-masks.ipynb)

8. **Arrays Indexing** [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Engrima18/statistics-lab-2024-25/blob/main/numpy/08-Fancy-indexing.ipynb)

### Python for Statistics tutorial

1. **Exploratory data analysis and visualization** [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Engrima18/statistics-lab-2024-25/blob/main/stats/01-Exploratory-data-analysis.ipynb)

2. **Expectation and sample mean distribution** [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Engrima18/statistics-lab-2024-25/blob/main/stats/02-Expectation.ipynb)

3. **Inequalities** [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Engrima18/statistics-lab-2024-25/blob/main/stats/03-Inequalities.ipynb)

4. **Empirical distribution and non-parametric inference** [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Engrima18/statistics-lab-2024-25/blob/main/stats/04-Estimating-the-CDF-and-statistical-functionals.ipynb)

5. **Sampling from distributions in python** [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Engrima18/statistics-lab-2024-25/blob/main/stats/00-Examples-of-sampling-distributions.ipynb)


---

## 🖥️ Instruction to locally run notebooks

If you want to locally run the lab notebooks, we recommend using uv package manager to easly handle all the project dependencies.

### 1. Clone this repository

Use git machine to clone the repository on your machine

```bash
git clone https://github.com/Engrima18/statistics-lab-2024-25
```

Then move in the cloned repository

```bash
cd statistics-lab-2024-25
```

### 2. Install uv

Using `uv` package manager is highly recommended, but you can equivalently opt for `pip`. [`uv`](https://github.com/astral-sh/uv) is a modern Python package manager that is significantly faster than `pip`. To install `uv`, follow the instructions from the [official installation guide](https://github.com/astral-sh/uv#installation).  

### 3. Set up the environment and install dependencies  

Run the following command in the repository root folder:  

```bash
uv sync
```

Now you are ready to open a notebook in your preferred editor and enjoy coding!

## ⚠️ Disclaimer

- The NumPy tutorials are adapted from Jake VanderPlas’s [Python Data Science Handbook](https://github.com/jakevdp/PythonDataScienceHandbook)
- The Computational Statistics tutorials and exercises are adapted the books [All of statistics](https://link.springer.com/book/10.1007/978-0-387-21736-9) by Larry Wassermann and [Practical Statistics for Data Scientists](https://github.com/gedeck/practical-statistics-for-data-scientists) by Peter C. Bruce, Andrew Bruce, Peter Gedeck
- Credits for the exercise solutions: [Telmo Correa](https://github.com/telmo-correa/all-of-statistics)

<table width='100%'>
<td><img src='images/pdsh.jpg' width=220></td>
  <td><img src='images/OReilly-english.jpg' width=220></td>
  <td><img src='images/aos.jpg' width=190></td>
</table>
