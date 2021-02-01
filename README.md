# franka_panda_desctiption

Forked from [justagist repo](https://github.com/justagist/franka_panda_description).

## My changes

1) **Visual meshes**: I've changed the visual mesh files to make compatible with gazebo rendering. I've removed the handmade color definitions (e.g., `<material name="panda_white"/>` and `<material>Gazebo/White</material>`).

![](https://raw.githubusercontent.com/qgallouedec/franka_panda_description/master/assets/panda.jpeg)

2) **Collision meshes**: I've changed the collision mesh files to make the collision spaces more relevant while keeping them simple. Mesh files are from [AndrejOrsula](https://github.com/AndrejOrsula/panda_ign).

![](https://raw.githubusercontent.com/qgallouedec/franka_panda_description/master/assets/collision.jpeg)

3) **Inertial**: I've corrected the intertial values (using values from [mkrizmancic's repo](https://github.com/mkrizmancic/franka_gazebo)), making them more accurate. 

 ![](https://raw.githubusercontent.com/qgallouedec/franka_panda_description/master/assets/inertia.jpeg)
