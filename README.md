# Sentiment analysis on products reviews with lexicon model and transformers
code from google collab
We start the project by importing the data,

We are also doing a Sentiment Analysis with Transformers provided by Hugging Face, DistilBert , using PyTorch and Python.
#fine-tuning our pretrained model in native PyTorch on our dataset.
 -Creating the model and defining its loss and optimize
 -The dataloader passes data to the model based on the batch size.
 -Subsequent output from the model and the actual category are compared to calculate the loss(Loss value is used to optimize the weights of the neurons in the network).


#Saving the Trained Model for inference
We use pytorch :torchave
With the saved final model we can make new prediction by entering new raw text for reviewing.
#Credits
The Sentiment Analysis model was fine-tuned using the DistilBERT model from Hugging Face Transformers library.
