## What is EMMA?
While many AI models are trained to predict a single, definitive answer for each given query, in real life, we often encounter many situations where there are no black or white answers! We introduce, EMMA, a machine advisor that goes beyond such one-dimensional decison to uncover answers and belief structures in complex situations.


### How does EMMA work?

![Flow](figures/flow.pdf)

EMMA materializes the beliefs of the model for an input statement, uncovering different assumptions and perspectives. It then builds a network of beliefs, and that structure is critiqued using self-feedback (such as structural consistency, self-beliefs) and human feedback (such as thumbs down). Together with this critique, the network of beliefs is then improved using maxsat based reasoning to generate the most consistent belief network as output.

### Using EMMA (video)

Watch a 2 minutes short video for a demonstration of our system!


### Examples 