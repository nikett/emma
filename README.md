## EMMA (*E*thics, *M*orality and beyond: a *M*achine *A*dvisor)

### What is EMMA?
While many AI models are trained to predict a single, definitive answer for each given query, in real life, we often encounter dilemmas and many situations where there are no black or white answers. We introduce, EMMA, a machine advisor that goes beyond such one-dimensional decisons and uncovers answers and perpectives incl. the underlying belief network of a model in complex situations.


### How does EMMA work?

![Flow](/figures/flow.png)

EMMA materializes the beliefs of the model for an input statement, uncovering different assumptions and perspectives. It then builds a network of beliefs, and that structure is critiqued using self-feedback (such as structural consistency, self-beliefs) and human feedback (such as thumbs down). Together with this critique, the network of beliefs is then improved using maxsat based reasoning to generate the most consistent belief network as output.

### Using EMMA (Demo video)

Watch a 2 minutes short video for a demonstration EMMA.
<iframe width="560" height="315" src="https://user-images.githubusercontent.com/53187122/182702175-834faabf-d4cf-441b-b52d-d1004ed1fa5e.mp4" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>




### Try out EMMA!
Click [`here`](https://allenai-defeasible-explanations-srcvdemo-interactive-jpe7t4.streamlitapp.com/?on_demand=false) to try out EMMA!
