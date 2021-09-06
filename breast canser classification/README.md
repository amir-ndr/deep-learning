<h1> Context</h1><br />
Invasive Ductal Carcinoma (IDC) is the most common subtype of all breast cancers.<br />
To assign an aggressiveness grade to a whole mount sample, pathologists typically focus on the regions which contain the IDC.<br />
As a result, one of the common pre-processing steps for automatic aggressiveness grading is to delineate the exact regions of IDC inside of a whole mount slide.<br /><br />

<h1> Content</h1><br />
The original dataset consisted of 162 whole mount slide images of Breast Cancer (BCa) specimens scanned at 40x.<br />
From that, 277,524 patches of size 50 x 50 were extracted (198,738 IDC negative and 78,786 IDC positive).<br />
Each patch’s file name is of the format: uxXyYclassC.png — > example 10253idx5x1351y1101class0.png .<br />
Where u is the patient ID (10253idx5), X is the x-coordinate of where this patch was cropped from, Y is the y-coordinate of where this patch was cropped from, and C indicates the class where 0 is non-IDC and 1 is IDC.<br /><br />

after creating the datasets and preprocessing the images, we create a CNN model and compile it with adam optimizer, then fitted it during 27 epochs with batch_size=128. at the end we got 90% accuracy on the validation set. you can also see the other evaluation in the jupyter notebook.
