*Math M148 Final Project • Spring 2025*  
Jerry Shi · Derek Nakagawa · Abhinav Madabhushi · Camden Weber

> **Goal:** Use reinforcement-learning–driven neural-architecture search (NAS) to discover high-performing, size-efficient multilayer perceptrons (MLPs) for any tabular dataset in a *single shot*.

## Repo Map

- RL_model: Contains code to apply and train a RL model on one dataset to find the best MLP architecture for it.
- RL_generalized: Contains code to apply and train a RL model on multiple datasets to eventually find the best MLP architecture for any given dataset. Does this by extracting data specific features.
- Data_Exploration: Applying specific MLP architecture on datasets based on intuition and generally used architectures to draw a comparison. 
- RL_model_visualization: Contains code to apply and train an RL model on one dataset to find the best MLP architecture for it.  In addition, visualizes the train/loss function, validation score, and evolutionary process of the model.
- Research papers neural networks: Contains all the research papers read over for NAS.
- nas_agent_checkpoint_alpha_0.8_epoch_reward_23512_no_stop_1st: Contains the latest weights of the DQN model, so can load these weights instead of running the whole RL model by scratch. These weights are for the Higgs Boson dataset. 
- nas_agent_checkpoint_alpha_0.8_epoch_reward_uci31_no_stop_1st: Weights for the Forest cover dataset.
- architecture_analysis_updated_alpha_0.8_final_reward_formula_forest.csv: Data of all the MLP architectures that the RL model tried along with the reward: accuracy and complexity for the forest cover dataset.
- architecture_analysis_updated_alpha_0.8_final_reward_formula.csv: Final data of all the MLP architectures that the RL model tried along with the reward: accuracy and complexity for the Higgs Boson dataset.
