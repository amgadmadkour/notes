# Learning Rate

The learning rate is a [hyperparameter](../concept/hyperparameter.md) that controls the *step size* at which the model’s parameters are updated during training. It determines how much to change the model in response to the estimated error each time the model weights are updated.

- **High Learning Rate:** The model might converge too quickly to a suboptimal solution or even diverge, failing to find a good solution.
- **Low Learning Rate:** The training process will be very slow, and it might get stuck in a local minimum.
