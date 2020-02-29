# Tensorflow 2.0 _Practice

# Content
1. Classical
  - Regression Problem
    - AUTO_MPG Dataset
  - CNN
    - Mnist Dataset
  - CNN + RNN
    - CNN --> RNN
    - CNN + RNN
2. Projects
  - Movie Recommendation
  
 ---
 
# Detail
1.1 Regression Problem
 
2.1 Movie-Recommend system
Python send a MemoryError when I read the whole dataset. The type of dataset are int64 and float64. Solutions are as follows:

|Id|Solution|
|:-:|:-|
|1|Change the dtypes to float16 / float32 if you don't need too high precision|
|2|Read the dataset as batches|
|3|Delete the variables when "for loop" is over|
