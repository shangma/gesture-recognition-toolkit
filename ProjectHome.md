The Gesture Recognition Toolkit (GRT) is a cross-platform, open-source, C++ machine-learning library designed for real-time gesture recognition.

**NEWS:** The GRT source has now moved to https://github.com/nickgillian/grt.  The project is also mirrored on this googlecode project, however, we suggest using the [github](https://github.com/nickgillian/grt) frontend for interfacing with the GRT.  The svn repository was moved to git at svn [revision 381](https://code.google.com/p/gesture-recognition-toolkit/source/detail?r=381).

In addition to a comprehensive C++ API, the GRT now also includes an easy-to-use graphical user interface that allows you to stream real-time data into the GUI from another application via Open Sound Control (OSC), record some training data, configure and train a gesture recognition system, stream the real-time prediction results out of the GUI to another application via OSC and save your trained model to a file so it can be loaded by the GRT C++ API.

![http://www.nickgillian.com/archive/wiki/grt/reference/GUI/GUIImage1.png](http://www.nickgillian.com/archive/wiki/grt/reference/GUI/GUIImage1.png)

The GRT has been designed to:
  * be easy to use and integrate into your existing C++ projects
  * be compatible with any type of sensor or data input
  * be easy to rapidly train with your own gestures
  * be easy to extend and adapt with your own custom processing or feature extraction algorithms (if needed)

The GRT features a large number of algorithms that can be used to:
  * recognize static postures (such as if a user has their hands in a specific posture or if a device fitted with an accelerometer is being held in a distinct orientation)
  * recognize dynamic temporal gestures (such as a swipe or tap gesture)
  * perform regression (i.e. continually map an input signal to an output signal, such as mapping the angle of a user's hands to the angle a steering wheel should be turned in a driving game)

The GRT currently works across several operating systems including:
  * Windows (Tested on Windows XP, Windows 7)
  * OS X (Tested on 10.7,10.8, 10.9)
  * Linux (Tested on Ubuntu 12, Ubuntu 14.04)

The current development build of the GRT contains machine-learning algorithms such as:
  * Adaptive Naive Bayes Classifier
  * Ada Boost
  * Bootstrap Aggregator (BAG)
  * Decision Tree
  * Dynamic Time Warping
  * K-Nearest Neighbor Classifier
  * Gaussian Mixture Models (GMM)
  * Hidden Markov Model (HMM)
  * Linear Regression
  * Logistic Regression
  * Min Dist
  * Random Forests
  * Softmax Classifier
  * Support Vector Machine
  * Artificial Neural Network (Multi Layer Perceptron)

In addition to the machine-learning algorithms, the GRT also contains a large number of pre-processing, post-processing, and feature-extraction algorithms such as:
  * Low Pass Filter
  * High Pass Filter
  * Moving Average Filter
  * Derivative
  * Zero Crossing
  * FFT
  * Class Label Filter
  * Class Label Timeout Filter

You can download the current development build of the GRT here: [checkout](http://code.google.com/p/gesture-recognition-toolkit/source/checkout)

The main GRT wiki can be found here: [www.nickgillian.com/wiki/GRT](http://www.nickgillian.com/wiki/pmwiki.php?n=GRT.GestureRecognitionToolkit), which includes tutorials, code examples, and instuctions on how to download and integrate the GRT in your own C++ projects.