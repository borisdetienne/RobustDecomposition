File format for instances of Robust two-stage capital budgeting with loans problem

This problem is described in Arslan, A.N., Detienne, B., Decomposition-based approaches for a class of two-stage robust binary optimization problems, INFORMS Journal Of Computing, 2020 (http://www.optimization-online.org/DB_HTML/2019/07/7301.html)

Files are made of space/newline-separated numbers only (most easily read using C++ streams).

The first line contains general parameters:
NumberOfItems(N) Budget(B) FirstStageLoanAmount(C1) SecondStageLoanAmount(C2) FirstStageLoanCost(lambda) SecondStageLoanCost(lambda*mu) DiscountFactorForLateInvestment(f) DummyValue(Rho, only used for instance generation) NumberOfRiskFactors(M)

One line for each item i:
NominalProfit(\bar{p}_i) InvestmentCost(c_i) ImpactOfRiskFactor1(Q_{i,1}) ... ImpactOfRiskFactorM(Q_{i,M})

