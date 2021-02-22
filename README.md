# AWSDeepRacer
What is AWS DeepRacer?
<img src="assets/overview.JPG" height="400em" width="800em"/>
It is way to try your the ML Model in HandsOn on building reinforcement learning models. .
Build your model, evaluate its performance on a virtual track, and then compete in the AWS DeepRacer League.

Traning:
AWS DeepRacer leverages Amazon SageMaker to train your model behind the scenes and uses AWS RoboMaker to simulate the agent's interaction with the environment. Watch how the agent behaves in the chosen environment, as prescribed by the reward function.

So i have tried with two sets FLASH1 is where i have trained the model for 60 minutes where it completes 3 Laps in 06:35.173.

<img src="assets/flash1.JPG" height="400em" width="400em"/>  <img src="assets/falsh1Time.gif" height="400em" width="400em"/>


Training configuration
Gradient descent batch size	64
Entropy	0.01
Discount factor	0.999
Loss type	Huber
Learning rate	0.0003
Number of experience episodes between each policy-updating iteration	20
Number of epochs	10
