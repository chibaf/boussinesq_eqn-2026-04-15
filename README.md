# boussinesq_eqn-2026-04-15
boussinesq_eqn

gradient in the cylindrical coordinates  
$${\rm grad} \varphi = \frac{\partial \varphi}{\partial r}e_r+\frac{1}{r}\frac{\partial \varphi}{\partial \theta}e_\theta+\frac{\partial \varphi}{\partial z}e_z$$

laplacian in the cylindrical coordinates  
$$\Delta \varphi = \frac{1}{r}\frac{\partial}{\partial r}\left(r\frac{\partial \varphi}{\partial r}\right)+\frac{1}{r^2}\frac{\partial^2 \varphi}{\partial \theta^2}+\frac{\partial^2 \varphi}{\partial z^2}$$

a vector field X in the cylindrical coordinates 
$$X=(\xi,\eta,\zeta)=R e_r+\Theta e_\theta+Z e_z$$  
$$R=\xi\cos\theta+\eta\sin\theta,\Theta=-\xi\sin\theta+\eta\cos\theta,Z=\zeta$$

divergence in the cylindrical coordinates  
$${\rm div} X = \frac{1}{r}\frac{\partial}{\partial r}\left(r R\right)+\frac{1}{r}\frac{\partial \Theta}{\partial \theta}+\frac{\partial Z}{\partial z}$$

rotation in the cylindrical coordinates  
$${\rm rot} X = \left(\frac{1}{r}\frac{\partial Z}{\partial \theta}-\frac{\partial \Theta}{\partial z}\right)e_r+
\left(\frac{\partial R}{\partial z}-\frac{\partial Z}{\partial r}\right)e_\theta+
\left(\frac{1}{r}\frac{\partial}{\partial r}(r\Theta)-\frac{1}{r}\frac{\partial R}{\partial \theta}\right)e_z$$

Navier-Stokes equation: axisymmetric flow with the assumption of no tangential velocity  
$
\begin{eqnarray}
\begin{array}{cll}
\displaystyle \rho\left(\frac{\partial u_r}{\partial t}+u_r\frac{\partial u_r}{\partial r}+u_z\frac{\partial u_r}{\partial z}\right) &=& \displaystyle -\frac{\partial p}{\partial r}+\mu\left[\frac{1}{r}\frac{\partial}{\partial r}\left(r\frac{\partial u_r}{\partial r}\right)+\frac{\partial^2 u_r}{\partial z^2}-\frac{u_r}{r^2}\right]+\rho g_r \\
\displaystyle \rho\left(\frac{\partial u_z}{\partial t}+u_r\frac{\partial u_z}{\partial r}+u_z\frac{\partial u_z}{\partial z}\right) &=& \displaystyle -\frac{\partial p}{\partial z}+\mu\left[\frac{1}{r}\frac{\partial}{\partial r}\left(r\frac{\partial u_z}{\partial r}\right)+\frac{\partial^2 u_z}{\partial z^2}\right]+\rho g_z \\
\displaystyle \frac{1}{r}\frac{\partial}{\partial r}(r u_r)+\frac{\partial u_z}{\partial z}&=&0
\end{array} \nonumber
\end{eqnarray}
$

## ref
Coupling three equations for a homogenization problem with the Boussinesq approximation  
https://community.freefem.org/t/coupling-three-equations-for-a-homogenization-problem-with-the-boussinesq-approximation/3936
