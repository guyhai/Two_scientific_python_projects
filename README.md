# Fisher - Wright & CNN sign language recognition

## Fisher - Wright
we model a population of bacteria and focus on two specific genes responsible
for metabolism of lactose (a sugar present in milk). The first gene has two
variants, or alleles: bacteria with the 𝐴 allele will transport lactose into their cell,
whereas bacteria with the 𝑎 allele will not, and therefore will not metabolize
lactose. The second gene also has two alleles: bacteria with the 𝐵 allele will be
able to digest lactose and convert it to energy, whereas bacteria with the 𝑏 allele
will not (note that digestion only occurs inside the cell).
Therefore, the fittest bacteria are of type 𝐴𝐵, which can both transport lactose
into the cell and digest it.
Goal. Our goal is to simulate this stochastic model using Python

## CNN - Sign Language

We will develop a model that, given an image 𝐱 (an array of
pixels), produces a classification (yA, yB, …, yY) such that yi is the probability that
the image is of the hand sign i and .
This is a supervised learning problem, as we have a set of images with their
corresponding hand signs.
Goal. We want to collect all cropped images into an array X and all classes into
an array Y (don’t forget one-hot encoding the classes). Then, we want to train a
convolutional neural network that, given an example cropped image x
produces the predicted class probabilities y for that image.

 

## Authors

* **Guy Haimovitz** - *Developer*

## Instructor
* **Yoav Ram Phd.**





