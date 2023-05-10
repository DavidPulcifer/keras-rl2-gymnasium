I was able to make a few changes to the core.py file of the original RL 2 library which allowed it to work with Gymnasium 0.28.1. Basically the output of reset() and step() no longer match the expected inputs of gymnasium, so it was only a few lines needing changes to get it to work.

Otherwise this is exactly the same as the archives Keras-rl2 library.

### NOTE: Requires tensorflow==2.1.0


## What is it?

`keras-rl2-gymnasium` adapts `keras-rl2` (https://github.com/tensorneko/keras-rl2) to the gymnasium library now maintained by the Farama Foundation (https://farama.org/).


## Installation

- Install from Github source:

```
git clone https://github.com/DavidPulcifer/keras-rl2-gymnasium.git
cd keras-rl2-gymnasium
python install .
```

