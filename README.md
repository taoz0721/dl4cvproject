# dl4cvproject
Image captioning combines the most advanced deep learning models in computer vision and natural language processing. In this project, we apply image captioning to the \textit{Hateful Memes Challenge} dataset to identify hateful content. We first developed a combined model of CNN and LSTM to generate captions. We used pre-trained Inception V3 model for image encoder to extract image features. Then we built a bidirectional LSTM model to generate captions. We trained the model over \textit{Flickr 8k} dataset and saved the best model for transfer learning. For \textit{Hateful Memes} dataset, we use the pretrained model to generate image caption. We built a BERT model as our sentiment classifier. In order to evaluate the performance of the joint model, we also implemented several conventional deep neural network to directly classify the image data as our base models.
