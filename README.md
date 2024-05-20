# Uncertainty-Quantification-for-Classification
RnD Project under Prof. Amit Sethi\\
Now a days, we all admit that we depend on AI models in
one way or the other but how can we be sure that the solution
AI model provides is correct or not, how much we can rely
on these models. One way to do so is measuring uncertainty
in the models’ predictions. For this we need to know the
sources of uncertainty, how we can measure it or estimate
it or quantify it. There are various methods of uncertainty
but those are scattered to their use cases, there is no one
such universal method for quantification of uncertainty but
some of the current methods are pretty much famous like
using Bayesian Neural Networks and Monte Carlo Dropout.
We conducted extensive literature survey to get to know all
these things. We also came across a paper ’Evidential Deep
Learning ’ which states that softmax is not a good option to
get predictions. So, we conducted experiments to validate this
and some different methods to quantify uncertainty without
being much computationally extensive. I used Dropout and
entropy to quantify uncertainty with resnet18 model and
MNIST and CIFAR10 dataset
