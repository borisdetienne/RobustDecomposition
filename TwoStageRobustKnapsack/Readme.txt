File format for instances of Robust two-stage knapsack problem

This problem is described in Arslan, A.N., Detienne, B., Decomposition-based approaches for a class of two-stage robust binary optimization problems, INFORMS Journal Of Computing, 2020 (http://www.optimization-online.org/DB_HTML/2019/07/7301.html)

Files are made of space/newline-separated numbers only (most easily read using C++ streams).

The first line contains general parameters:
NumberOfItems(I) Capacity(C) UncertaintyBudget(Gamma)

One line for each item i:
NominalProfit(\bar{p}_i) MaximumProfitDegradation(\hat{p}_i) RepairWeight(t_i) NormalWeight(c_i) OutsourcingCost(f_i)

