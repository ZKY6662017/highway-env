# Homework 5 highway-env


A collection of environments for *autonomous driving* and tactical decision-making tasks

<p align="center">
    <img src="https://raw.githubusercontent.com/eleurent/highway-env/master/../gh-media/docs/media/highway-env.gif?raw=true"><br/>
    <em>An episode of one of the environments available in highway-env.</em>
</p>

## [Try it on Google Colab! ![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](scripts)

## The environments

### Highway

```python
env = gym.make("highway-v0")
```

In this task, the ego-vehicle is driving on a multilane highway populated with other vehicles.
The agent's objective is to reach a high speed while avoiding collisions with neighbouring vehicles. Driving on the right side of the road is also rewarded.

<p align="center">
    <img src="https://raw.githubusercontent.com/eleurent/highway-env/master/../gh-media/docs/media/highway.gif?raw=true"><br/>
    <em>The highway-v0 environment.</em>
</p>

A faster variant, `highway-fast-v0` is also available, with a degraded simulation accuracy to improve speed for large-scale training.


