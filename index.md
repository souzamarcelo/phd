---
layout: template
title: Marcelo's PhD
---

# Automatic Algorithm Configuration: Methods and Applications

Hi, this is [Marcelo de Souza](https://souzamarcelo.github.io){:target="_blank"}! This page presents links to the artifacts arising from my PhD research. Here I enumerate the scientific publications, talks and presentations in workshops, doctoral consortia and Ph.D. schools, software implementations of the proposed methods, and supplementary data for most of our experiments.

First of all, please check my [PhD dissertation (PDF)](https://lume.ufrgs.br/handle/10183/236350){:target="_blank"}.

***

## Abstract

The performance of algorithms is often highly sensitive to the values of their parameters. Therefore, algorithm configuration plays a pivotal role when designing or adapting algorithms for a given problem domain. *Automatic algorithm configuration* methods automate this process, reducing human effort and potential biases involved in error-prone manual configuration approaches. A more general and ambitious research field, called *automatic algorithm design*, applies automatic configuration methods to select, combine and calibrate algorithm components, producing high-quality algorithms automatically for different problem domains. Despite the growing attention and substantial progress made in the last years, there are still open research directions on understanding, improving and exploring methods for the automatic design and configuration of algorithms.

We present a comprehensive study on automatic algorithm configuration with the following contributions. First, we improve the efficiency of the automatic configuration of optimization algorithms. In particular, we propose a set of capping methods that
use previous executions to build a performance envelope, which is used to identify poor-performing executions and stop them early. These methods considerably reduce the configuration time without loss of quality. Second, we improve the quality of automatic algorithm configuration by exploring parameter regression models. Instead of searching for parameter values, we calibrate models that set these values according to the instance size of the instance being solved, leading to expressive gains in algorithm performance when compared to using fixed configurations. Third, we provide a visualization tool to analyze and understand the automatic algorithm configuration process. The visualizations allow to identify different types of flaws and improve configuration scenarios. Finally, we propose a component-wise heuristic solver for a general class of binary optimization problems. This solver implements a set of heuristic components that can be selected and combined to produce complete algorithms. Given a problem, automatic configuration methods explore this design space and search for the best heuristic algorithm. We automatically produce new
state-of-the-art algorithms for different binary problems using this solver.

**Keywords:** Automatic algorithm configuration. Automatic algorithm design. Parameter tuning. Capping methods. Parameter regression models. Unconstrained binary quadratic programming.

***

## Publications

1. <u>Marcelo de Souza</u>, Marcus Ritt and Manuel López-Ibáñez. **Capping methods for the automatic configuration of optimization algorithms**. Computers & Operations Research, v. 139, p. 1–15, 2022. [DOI: [10.1016/j.cor.2021.105615](https://doi.org/10.1016/j.cor.2021.105615){:target="_blank"}]<br><br>

2. <u>Marcelo de Souza</u> and Marcus Ritt. **Improved regression models for algorithm configuration**. The Genetic and Evolutionary Computation Conference (GECCO), 2022. [DOI: available soon]<br><br>

3. <u>Marcelo de Souza</u>, Marcus Ritt, Manuel López-Ibáñez and Leslie Pérez Cáceres. **ACVIZ: A tool for the visual analysis of the configuration of algorithms with irace**. Operations Research Perspectives, v. 8, p. 1–9, 2021. [DOI: [10.1016/j.orp.2021.100186](https://doi.org/10.1016/j.orp.2021.100186){:target="_blank"}]<br><br>

4. <u>Marcelo de Souza</u> and Marcus Ritt. **A study of the automatic design of heuristics for binary quadratic programming**. XLVIII Brazilian Symposium on Operational Research (SBPO), p. 1673–1684, 2016.<br><br>

5. <u>Marcelo de Souza</u> and Marcus Ritt. **Automatic grammar-based design of heuristic algorithms for unconstrained binary quadratic programming**. 18th European Conference on Evolutionary Computation in Combinatorial Optimization (EvoCOP), p. 67–84, 2018. [DOI: [10.1007/978-3-319-77449-7_5](https://doi.org/10.1007/978-3-319-77449-7_5){:target="_blank"}]<br><br>

6. <u>Marcelo de Souza</u> and Marcus Ritt. **An automatically designed recombination heuristic for the test-assignment problem**. 2018 IEEE Congress on Evolutionary Computation (CEC), p. 2411–2418, 2018. [DOI: [10.1109/CEC.2018.8477801](https://doi.org/10.1109/CEC.2018.8477801){:target="_blank"}]<br><br>

***

## Talks and Presentations

1. <u>Marcelo de Souza</u> and Marcus Ritt. **Capping strategies based on performance envelopes for the automatic design of meta-heuristics**. XXIII Latin-American Summer School in Operational Research (ELAVIO), 2019.<br><br>

2. <u>Marcelo de Souza</u> and Marcus Ritt. **Capping strategies based on performance envelopes for the automatic design of meta-heuristics**. Configuration and Selection of Algorithms Workshop (COSEAL), 2019.<br><br>

3. <u>Marcelo de Souza</u>. **On the automatic configuration of algorithms**. 1st Doctoral Consortium at the European Conference on Artificial Intelligence (DC-ECAI), p. 15–16, 2020.<br><br>

4. <u>Marcelo de Souza</u>. **How to speed-up the automated configuration of optimization algorithms**. Doctoral Consortium of the 14th Annual Symposium on Combinatorial Search (SoCS), AAAI, 2021.<br><br>

5. <u>Marcelo de Souza</u>. **Automatic design of heuristic algorithms for binary optimization problems**. Doctoral Consortium of the 30th International Joint Conference on Artificial Intelligence (IJCAI), 2021. [DOI: [10.24963/ijcai.2021/672](https://doi.org/10.24963/ijcai.2021/672){:target="_blank"}]<br><br>

6. Leslie Pérez Cáceres, <u>Marcelo de Souza</u>, Manuel López-Ibáñez and Marcus Ritt. **Evaluation of random forest importance measures for algorithm configuration**. Configuration and Selection of Algorithms Workshop (COSEAL), 2021.<br><br>

***

## Software

1. <u>Marcelo de Souza</u>, Marcus Ritt and Manuel López-Ibáñez. **[CAPOPT: Capping methods for the automatic configuration of optimization algorithms -- source code](https://github.com/souzamarcelo/capopt){:target="_blank"}**, 2020.<br><br>

2. <u>Marcelo de Souza</u> and Marcus Ritt. **[Improved regression models for algorithm configuration -- source code](https://github.com/souzamarcelo/regression-models-ac){:target="_blank"}**, 2022.<br><br>

3. <u>Marcelo de Souza</u> and Marcus Ritt. **[ILSBQP: A simple iterated local search for unconstrained binary quadratic programming -- source code](https://github.com/souzamarcelo/ilsbqp){:target="_blank"}**, 2022.<br><br>

4. <u>Marcelo de Souza</u>, Marcus Ritt, Manuel López-Ibáñez and Leslie Pérez Cáceres. **[ACVIZ: A tool for the visual analysis of the configuration of algorithms with irace -- source code](https://github.com/souzamarcelo/acviz){:target="_blank"}**, 2020.<br><br>

5. <u>Marcelo de Souza</u> and Marcus Ritt. **[AutoBQP: A component-wise solver to binary optimization -- source code](https://github.com/souzamarcelo/autobqp){:target="_blank"}**, 2018.<br><br>

6. <u>Marcelo de Souza</u> and Marcus Ritt. **[HHPAL: Hybrid heuristic for unconstrained binary quadratic programming trained on Palubeckis’ instances -- source code](https://github.com/souzamarcelo/hhpal){:target="_blank"}**, 2018.<br><br>

7. <u>Marcelo de Souza</u> and Marcus Ritt. **[HHMC: Hybrid heuristic for the maximum cut on graphs -- source code](https://github.com/souzamarcelo/hhmc){:target="_blank"}**, 2018.<br><br>

8. <u>Marcelo de Souza</u> and Marcus Ritt. **[HHBQP: Hybrid heuristic for unconstrained binary quadratic programming -- source code](https://github.com/souzamarcelo/hhbqp){:target="_blank"}**, 2018.<br><br>

9. <u>Marcelo de Souza</u> and Marcus Ritt. **[HHTA: Hybrid heuristics for the test-assignment problem -- source code](https://github.com/souzamarcelo/hhta){:target="_blank"}**, 2018.<br><br>

***

## Supplementary Material

In the following links, I provide the source code of the tested algorithms, all data, instructions and scripts to reproduce the experiments, and additional details for the results. I also provide all files for the configuration scenarios we used throughout this thesis, including algorithm implementations, execution scripts, problem instances, parameter descriptions and the  configurator setup.

1. <u>Marcelo de Souza</u>, Marcus Ritt and Manuel López-Ibáñez. **[Capping methods for the automatic configuration of optimization algorithms -- supplementary material](https://github.com/souzamarcelo/supp-cor-capopt){:target="_blank"}**, 2021.<br><br>

2. <u>Marcelo de Souza</u> and Marcus Ritt. **[Improved regression models for algorithm configuration -- supplementary material](https://github.com/souzamarcelo/supp-models-ac){:target="_blank"}**, 2022.<br><br>

3. <u>Marcelo de Souza</u>, Marcus Ritt, Manuel López-Ibáñez and Leslie Pérez Cáceres. **[ACVIZ: Algorithm configuration visualizations for irace -- supplementary material](https://doi.org/10.5281/zenodo.4028904){:target="_blank"}**, Zenodo, 2020.<br><br>

4. <u>Marcelo de Souza</u> and Marcus Ritt. **[Algorithm configuration scenarios](https://github.com/souzamarcelo/ac-scenarios){:target="_blank"}**, 2022.

<br><br>