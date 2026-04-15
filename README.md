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
<img width="1664" height="340" alt="image" src="https://github.com/user-attachments/assets/b6952960-565b-4ad9-9e79-7447b0c57605" />

## ref
Coupling three equations for a homogenization problem with the Boussinesq approximation  
https://community.freefem.org/t/coupling-three-equations-for-a-homogenization-problem-with-the-boussinesq-approximation/3936
