# equational-inference
Repo for the "Similarity-based equational inference in physics" paper.

Although the experiment from the paper is described fully by the **Equational_Inference_Full_Experiment** notebook
and the PhysAI-DS1.csv dataset, it is difficult to read.

To mitigate this, I have uploaded two separate supporting notebooks highlighting the Computer Algebra Derivation
and the core Search Algorithm (which is effectively pseudocode without its Full_Experiment context).

To run each experiment, replace ````tuple_L```` with one of ````tuple_L````, ````tuple_DL````, ````tuple_H````, ````tuple_J````, ````tuple_JW```` in the following line:

````predictions_L, Data_state_history, start_state = experiment(tuple_L)````

SymPy version 1.4
