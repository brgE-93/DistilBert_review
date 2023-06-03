# Sentiment analysis on products reviews with lexicon model and transformers
  - code from google collab
  - The project is based on the Amazon product review from customers dataset.
  - This is a multi-class classification. Reviews should be classified into five classes 1,2,3,4,5.(from very bad to very good)
# Used approaches
   - EDA and Different visualization approaches:WordCloud,Pandas,Seaborn,nltk
   - detection of polarity and intensity of emotion:lexicon and rule-based sentiment analysis tool---Vader4
   - Sentiment analysis and multi-labels classification:Transformers provided by Hugging Face, DistilBert,Pytorch,Python
   
    
# fine-tuning our pretrained model in native PyTorch on our dataset.
 - Creating the model and defining its loss and optimize
 - The dataloader passes data to the model based on the batch size.
 - Subsequent output from the model and the actual category are compared to calculate the loss(Loss value is used to optimize the weights of the neurons in the network).


# Saving the Trained Model for inference
We use pytorch :torch_save
With the saved final model we can make new prediction by entering new raw text for reviewing.

# Credits
The Sentiment Analysis model was fine-tuned using the DistilBERT model from Hugging Face Transformers library.
