# DeepLeearning.AI: ChatGPT Prompt Engineering for Developers

This repo contains notebooks adapted from the short course available from: https://www.deeplearning.ai/short-courses/chatgpt-prompt-engineering-for-developers/

The notebooks here allow you to also use keys from Azure OpenAI.

## Setup
* Copy `.env_template` to `.env` and fill in the templated env variables.
* Create a conda environment, install necessary packages and start your jupyter server
  ```
  conda create -y -n dlai_prompting python=3.9
  conda activate dlai_prompting
  pip install -r requirements.txt
  jupyter notebook
  ```