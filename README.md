# AWSDeepRacer
What is AWS DeepRacer?
It is way to try your the ML Model in HandsOn on building reinforcement learning models. .
Build your model, evaluate its performance on a virtual track, and then compete in the AWS DeepRacer League.

Traning:
AWS DeepRacer leverages Amazon SageMaker to train your model behind the scenes and uses AWS RoboMaker to simulate the agent's interaction with the environment. Watch how the agent behaves in the chosen environment, as prescribed by the reward function.


Training configuration
Environment simulation
Empire City Training
Reward function
Show
Sensor(s)
Camera
Action space type
Discrete
Action space
Speed: { 0.33, 0.67, 1 } m/s
Steering angle: { -30, 0, 30 } °
Framework
Tensorflow
Reinforcement learning algorithm
PPO
Hyperparameter
Value
Gradient descent batch size	64
Entropy	0.01
Discount factor	0.999
Loss type	Huber
Learning rate	0.0003
Number of experience episodes between each policy-updating iteration	20
Number of epochs	10
