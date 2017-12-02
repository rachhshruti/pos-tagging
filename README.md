# POS tagging

# Running the code:
    python label.py training_file testing_file

# Description
- Trained the model given the training_file which contains list of sentences and the parts of speech for each of the words.
- Implemented three types of model:
  - __Simplified:__ There are no dependencies between the words in the sentence when determining their parts of speech.
  - __HMM:__ There are dependencies between the current word and the previous word in the sentence.
  - __Complex:__ There are dependencies between the word and previous two words in the sentence.
- Tested the model using the testing file and achieved an accuracy above 90% for each of the models as given below,

    | Simplified | HMM     | Complex |
    | :--------: | :-----: | :-----: |
    | 93.92 %    | 95.07%  | 91.91 % |
