In the world of Artificial Intelligence and advancement in technologies, many researchers and big companies like Tesla, Uber, Google, Mercedes-Benz, Toyota, Ford, Audi, etc are working on autonomous vehicles and self-driving cars. So, for achieving accuracy in this technology, the vehicles should be able to interpret traffic signs and make decisions accordingly.
The German Traffic Sign Benchmark is a multi-class, single-image classification challenge held at the International Joint Conference on Neural Networks (IJCNN) 2011. the properties are:
1- Single-image, multi-class classification problem
2- More than 40 classes
3- More than 50,000 images in total
4- Large, lifelike database
here we classify the signs using deep learning(CNN) algorithm. we create the datasets using imageDataGenerator and then made the pictures ready for process.
after making the model, we compiled it with adam optimizer and 'categorical_crossentropy' loss function.
after fitting this model during seven epochs (batch_size = 128), we got 99% accuracy on training/validation sets and 98% accuracy on the test set