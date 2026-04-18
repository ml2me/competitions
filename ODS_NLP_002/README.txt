Practical Assignment 3: Agents
You need to develop a solution to answer questions about the composition of dishes (for example, calories and macronutrients or by recipes), using large language models (LLMs) with support for tool calling. Participants are required to use an open LLM from Hugging Face together with external APIs (a Recipe API and a Calories API) to accurately determine the nutritional value per serving for given dishes.

Prediction requirements
- For questions related to calories, predictions must be given in kilocalories (kcal).
- For all other nutrient parameters (protein, fat, carbohydrates, etc.) predictions must be given in grams (g).
- Round predictions up to 2 decimal places.

Constraints
- You may use any models, but model size must not exceed 4B parameters and the weights must be open.
- You may not use any additional data beyond what is already provided in the competition.
- A full run of the solution should be fit within Colab or Kaggle resource limits.
- You are allowed to use additional tools.

We provide you with MCP servers for Recipe API and Calories API.

You can start from LLM_agents_start_solution_ipynb_.ipynb