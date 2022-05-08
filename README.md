# Entity Gym

Entity Gym is an open source Python library that defines an _entity based_ API for reinforcement learning environments.
Entity Gym extends the standard paradigm of fixed-size observation spaces by allowing observations to contain dynamically-sized lists of entities.
This enables a seamless and highly efficient interface with simulators, games, and other complex environments whose state can be naturally expressed as a collection of entities.

The [ENN-PPO library](https://github.com/entity-neural-network/incubator/tree/main/enn_ppo) can be used to train agents for Entity Gym environments.

## Installation

```
pip install entity-gym
```

## Usage

- The [Quick Start Guide](tutorial.md) walks you through the process of implementing and running a simple grid-world environment.
- The [Advanced Tutorial](ADVANCED-TUTORIAL.md) goes into additional detail about environments in which the agent controls multiple entities.

## Examples

A number of simple example environments can be found in [entity_gym/examples](https://github.com/entity-neural-network/incubator/tree/main/entity_gym/entity_gym/examples). The [ENN-Zoo](https://github.com/entity-neural-network/incubator/tree/main/enn_zoo/enn_zoo) project implements Entity Gym bindings for [Procgen](https://github.com/openai/procgen), [Griddly](https://github.com/Bam4d/Griddly), [MicroRTS](https://github.com/santiontanon/microrts), [VizDoom](https://github.com/mwydmuch/ViZDoom), and [CodeCraft](https://github.com/cswinter/DeepCodeCraft).

## API Reference

TODO
