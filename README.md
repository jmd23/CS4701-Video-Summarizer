# YD_Transformers_jl2726_jmd496_wnl6=

Our project is a video to story AI application. It takes in a video, extracts image frames, captions these images, and then summarizes the output text to (ideally) tell a cohesive story/summary of the video. 


The following was our **_demo 1_** script, which we have left in the Readme for archival purposes.

Iris will be demonstrating the tokenizer, and image/caption pre-processing. They will run tests to show accuracy, cosistency, and appropriate padding of the tokenizer. Other tests will show correct size/number of channels of the image pre-processor. The TA should expect to see "all tests passed!" for non-trivial input strings and images. 

Josh will be demonstrating the Convolutional Neural Network (CNN) and Recurrent Neural Network (RNN). The CNN tests ensure the correct number of output features, and the RNN tests ensure the output is of correct size, [max_length x vocab_size]. The TA should expect to see all tests passed. They will also begin the training process of the model on a small subset (10 images captions) of the Flickr30 dataset

Wendy will demonstrate the training of the model, and the caption prediction on a new iage. The TA will see 10 epochs of training, with the loss monotonically decreasing across epochs. There is also a validation set; the model will be run on this set and average loss will be observed. The trained model will then be fed a new image, which will output a caption (*this implementation may not yet be perfect*).
