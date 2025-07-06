# CFD-with-LBM-in-Python
A simple 2D Lattice-Boltzmann (D2Q9) solver in Python, first around a circular cylinder and then using a real airfoil profile. 
Key functions: 
- main(): simulate flow past a cylinder
- load_airfoil_mask(): read any airfoil .dat and rasterize it into a boolean mask
- main_airfoil(): same LBM loop but with the airfoil obstacle
I used the code described in https://youtu.be/JFWqCQHg-Hs?si=jNCdTBn8eZoyBjE_ and adapted it for an airfoil profile (NACA 0012)
