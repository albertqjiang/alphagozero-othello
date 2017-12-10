# alphagozero-othello
Play the game of Othello with methods used by AlphaGo Zero


# Prerequisite:
Standard Machine Learning Python libraries
MXNet/Gluon: installation here: [installation](https://mxnet.incubator.apache.org/get_started/install.html)

# How to use:
First execute mcts.py, change the code
```python
state = OthelloState(16)
```
in line 383, default is 16 * 16.
This will run the game of Othello with MCTS and record the states/probabilities. Change the code at the bottom to run it for multiple times.

Then execute the jupyter notebook mcts_result_formulation.ipynb to handle the records. By default this will only handle the result for the first game.

Execute ResNet_simplified.ipynb to run the simplified resnet on the results for 1000 iterations.