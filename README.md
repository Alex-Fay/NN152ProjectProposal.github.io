# Exploring Shared Robot Intention 

![LeafBlowing](https://learning-dynamic-manipulation.cs.princeton.edu/gifs/IMG_1082.gif "Leaf Blowing")

## Proposal:
Robots often lack a good way to model each other's future goals or actions without communication. Humans typically manage this through nonverbal cues and guessing each other's intentions. Prior work in robot teams created a small simulation where robots equipped with different tools and abilities were able to succesfully collaborate together through spatial intention maps. These maps are grid likelihood patches which indicate where the robot is most likely to go next. Similar work by the same authors created a physics-real leaf blower and trained the robot to successfully blow leaves into a designated area. 

![SpatialIntention](https://spatial-intention-maps.cs.princeton.edu/gifs/lifting_4-small_empty-ours.gif "Spatial Intention")
![Pushing](https://spatial-intention-maps.cs.princeton.edu/gifs/pushing_4-small_divider-ours.gif "Pushing")

The goal of this project is to explore how shared spatial intention maps of robots can be used to promote better collaborations in complex tasks such as nonlinear dynamics. Leaf blowing provides an interesting opportunity to explore robot teams ability to work well under nonverbal communication due to the complexity of aerodynamics. Through using a team of 3-6 robots, the goal is to use a combination of learned intention maps for each robot to better understand how to pull leaves into a given area. If there is time, this project will work on training under disturbances (i.e. a gust of wind from afar) in order to push the limits of the system and see if the robots can adjust thier plans. Prior work in this area has been completed with an existing simulation in Python that is easy to deploy. This work can be found through the prior publication here: https://arxiv.org/pdf/2204.02390.pdf and through spatial intention maps here: https://arxiv.org/pdf/2103.12710v1.pdf

## Goals:

- Explore if shared spatial intention maps work on more complicated tasks (leaf blowing)
- Train with disturbances to see if robots can work around failures such as removing a robot, external gust of wind, etc
- Gain experience with RL and NN. Potentially explore alternative ways to learn robot plans and update them

![LeafBlowingSIM](https://learning-dynamic-manipulation.cs.princeton.edu/gifs/blowing-large_door-mixed_shapes.gif "Leaf Blowing SIM")
