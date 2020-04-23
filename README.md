# continuous_state_sa
Code for the preprint [Learning State Abstractions for Transfer in Continuous Control](https://arxiv.org/pdf/2002.05518.pdf) by Kavosh Asadi, David Abel, and Michael L. Littman.

To run experiments:

	> python run_learning_experiments_(domain).py

Where "(domain)" can be each of {puddle, lunar, cartpole}. To run the transfer experiments, open the file and set params['multitask'] to True.

To reproduce figure 3b, uncomment the call to _num_training_data_experiment()_ in _run_learning_experiments_puddle.py_ and run it.