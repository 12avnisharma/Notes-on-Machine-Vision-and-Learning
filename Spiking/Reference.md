1. [Introduction to spiking neural networks: 
information processing, learning and applications](http://www.ane.pl/pdf/7146.pdf)

2. [Image Processing with Spiking Neuron
Networks](https://lezoray.users.greyc.fr/Publis/Meftah_Turing2012.pdf) 

Wolfgang Maass delineates past and current artificial neural network research
into three generations and makes the following observations.
The first generation is based on the McCulloch-Pitts neuron (also known as a
perceptron or a threshold-gate) as the basic computation unit. Models of the first
generation, such as the multi-layer per
ceptron, use digital input and output, usu-
ally binary or bipolar. Any Boolean function can be computed by some multi-layer
perceptron with a single hidden layer.
The second generation is based on computation units (neurons) that use an activa-
tion function of a continuous set of possible output values. Commonly, these activa-
tion functions are the sigmoid, or the hyper
bolic tangent. Second generation neural
networks, like first generation networks, can compute arbitrary boolean functions
(after using a threshold). Second generation networks can compute certain boolean
functions with fewer neurons than first gene
ration neurons. Also, second generation
networks with one hidden layer can approximate any continuous, analog function
arbitrarily well. Important to many implementations is the fact that second genera-
tion networks support learning algorithms based on gradient descent, such as error
back-propagation.
The third generation of artificial neural networks is based on spiking neurons, or
integrate and fire neurons. These neurons
use recent insights from neurophysiology,
specifically the use of temporal coding to pass information between neurons. These
networks, like those of the second genera
tion, can approximate continuous functions
arbitrarily well, but with temporally encoded inputs and outputs [11], [12]. Further,
there are function that require fewer neurons in a pulsed neural net to approximate
than would be needed in a second generation network [11].


