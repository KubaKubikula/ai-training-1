<img width="604" alt="Snímek obrazovky 2021-09-05 v 11 43 38" src="https://user-images.githubusercontent.com/3868751/132124102-469f4589-1f3c-49e6-a9cf-1fa9c1b9f207.png">

- neural network
- lost function 
- entropy
- optimizer
- autograd
- ndarrays
- maderia
-  matrix - indexing and slicing: 
- numpy
- pandas
- torchvision.transforms
- ToTensor and Lambda.
- linear layer
- nn.Module
- nn.Softmax
- nn -- ingeneral

flatten = nn.Flatten()
- this creates string of 01 of each bite from image


Linerani transformace-
-------

https://medium.com/@falgunimukherjee/linear-algebra-for-machine-learning-part-4-linear-transformation-and-eigendecomposition-evd-e669266f18c1

nn.Linear(28*28, 512),
posune nebo nakloní vektor :-) asi teda :-D

nn.ReLU(),
---------------------
https://en.wikipedia.org/wiki/Activation_function
https://en.wikipedia.org/wiki/Rectifier_(neural_networks)

- to asi zanedba minusove hodnoty a pak všechno co není nula tak aktivuje neuron :-) (redneck pochopení)

nn.Sequential


nn.Softmax
 [-infty, infty] - posledni layer (logits) uděla [0, 1]

 Backpropagation 
--------------------
video
https://www.youtube.com/watch?v=tIeHLnjs5U8

 https://cs.wikipedia.org/wiki/Algoritmus_zp%C4%9Btn%C3%A9ho_%C5%A1%C3%AD%C5%99en%C3%AD_chyby
<img width="1018" alt="Snímek obrazovky 2021-09-05 v 12 08 58" src="https://user-images.githubusercontent.com/3868751/132124623-a6d712b3-573f-4111-8904-25c77d8b1f82.png">

Gradientni sestup
--------------------
 https://cs.wikipedia.org/wiki/Gradientn%C3%AD_sestup

 hledaní lokálního minima funkce :-)

 https://cs.wikipedia.org/wiki/Gradientn%C3%AD_sestup

 -- autograd v podstatě propoji jednotlivé listy stromu asi teda

 Optimizinig model
 -------------------
 https://cs.wikipedia.org/wiki/Derivace
 
 - hyperparameter tuning
 	learning_rate = 1e-3
	batch_size = 64
	epochs = 5

 - Optimization Loop
The Train Loop - iterate over the training dataset and try to converge to optimal parameters.
The Validation/Test Loop - iterate over the test dataset to check if model performance is improving.

https://pytorch.org/tutorials/beginner/basics/optimization_tutorial.html#full-impl-label

 - Loss function 
 - Optimizer
 	

Numpy
- ndarray.ndim
- ndarray.shape
- ndarray.size
- ndarray.dtype
- ndarray.itemsize
- ndarray.data

https://jupyter.org/install
command cmd: jupyter-lab

https://cs.wikipedia.org/wiki/MATLAB

https://matplotlib.org/

<img width="629" alt="Snímek obrazovky 2021-09-20 v 15 29 34" src="https://user-images.githubusercontent.com/3868751/134020059-e355a460-89fa-466f-a93f-edb537de2353.png">

https://en.wikipedia.org/wiki/Evaluation_function#In_chess

https://en.wikipedia.org/wiki/Beam_search

