In the world of Artificial Intelligence and advancement in technologies, many researchers and big companies like Tesla, Uber, Google, Mercedes-Benz, Toyota, Ford, Audi, etc are working on autonomous vehicles and self-driving cars. So, for achieving accuracy in this technology, the vehicles should be able to interpret traffic signs and make decisions accordingly. <br /><br />
The German Traffic Sign Benchmark is a multi-class, single-image classification challenge held at the International Joint Conference on Neural Networks (IJCNN) 2011. the properties are:<br />
1- Single-image, multi-class classification problem<br />
2- More than 40 classes<br />
3- More than 50,000 images in total<br />
4- Large, lifelike database<br /><br />
here we classify the signs using deep learning(CNN) algorithm. we create the datasets using imageDataGenerator and then made the pictures ready for process.<br />
after making the model, we compiled it with adam optimizer and 'categorical_crossentropy' loss function.<br />
after fitting this model during seven epochs (batch_size = 128), we got 99% accuracy on training/validation sets and <strong>98.2%<strong /> accuracy on the test set
