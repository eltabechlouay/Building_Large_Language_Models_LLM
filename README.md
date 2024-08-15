# Building_Large_Language_Models_LLM

## *GPT Version 1*

I developed this large language model (LLM) by meticulously training it on The Wizard of Oz and crafting the necessary code components on AWS SageMaker. This project involved building a transformer-based model using PyTorch, optimizing the architecture with multi-head attention and feedforward layers, and leveraging AWS SageMaker’s powerful infrastructure for training.

Despite initial hardware limitations, transitioning to AWS SageMaker ensured efficient training and validation, resulting in a robust language model.

By adjusting parameters like embedding dimensions, number of heads, and layers, I optimized the model’s performance, achieving significant improvements in loss values over 500 iterations on a CUDA-Runtime Kernel. Still, unfortunately, it didn't work as expected. Moreover, the generated output still contained nonsensical text, likely due to limited training data or inadequate fine-tuning of hyperparameters. Further fine-tuning and providing more diverse training data could improve the coherence of the generated text.

Likely, I will try to build a second better version of this model, and I will test and fine-tune it for better results.

## *Google Colab Notebook GPT Version 1*

I built the GPT version 1 again, but this time using Google Colab for better and faster processing of runtime. Google Colab allows you to use the built-in T4 GPU, which is far better for others who don't have the INVIDIA GPU to use PyTorch Functions.
*https://colab.research.google.com/drive/1RqfQI_cc81xDka84gsXdxGosMseZpagy?usp=sharing*
