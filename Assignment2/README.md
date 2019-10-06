Data set speeches.txt file provided, sourced from https://raw.githubusercontent.com/ryanmcdermott/trump-speeches/master/speeches.txt
I have dumped my train and test sentences in 2 txt files called traindump and testdump which are provided.
1,2,3,4 gram models have been implemented from scratch with add one smoothing. Add one smoothing generally shifts the probabilty distribution appreicably, hence the values obtained will not be ideal.
I have chosen length of a sentence as 10 for the ngram models text generation task. 
References:
https://stackoverflow.com/questions/51956000/what-does-keras-tokenizer-method-exactly-do
https://machinelearningmastery.com/how-to-develop-a-word-level-neural-language-model-in-keras/ for deep learning tasks of LSTMs and RNNs.
Keras Documentation
https://stackoverflow.com/questions/42943291/what-does-keras-io-preprocessing-sequence-pad-sequences-do
