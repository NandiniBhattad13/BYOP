# BYOP
## Project Structure
### Main Branch
The main branch contains the following components:

- Jupyter Notebooks: Each feature of the sentiment analysis model is implemented in a separate Jupyter notebook. It has the following notebooks:
  - category.ipynb
  - emotion_analysis.ipynb
  - pos_or_neg.ipynb

- Gradio App Notebook: Additionally, there is a notebook dedicated to implementing a Gradio app for interactive sentiment analysis. Gradio_app.ipynb notebbok is meant for the same
- The documentation to the project.

### Datasets Branch
Here are the datasets used to train the models:
For emotion analysis: go_emotions dataset from the [datasets](https://huggingface.co/docs/datasets/index) library.
For AI text classification: 2.5 B parameters [GPT-2 outputs](https://github.com/openai/gpt-2-output-dataset) dataset.
For positive or negative: imdb dataset of the [datasets](https://huggingface.co/docs/datasets/index) library.
For category prediction: Five [NLI datasets](https://github.com/MoritzLaurer/zeroshot-classifier/blob/main/datasets_overview.csv) with around 885k texts.
