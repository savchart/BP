## Notebooks

1. **scraper.ipynb**: This notebook contains the code for scraping data from finance.poradna.cz.

2. **EDA.ipynb**: This notebook provides an overview of the data through exploratory data analysis.

3. **dataset.ipynb**: In this notebook, the dataset is created, balanced, and preprocessed for further use.

4. **finetune-gpt.ipynb**: Here, the model is fine-tuned on the created dataset using Transformers and Torch libraries.

5. **evaluation.ipynb**: This notebook evaluates the fine-tuned model's performance with various metrics, including accuracy and fluency. Evaluation happens with GPT API.

## Possible Questions for GPT Evaluation:

### Accuracy
- **[1a]**: Has any content been inappropriately omitted from the text?
- **[1b]**: Does the text exhibit any mistakes that change the intended meaning of the text?
- **[1c]**: Are there any other accuracy issues that affect the translation?

### Fluency
- **[2a]**: Are there any grammar problems in the text?
- **[2b]**: Are there any stylistic problems in the text?
- **[2c]**: Are there any other fluency problems in the text?
