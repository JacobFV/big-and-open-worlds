# Big and Open Worlds

There are so many worlds to explore, and so many ways to explore them! This repository presents managed `gym.Env` interfaces for a hand-picked collection of environments as well as a suite of `hub.Dataset`'s that provide a starting point for training and evaluating anthropocentrically "general" artificial intelligence models. I.E.: you don't have to manually launch auxillary processes or provision `gcloud` or `docker` instances.

## Getting Started

Depending on your use case, run one the following commands:
```bash
$ pip install big-and-open-worlds  # no docker or gcloud support
$ pip install big-and-open-worlds[docker]  # docker support
$ pip install big-and-open-worlds[gcloud]  # gcloud support
$ pip install big-and-open-worlds[gcloud,docker]  # both docker and gcloud support
```

## Datasets

All datasets are provided as `hub.Dataset`'s. Some have been pre-pipelined for convenience. Get started with an dataset by importing it from the `datasets` submodule. Big and Open Worlds provides the following datasets:

### < Dataset >
< Description >
< Samples >
< data/tensor_spec >
< other details >
```python
< usage example >
```

### < Dataset >
< Description >
< Samples >
< data/tensor_spec >
< other details >
```python
< usage example >
```

## Environments

All environments are wrapped in [OpenAI Gym](https://gym.openai.com/) `Environment` objects. Environment wrappers provide defaults to manage their own backend processes if necessary. Get started with an environment by importing it from the `environments` sunmodule. Big and Open Worlds provides the following environments:

### TODO: Add environments

< Description >
< Samples >
< obs/act_spec >
< other details >
```python
< usage example >
```

### VNCEnv

< Description >
< Samples >
< obs/act_spec >
< other details >
```python
< usage example >
```

### Anymal and IsaacGym2

< Description >
< Samples >
< obs/act_spec >
< other details >
```python
< usage example >
```

### bsuite

< Description >
< Samples >
< obs/act_spec >
< other details >
```python
< usage example >
```

### control_suite

< Description >
< Samples >
< obs/act_spec >
< other details >
```python
< usage example >
```

### distraction_suite

< Description >
< Samples >
< obs/act_spec >
< other details >
```python
< usage example >
```

### psych_suite (?)

< Description >
< Samples >
< obs/act_spec >
< other details >
```python
< usage example >
```

### Crafter

< Description >
< Samples >
< obs/act_spec >
< other details >
```python
< usage example >
```

### MALMO (or maybe just MineRL)

< Description >
< Samples >
< obs/act_spec >
< other details >
```python
< usage example >
```

### NeuralMMO

< Description >
< Samples >
< obs/act_spec >
< other details >
```python
< usage example >
```

### BEHAVIOR

< Description >
< Samples >
< obs/act_spec >
< other details >
```python
< usage example >
```

### NetHack

> The NetHack Learning Environment (NLE) is a Reinforcement Learning environment presented at [NeurIPS 2020](https://neurips.cc/Conferences/2020).
> 
> NLE is based on [NetHack 3.6.6](https://github.com/NetHack/NetHack/tree/NetHack-3.6.6_PostRelease) and designed to provide a standard RL interface to the game, and comes with tasks that function as a first step to evaluate agents on this new environment.
> 
> NetHack is one of the oldest and arguably most impactful videogames in history, as well as being one of the hardest roguelikes currently being played by humans. It is procedurally generated, rich in entities and dynamics, and overall an extremely challenging environment for current state-of-the-art RL agents, while being much cheaper to run compared to other challenging testbeds. Through NLE, we wish to establish NetHack as one of the next challenges for research in decision making and machine learning.
> 
> You can read more about NLE in the [NeurIPS 2020 paper](https://arxiv.org/abs/2006.13760), and about NetHack in its [original README](./README.nh), at [nethack.org](https://nethack.org/), and on the [NetHack wiki](https://nethackwiki.com).
> 
> ![Example of an agent running on NLE](https://github.com/facebookresearch/nle/raw/main/dat/nle/example_run.gif)
> ([https://github.com/facebookresearch/nle](https://github.com/facebookresearch/nle))

< obs/act_spec >
< other details >
```python
< usage example >
```