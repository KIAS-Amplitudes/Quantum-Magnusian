This repository is ancillary to the paper \
"The Diagrammar of Quantum Magnusian" \
by Li Guo, Joon-Hwi Kim, Jung-Wook Kim, Sungsoo Kim, Sangmin Lee, Jian-Rong Li \
\
We provide a Mathematica notebook "Users.nb” accompanied by folders containing data files. \
\
For the current version, the data covers the following cases. \
V = 2, L = 0 \
V = 3, L = 0, 1 \
V = 4, L = 0, 1, 2, 3 \
V = 5, L = 0, 1, 2, 3, 4, 5, 6 \ 
V = 6, L = 0, 1, 2, 3, 4 \
V = 7, L = 0, 1, 2 \
\
We focus on "primary" graphs with no "banana loops".\ 
Up to V = 5, our data exhausts all possible values of L.\ 
For V = 6, 7, due to limited computational resources, we stop at low values of L.\
\
In the BW basis, we suppress the cut propagators, as they do not directly affect Murua coefficients,\
Then, it suffices to consider L = even.\
\
The notebook “Users.nb” has two main functions\ 
	a) Retrieve the Murua coefficient of a given graph\ 
	b) Illustrate how the Murua formula works for a given graph\ 
Examples are given in Chapter 4. Readers are encouraged to play with more examples.\ 
\
(* Known Issue *)\
Banana loops may not be correctly displayed if you are using Mathematica version lower than 12.1.\
