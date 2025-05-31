Why use machine learning (or deep learning)?
Manual coding can be cumberson, machine learning can automate this.
Machine learing can automate complex processes with many steps that would be difficult for traditional programming.
The more "rules" there are to a problem, the more attractive machine learning is.
can adapt to continuously changing environemtns easily,  
 **_Discovering insights within large collections of data_** (AI IS FLOURISHING)

When not to use machine learning?
googles #1 rule for machine learning, "if you can build a simple rule-based system that doesnt require machine learning, do that".
A short and simple code should be priortized for menial tasks, not complex machine learning.  
 when you need explainability, deep learning models are uninterpretable by humans.
when errors are unacceptable, machine learning systems are unpredictable and not deterministic.
when you dont have much data, machine learning models typically require large amounts of data.

When to use machine learning.
when you have large amounts of STRUCTURED data. (rows x collumns) i.e algorithms such as XGBoost
Some algorithms include
Random forest.
gradient boosted machine.
naive bayes.
nearest neighbor.
support vector machine.
many more.

When to use deep learning.
when you have large amounts of UNSTRUCTURED data (natural languages, images data) i.e neural network algorithms
some algorithms include.
neural networks
fully connected neural networks
convulutional neural network.
transformers.
many more.

What are neural networks?
inputs (images/audio/random languages) -> numerical encoding (matrixes or tensors) -> learns representation (patterns/features/weights) -> representation outputs (large numerical data set or more tensors) ->
human output (image of cat/"Hey Siri..."/language a joke or serious?)
Use the appropriate neural network for your problem (C.N.N for images or transformers for languages/audio)
Anatomy of Neural Networks.
input layer -> hidden layer(s) -> output layer

Types of learning.
Supervised Learning.
Lots of data and examples of what the inputs should be. i.e photos of cats and dogs with each labled (data and labels)
Unsupervised & Self-supervised Learning.
Learns solely on the data given i.e only the photos of cats and dogs, finds patterns between the two but cannot necesserily differentiate
Transfer Learning.
Learns what one model learns and tranfers it to another. i.e can learn what Supervised Learning model discovered and transfer to another, giving a "head start"

What is deep learning used for?
Youtube algorithms, google translate, speech recognition, computer vision, natural language processing (NLP)
Translation and Speech Recognition == Sequence to Sequence (seq2seq) i.e sequence of letters or sequence of audio waves
Computer Vision and Natural Language Processing (NLP) == Classification/Regression i.e Regression is predicting a number or predicting the coordinates of computer visions "attnetion" and
Classification is predicting if something is one thing or another.

What is PyTorch?
Most popular research deeo learning framework\*
Write fast deep learning code in Python(able to run on a GPU(s))
Able to access many pre-built deep learning models (Torch Hub/torchvision.models)
Whole stack: preprocess data, model data, deploy model in your application/cloud
Originally designes and used in-house by Facebook/Meta (now open-source)

What is a Tensor?
https://www.youtube.com/watch?v=f5liqUk0ZTw
