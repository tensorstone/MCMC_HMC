# MCMC_HMC
June.2017.Using HMC-P to accelerate MCMC of Ising Models

1.Why use Hopfield neural networks?
-----
  
  DHNN has the same energy function as Ising model. At very begining I was thinking about to use Bose-Einstein Condensation(BEC) and optical lattice technics in ultra-cold atom physics to simulate this network.(Because human can simulate Ising model in optical lattices)
  
2.Mathematical equility
------
![image](https://github.com/tensorstone/MCMC_HMC/blob/master/DHNN_MCMC.png)

Sothat the MCMC and HMC are equal in mathmatical perspective

3.What can HMC do
-----

### use MCMC
![image](https://github.com/tensorstone/MCMC_HMC/blob/master/MCMC.png)

### use HMC
![image](https://github.com/tensorstone/MCMC_HMC/blob/master/HMC.png)

### use HMC_Ponly
![image](https://github.com/tensorstone/MCMC_HMC/blob/master/HMC_Ponly.png)


4.What's wrong with Parallel HMC?
----

![image](https://github.com/tensorstone/MCMC_HMC/blob/master/HMC_P_likeanti.png)
![image](https://github.com/tensorstone/MCMC_HMC/blob/master/P_1.png)
![image](https://github.com/tensorstone/MCMC_HMC/blob/master/P_2.png)

5.How can Parallel HMC help us?
-----
![image](https://github.com/tensorstone/MCMC_HMC/blob/master/MCMC_HMC-P.png)
![image](https://github.com/tensorstone/MCMC_HMC/blob/master/contrast.png)

6.Error analysis
-----
### T=2.0
![image](https://github.com/tensorstone/MCMC_HMC/blob/master/T2.0.png)
### T=2.2
![image](https://github.com/tensorstone/MCMC_HMC/blob/master/T2.2.png)
### T=2.3
![image](https://github.com/tensorstone/MCMC_HMC/blob/master/T2.3.png)
### T=2.6
![image](https://github.com/tensorstone/MCMC_HMC/blob/master/T2.6.png)
### T=2.9
![image](https://github.com/tensorstone/MCMC_HMC/blob/master/T2.9.png)
### T=2.24
![image](https://github.com/tensorstone/MCMC_HMC/blob/master/T2.24.png)
### T=2.25
![image](https://github.com/tensorstone/MCMC_HMC/blob/master/T2.25.png)
### T=2.26
![image](https://github.com/tensorstone/MCMC_HMC/blob/master/T2.26.png)
### T=2.27
![image](https://github.com/tensorstone/MCMC_HMC/blob/master/T2.27.png)
### T=2.28
![image](https://github.com/tensorstone/MCMC_HMC/blob/master/T2.28.png)
### T=4.9
![image](https://github.com/tensorstone/MCMC_HMC/blob/master/T4.9.png)

7.TODOs
-----
Calculate the KL-Divergence, instead use MSE as the error estimator.

