Exploring Shared Robot Intention 

![LeafBlowing](https://learning-dynamic-manipulation.cs.princeton.edu/gifs/IMG_1082.gif "Leaf Blowing")
![LeafBlowingSIM](https://learning-dynamic-manipulation.cs.princeton.edu/gifs/blowing-large_door-mixed_shapes.gif "Leaf Blowing SIM")

Proposal:
Robots often lack a good way to model each other's future goals or actions without communications. Humans typically manage this through onverbal cues about each others actions. However, robots lack this abilitly. Prior work in robot teams created a small simulation where robots equiped with physics real lead blower collaberate to push leaves from across the enviroment into a desired location. Through introducing spatial intention maps in a related work, the robots were able to succesfully blow leaves from one side to another. Spatial intention maps are grid likelihood patches which indicate where the robot is most likely to go next. Prior work has shown these maps can help robots with variable tools to co-operate to succesfully work together. 

![SpatialIntention](https://spatial-intention-maps.cs.princeton.edu/gifs/lifting_4-small_empty-ours.gif "Spatial Intention")
![Pushing](https://spatial-intention-maps.cs.princeton.edu/gifs/pushing_4-small_divider-ours.gif "Pushing")

The goal of this project is to explore how shared spatial intention maps of robots can be used to promote better collaberations in complex tasks such as nonlinear dynamics. Leaf blowing provides an interesting oppurtunity to explore robot teams ability to work well under nonverbal communication due to the complexity of aerodynamics. Through using a team of 3-6 robots, the goal is to use a combination of learned intention maps for each robot to better understand how to pull leaves into a given area. If there is time, this project will work on training under disturbances (i.e. a gust of wind from afar) in order to push the limits of the system and see if the robots can adjust thier plans. Prior work in this area has been completed with an existing simulation in python that is easy to deploy and begin working with the project. This work can be found through the prior publication here: https://arxiv.org/pdf/2204.02390.pdf and through spatial intention maps here: https://arxiv.org/pdf/2103.12710v1.pdf

Goals:
Explore if shared spatial intention maps work on more complicated tasks
Train with disturbances to see if robots can work around failures such as removing a robot, external gust of wind, etc
Gain experience with RL and NN. Potentially explore alternative ways to learn robot plans and update them
