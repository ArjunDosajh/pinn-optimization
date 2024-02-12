# Solving real-world optimization tasks using physics-informed neural computing

### Paper link: https://www.nature.com/articles/s41598-023-49977-3

This paper provides 3 examples of using PINNs to solve real-world optimization tasks. The examples are:
1. Swinging up a pendulum
2. Determining the shortest-time path connecting two given points
3. Finding a swingby trajectory of a spacecraft

I have implemented a fourth example: `Inverting pendulum attached to cart`

The code is avalailible at [data/inverting_pendulum/inverted_pendulum_cart.ipynb](https://github.com/ArjunDosajh/pinn-optimization/blob/main/data/inverting_pendulum/inverted_pendulum_cart.ipynb)
All the data required for training the model is generated within the notebook itself.

The resource used for the dynamical equations of the system is: [Dynamics of inverted pendulum on a cart](https://ctms.engin.umich.edu/CTMS/index.php?example=InvertedPendulum&section=SystemModeling)

More information about the problem and the model is given in the images below:

<img src="Readme Assets/model_information_1.jpg" />
<img src="Readme Assets/model_information_2.jpg" />