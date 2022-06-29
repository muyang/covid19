---
bibliography:["COVID-19文库.bib"]
---
# 1 项目框架
![avatar](/img/%E7%A0%94%E7%A9%B6%E6%A1%86%E6%9E%B6.png)

# 2 传播动力学模型
## 2.1 群体模型：SIRS
![avatar](/img/SIRS_beta.png)
$\frac{dS}{dt}=-\beta SI+ \gamma R$

$\frac{dI}{dt}=\beta SI - \mu I$

$\frac{dR}{dt}=\mu I - \gamma R$

### 2.1.1 Social contact
(1) location catagories
Home,Work,School,Others
$\beta_i=\Sigma (\alpha^{sc}(1-\rho_j)+\alpha^c\rho_j)\frac{I_j}{N_j}C^l_{ij}$ 
其中$(1-\rho_j)$ 对应asymptomatic group，$\rho_j$ 对应sub-clinical group

$C=\beta_hC^h+\beta_wC^w+\beta_wC^w+\beta_oC^o$
## 2.2 个体免疫应答模型

$\frac{dT}{dt}=d(T_0-T)-\frac{k}{A\alpha} VT$,       (1)

$\frac{dI}{dt}=\frac{k}{A\alpha} VT-\delta I$,       (2)

$\frac{dV}{dt}=pI-cV$,                               (3)



