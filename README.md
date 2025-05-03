# adaptive-dqn-autonomous-driving
Safe autonomous driving with Deep Q-Networks using adaptive interval-based robust control. Integrates Bayesian uncertainty, online error tracking, and CEM planning in the highway-env simulator to improve decision-making under noisy dynamics. 

To re-create the project results, run the notebooks inside the `/notebooks` directory in order. Development was done in Google's Colab, so that would be preferable. Please be sure to upload the required files for each running environment. Notebooks 00 and 01 do not need any. Notebook 02 needs the roundabout DQN model that is trained in notebook 01. Notebook 03 needs the roundabout DQN model trained in notebook 01 AND the transition buffer that is collected in notebook 02. 

If you would like to bypass running notebooks 00-02 and run the evaluation notebook from the start, please make use of the files in the `/utility_files` folder. Note that the `benchmark_results.json` file is not needed anywhere to run the notebooks. The contents of the file were hard-coded in notebook 03 and used for evaluation.

The `/images` folder contains the visual results from notebook 03. 

The `/reports` folder contains the two reports for the project.
