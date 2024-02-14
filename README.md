# Particle swarm optimization with modification
This work embodies implementation of particle swarm algorithm for optimization (PSO) of the function $(y-x^2)^2+(1-x)^2$. When running the program you can tune all the hyperparameters, 
including population size, number of generations, inertia weight, congnitive and social coefficients.
### A little modification
Also, to improve the operation of the algorithm, a modification of the algorithm was carried out. This modification adds dynamic inertial weight and damping factor to the speed upgrade. The new velocity is calculated as a weighted sum of inertial, cognitive and social coefficients, where the social and cognitive coefficients are terms of the velocity equation with a multiplier of the influence of the best point for all individuals on speed and a multiplier of the influence of the best point of an individual on speed, respectively. To reduce the influence of these coefficients, a damping coefficient equal to 0.5 was introduced. This damping factor can help control the effect of each value on the speed update.
### Results 
The modification gave an increase in the convergence rate by almost 20%.
### Example:
<p align="center">
<img width="469" alt="Снимок экрана 2024-02-14 в 12 39 02 PM" src="https://github.com/sastsy/pso-ai/assets/53853716/d8956ec2-3196-4433-aa67-8c3e3ed01aa7"><br>
<img width="469" alt="Снимок экрана 2024-02-14 в 12 39 22 PM" src="https://github.com/sastsy/pso-ai/assets/53853716/f51e6b54-38a1-4e8b-ac44-9191cb926200">
</p>
