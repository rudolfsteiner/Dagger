# Imitation Learning

Dependencies: TensorFlow, MuJoCo version 1.31, OpenAI Gym

**Note**: MuJoCo versions until 1.5 do not support NVMe disks therefore won't be compatible with recent Mac machines.
There is a request for OpenAI to support it that can be followed [here](https://github.com/openai/gym/issues/638).

`run_expert.ipynb`, which is code to load up an expert policy, run a specified number of roll-outs, and save out data.
'run_clone.ipynb', which is code to use a neural network to imitate the expery policy
'run_dagger.ipynb', which is code to use the behavior cloning and dataset aggregation to better imitate the expery policy

In `experts/`, the provided expert policies are:
* Ant-v1.pkl
* HalfCheetah-v1.pkl
* Hopper-v1.pkl
* Humanoid-v1.pkl
* Reacher-v1.pkl
* Walker2d-v1.pkl

The name of the pickle file corresponds to the name of the gym environment.
