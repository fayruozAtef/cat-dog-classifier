# cat-dog-classifier
A model that classifies between cats and dogs using tensor flow
The used dataset is from a stored dataset in https://storage.googleapis.com/mledu-datasets/cats_and_dogs_filtered.zip , which is splitted into train and validation datasets
Steps:
  1. Read the images and convert it into tensors.
  2. Define augmantaion function and apply on the images to increase the size of the training dataset.
  3. Divide the train dataset into batches.
  4. Build the model (classifier)
  5. Define the hyper-parameters : loss = binary crossentropy , optimizer = adam
  6. Start training the model over 15 epoch
