# simple_convnet
A simple convnet implementation on tensorflow

Borrowed the implementation from https://github.com/blackecho/Deep-Learning-TensorFlow with several changes:
  1. Added Channel first option for performance boost
     look: https://www.tensorflow.org/performance/performance_guide#data_formats
  2. Added batch normalization option
  3. Fixed memory leak problem
