# Machine-Learning-Project-Object-Detection-using-YOLO-v4

The word "object recognition" will be used generally to refer to both object detection and image classification, which are tasks that call for algorithms to identify the classes of objects that are present in an image.
In detail we can say that, A computer vision technique called object detection is used to find occurrences of objects in pictures or movies. To generate useful results, object detection algorithms frequently use machine learning or deep learning. Humans can quickly identify and pinpoint objects of interest when viewing photos or videos. Object detection seeks to automate the replication of this intelligence.

#How It Works

->Object Detection Using Deep Learning:
    -Create and train a custom object detector: To train a custom object detector from scratch, you need to design a network architecture to learn the features for the      objects of interest. You also need to compile a very large set of labeled data to train the CNN. The results of a custom object detector can be remarkable. That        said, you need to manually set up the layers and weights in the CNN, which requires a lot of time and training data.
    -Use a pretrained object detector. Many object detection workflows using deep learning leverage transfer learning, an approach that enables you to start with a          pretrained network and then fine-tune it for your application. This method can provide faster results because the object detectors have already been trained on        thousands, or even millions, of images.
->Object Detection Using Machine Learning:
    -Machine learning techniques are also commonly used for object detection, and they offer different approaches than deep learning. Common machine learning         t      techniques include:
    -Aggregate channel features (ACF)
    -SVM classification using histograms of oriented gradient (HOG) features
    -The Viola-Jones algorithm for human face or upper body detection
    
Similar to deep learning–based approaches, you can choose to start with a pretrained object detector or create a custom object detector to suit your application. You will need to manually select the identifying features for an object when using machine learning, compared with automatic feature selection in a deep learning–based workflow.       
