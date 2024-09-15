The directory includes the following files:

1. README.md: An overview of the project.
2. preprocessing.ipynb: A notebook for data cleaning and preparation.
3. prompting_using_dspy.ipynb: A notebook for generating prompts with DSpy.
4. inferencing.ipynb: A notebook for generating and evaluating case analyses using Together AI.
5. fine_tuning.ipynb: A notebook for fine-tuning the Saul-LM 7B model on the legal dataset.

Additionally, the following directories are included:
1. data: Contains the dataset files used for preprocessing and training.
2. prompts: Stores the templates for prompts used in the prompting step.
3. results: Holds the results generated during the inference step.
4. fine_tuned_model_v2: Contains the weights for the fine-tuned Saul-LM 7B model.

Execution Order:
1. preprocessing.ipynb: Start with preparing the dataset.
2. prompting_using_dspy.ipynb: Generate prompts using DSPy.
3. inferencing.ipynb: Generate and evaluate case analyses.
4. fine_tuning.ipynb: Fine-tune the Saul-LM 7B model with the prepared data.
