# structuredproductrisk
Analysis of risks (underlying) in structured products
Financial structured products are sold to retail investor. Nevertheless the correletated risks like delta weighted underlying exposure are unknown to retail investor.
Idea is simple :
1) retail investor loads the factsheet (by law, a factsheet must be available publicly)
2) app analyse the risks :
     - display the exposure of e.g. stock (nomnal weighted by delta of option)
     - probability of 100 % repayment
     - probability of hitting the barrier
     - credit risk : either credit defaut swap (wors case bond spread to treasury)
3) app is runned localy (avoidimg any data issue)
4) although done in Python3, product will be be an exec file (focus on Mac)
