**IMPORTANT:** Please note that the main dataset file, **cases.nia_cases.json**, is not included in this repository due to its large size and confidentiality constraints. If you require access to this dataset for research or replication purposes, please feel free to contact me via email, and I will be happy to share it with you upon request.

Additionally, the file **cleaned_nia_cases.json** will not be present in the data folder initially. This file will be automatically generated after running the preprocessing script. The script processes the main dataset (cases.nia_cases.json), cleans the data, and outputs cleaned_nia_cases.json as part of the preprocessing workflow.

**Please ensure you have the required main dataset file before running the code.**

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
