# Mode Recognition Machine Learning
Code and notes to develop machine recognition of modes that represent the final step of a quantum random walk in the space of orbital angular momentum of LASER light, in which the labelling process is automated.

The material in this repository is supplemetary to this tutorial
https://github.com/EdjeElectronics/TensorFlow-Object-Detection-API-Tutorial-Train-Multiple-Objects-Windows-10
from EdjeElectronics. The steps to follow in lab are:
1) Read the guide cited above and make all the suggested downloads and settings
1) Choose some classes of modes to recognize, for example 5 differently balanced realizations of the superposition of modes |-5> and |5>.
2) Get a suffcient number (for example 250) of shots of these modes through a lab CCD.
3) Run the code "setup_generation.ipynb": it generates a sufficient number of images from the ones taken in lab in which some displacements, blur, disturbances and so on are introduced; it also produces the ".xml" files that are needed to execute the machine-learning process.
4) Go back to the guide and produce all the needed files, skipping the steps related to the labeling of the images, that has automatically been done in the previous step.

You can use this technique to know how similar to the model on which your computer learned are the modes you are genearating or to teach to your computer to recognize wether the experimental realization has some misalignements or errors in the generation of the modes and know ho to correct them.
