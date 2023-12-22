# GPT-2 Fine-tuning utilizing CUDA

## Branch Overview

This branch of the repository focuses on the attempt to fine-tune the GPT-2 model using a CUDA accelerated GPU and TensorFlow. The primary goal was to generate Steam review-like content based on existing Steam reviews. However, the fine-tuning process led to catastrophic forgetting in the model.

## Key Features

1. **Fine-tuning with CUDA:**
   - Utilized a CUDA accelerated GPU for training the GPT-2 model with TensorFlow.

2. **Catastrophic Forgetting:**
   - Encountered issues related to catastrophic forgetting during the fine-tuning process.

## Issues Encountered

The attempt to fine-tune the GPT-2 model using CUDA acceleration resulted in unexpected challenges, primarily related to catastrophic forgetting. This phenomenon occurs when the model forgets previously learned information while learning new data.

## Code Files

The key code files for this branch are:

1. **CUDA_GPT_Train.ipynb:**
   - The `CUDA_GPT_Train.ipynb` notebook contains the code for training the GPT-2 model using CUDA acceleration and TensorFlow. You can explore the steps taken during the fine-tuning process and the parameters used in this notebook.

2. **Epic_Fail.ipynb:**
   - The `Epic_Fail.ipynb` notebook is dedicated to testing the fine-tuned GPT-2 model. It details the evaluation process and showcases the encountered issues, particularly related to catastrophic forgetting.
