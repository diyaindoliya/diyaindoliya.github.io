<link rel="shortcut icon" type="image/x-icon" href="favicon.ico">

# currently...
![Illustration of robot demo](/assets/clutter_demo.png)

### Task-Informed Robotic Manipulation ~ _Improbable AI Group (MIT CSAIL)_
    
I'm collaborating with Anthony Simeonov to explore robotic manipulation of novel, cluttered objects conditioned on manipulation task. In the way that you wouldn't grab a mug by its rim if you wanted to flip it upside down, we want to generate grasps that depend on what the robot intends to do with an object.
    
Current questions: Can we take task/motion planning into account when generating grasps? What are ways to allow for subgoal search given an ultimate goal and potentially unfavorable initial object configurations?
    
Using: PyTorch, ROS, PointNet++ architecture, GraspNet architecture, CVAEs, Docker, PyBullet, RViz

<img src='assets/hsa_screencap.jpg' alt='Screenshot of HSA' width='300'>
