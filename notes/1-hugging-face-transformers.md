# Hugging Face Transformers

- Hugging Face is a transformer library
- NLP transformers, text-to-image, image transformer (vision transformer), image-to-text
- multimodal, computer vision, NLP, audio, Tabular (!!)
- different models are called "Tasks"
- Hugging Face transformers can be used with TensorFlow and PyTorch
- you can use hugging face transformers by themselves, or you can fine tune them on custom data
- pretraining is unsupervised
- fine tuning is supervised (example, and example output)

# Hugging Face Pipeline

1. preprocess your inputs
2. run the model
3. post process the outputs

Input into the pipeline: Context + Questions  
Output from the pipeline: Answers

You first fine tune a transformer, then use a pipeline.

Fine Tuning Transformers:

- Tokenizer
- Trainer
  - Evaluation metrics
- Tokenizer
- human readable output

**checkpoint**: set of learned parameters for a model using a training procedure for some task.

pipeline docs: https://huggingface.co/docs/transformers/main/en/quicktour#pipeline

# Hugging face checkpoints

- checkpoints = transformers
- when you store a model, it is known as a check point
- you can use preexisting checkpoints from hugging face
- checkpoints are specific to a kind of task
- a `task` is a kind of model, e.g. sentiment analysis, summarization, text-generation, etc.
- naming checkpoints:
  - (1) username/checkpoint
- examples of `Models` are DistilBERT or BERT
- different models are built off of different `Datasets`

# Hugging Face Spaces

-
