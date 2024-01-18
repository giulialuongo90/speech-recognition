The purpose of the analysis is the training of models based on neural networks for speech recognition. Each word (30 in this dataset, in English) is associated with sequences that represent its "spoken" word.


The models can be used in the field of voice recognition, aimed at human-machine communication: some application examples could be voice assistants, the simultaneous transcription of spoken speech into text or even translation.


The dataset used contains sequential speech recognition data: it is made up of 41849 sequences, each made up of 101 time instants. At each time instant there are 40 measurements.


The dataset consists of 30 classes, where each class represents a spoken word. The words present in the dataset are: bed, eight, house, off, sheila, two, bird, five, left, one, six, up, cat, four, marvel, on, stop, wow, dog, go, nine, right , three, yes, down, happy, no, seven, tree, zero.


The architectures used in this analysis are MLP (Multi-Layer Perceptron) and CNN (Convolutional Neural Network). In both cases, a first phase of selection of the optimal hyperparameters was carried out, through the sklearn ParameterGrid class.
