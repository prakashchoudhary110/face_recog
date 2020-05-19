# face_recog

Transfer learning scenarios
Remove the fully connected layers near the end of the pretrained base ConvNet.
Add a new fully connected layer that matches the number of classes in the target dataset.
Randomize the weights of the new fully connected layer and freeze all the weights from the pre-trained network.



Briefly, the VGG-Face model is the same NeuralNet architecture as the VGG16 model used to identity 1000 classes of object in the ImageNet competition. The VGG16 name simply states the model originated from the Visual Geometry Group and that it was 16 trainable layers.
