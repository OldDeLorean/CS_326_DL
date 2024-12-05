# README

## Project Structure

## Description

- **LayoutGPT**  
  Contains scripts used for layout generation and parsing outputs from a language model.  
  - `parse_llm_output.py`: Processes the output from the language model.  
  - `run_layoutgpt_3d.py`: Runs LayoutGPT in 3D mode.  

- **IDesign.py**  
  A script for generating initial design layouts, used for baseline collection.

- **ml_hypersim+fine_tuning**  
  A directory dedicated to dataset generation and fine-tuning tasks.  
  - `question_answers.csv`: A CSV file containing Q&A data for the model.  
  - `size_questions.csv`: Size-related queries for dataset augmentation.  
  - `ai_001_001_top_down_view.png`: A top-down view of a generated layout.  
  - `ai_001_001_furniture_list.json`: A JSON file listing furniture in a scene.  
  - `box_and_dataset_generation.ipynb`: Notebook for dataset and bounding box generation.  
  - `llama-vision-11b-fine-tuning.ipynb`: Fine-tuning notebook for the llama-3.2-11b-vision-instruct model.  

## Usage

### 1. Baseline Collection  
Run the following scripts to collect baseline data:  
- `LayoutGPT/run_layoutgpt_3d.py`  
- `IDesign.py`  

### 2. Dataset Generation & Fine-Tuning  
Use notebooks and scripts in `ml_hypersim+fine_tuning` for dataset creation and model fine-tuning.  

## Fine-Tuning Model  
Model: **llama-3.2-11b-vision-instruct**