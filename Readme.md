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
 https://cs.wikipedia.org/wiki/Algoritmus_zp%C4%9Btn%C3%A9ho_%C5%A1%C3%AD%C5%99en%C3%AD_chyby

Gradientni sestup
--------------------
 https://cs.wikipedia.org/wiki/Gradientn%C3%AD_sestup

 hledaní lokálního minima funkce :-)