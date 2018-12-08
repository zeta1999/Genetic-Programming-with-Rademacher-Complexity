# Genetic Programming for Symbolic Regression

### [benchmark_classic.py](https://github.com/Decadz/Genetic-Programming-for-Symbolic-Regression/blob/master/algorithms/benchmark/benchmark_classic.py) 
- A classic implementation of Genetic Programming for Symbolic Regression.
This program aims to map the input data to the output data through the use
of a symbolic representation (expression trees) and evolutionary techniques.

### [benchmark_pareto_parsimony.py](https://github.com/Decadz/Genetic-Programming-for-Symbolic-Regression/blob/master/algorithms/benchmark/benchmark_pareto_parsimony.py)
- A multi-objective (pareto) implementation of Genetic Programming for Symbolic
Regression. This program aims to optimise for both fitness and parsimony (size
of expression tree). This is used as a benchmark for parsimony pressure.

### [benchmark_diversity.py](https://github.com/Decadz/Genetic-Programming-for-Symbolic-Regression/blob/master/algorithms/benchmark/benchmark_diversity.py)
- A diversity maintaining implementation of Genetic Programming for Symbolic
Regression. This program aims to manage the diversity of individuals by using
a domination based selection scheme. "Multi-Objective Methods for Tree Size
Control" by Edwin D. de Jong, Jordan B. Pollack.

### [benchmark_spea2_parsimony.py](https://github.com/Decadz/Genetic-Programming-for-Symbolic-Regression/blob/master/algorithms/benchmark/benchmark_spea2_parsimony.py)
- A multi-objective implementation of Genetic Programming for Symbolic Regression.
This program uses the Strength Pareto Evolutionary Algorithm (SPEA2) selection.

---

### [experimental_diversity.py](https://github.com/Decadz/Genetic-Programming-for-Symbolic-Regression/blob/master/algorithms/experimental/experimental_diversity.py)
- A diversity maintaining implementation of Genetic Programming for Symbolic
Regression. This program aims to manage the diversity of individuals by using
a domination based selection scheme which penalises based on the order or
appearance and distance from the pareto frontier.

### [experimental_pareto_dimensionality.py](https://github.com/Decadz/Genetic-Programming-for-Symbolic-Regression/blob/master/algorithms/experimental/experimental_pareto_dimensionality.py)
- A multi-objective (pareto) implementation of Genetic Programming for Symbolic
Regression. This program aims to optimise for both fitness and the dimensionality
of the problem (number of distinct features present).

### [experimental_spea2_simplification.py](https://github.com/Decadz/Genetic-Programming-for-Symbolic-Regression/blob/master/algorithms/experimental/experimental_spea2_simplification.py)
- A multi-objective implementation of Genetic Programming for Symbolic Regression,
this program uses a modified version of the Strength Pareto Evolutionary Algorithm
(SPEA2) selection which simplifies the solutions in the archive.

### [experimental_pareto_parsimony_linearity.py](https://github.com/Decadz/Genetic-Programming-for-Symbolic-Regression/blob/master/algorithms/experimental/experimental_pareto_parsimony_linearity.py)
- A multi-objective (pareto) implementation of Genetic Programming for Symbolic
Regression. This program aims to optimise for: fitness and parsimony (size of
expression tree) and non-linearity.

### [experimental_rademacher_complexity.py](https://github.com/Decadz/Genetic-Programming-for-Symbolic-Regression/blob/master/algorithms/experimental/experimental_rademacher_complexity.py)
- An experimental version of Genetic Programming which uses Rademacher Complexity
to estimate the generalisation error. (Used as an alternative to VC dimensions).

---

### [config.py](https://github.com/Decadz/Genetic-Programming-for-Symbolic-Regression/blob/master/algorithms/config.py)