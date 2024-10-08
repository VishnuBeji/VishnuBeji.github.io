---
title: "Bayesian Network Structure Learning with Quantum Annealing"
collection: projects
type: "Independent Research"
permalink: /projects/DR
venue: "IIT madras"
date: 2019-11-01
location: "Chennai, India"
excerpt: "<img src='/images/Alarm.png' width='500'>"
---

## Introduction
In the paper [O'Gorman et al.](https://doi.org/10.1140/epjst/e2015-02349-9), we are introduced to the concept of Bayesian Network structure learning with  encoding into a **Quadratic Unconstrained Binary Optimisation** (**QUBO**) problem. 

This is an implementation of the same, with results upon ALARM dataset.


Quantum annealing is a method for finding the minimum value of a given objective function. It is the quantum analogue of classical simulated annealing,
where the computation is driven by quantum, rather than thermal fluctuations. We construct an instance of QUBO whose solution is the score-maximizing DAG; there is a simple transformation between a classically defined QUBO instance and a diagonal quantum 2-local Hamiltonian consisting of only Pauli Z and ZZ terms. 

## Problems Used
Patient monitoring system from ALARM dataset:

<img src='/images/Alarm.png'>

The **QUBO** problem is solved using **Quantum Annealing** approach using the libraries and **quantum annealers** provided by [D-Wave Systems](https://www.dwavesys.com/).



