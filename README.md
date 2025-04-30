# 🧠 Neural Network Classification using Keras

“Because if a computer can learn, maybe I can too.”



# 📦 Project Summary

I built and trained deep learning models to classify two types of datasets:
🌸 Iris dataset — classic, clean, elegant (4 features, 3 classes)
✍️ MNIST dataset — messy, pixelated, iconic (784 features, 10 classes)
And no, I didn't just copy code from StackOverflow... I also tweaked it until it stopped throwing errors 😤


# 🔍 What I Allegedly Learned (and Totally Didn’t Just Google)

## Data Preprocessing

Normalized data for stable and efficient training
One-hot encoded labels so the model wouldn’t look at me like “what’s a flower?”


## For MNIST:

Reshaped every image to 784-long vectors
Scaled pixel values from [0-255] ➝ [0-1]
Converted digit labels to one-hot vectors like a responsible machine learning adult



# 🏗️ Model Architecture

## 📘 For Iris:

Input Layer: 4 neurons (one for each feature)
Hidden Layer: 1–2 dense layers with ReLU activation (because ReLU is bae)
Output Layer: 3 neurons with softmax to predict flower type


## 🖼️ For MNIST:

Input Layer: 784 neurons (flattened image)
Hidden Layers: 2–3 dense layers (more neurons = more chaos control)
Output Layer: 10 neurons with softmax (predicting digits 0–9)



# ⚙️ Compilation & Training

Optimizer: adam (because it just works)
Loss Function: categorical_crossentropy for multi-class classification
Metric: accuracy — the good ol' faithful


# 🔁 Training Strategy:

Played around with batch sizes (32/64)
Used validation_split=0.2 during model.fit() to monitor overfitting
Trained over several epochs (until my GPU fan cried for mercy)


# 🧪 Evaluation

Got accuracy scores that made me feel like a genius
Used:
confusion_matrix to catch those sneaky misclassifications
classification_report to flex precision/recall/f1-score



# 📊 Results That I Pretend I Fully Understand:

Dataset	Accuracy	Comments
Iris	~96%	My model is basically a botanist now.
MNIST	~98%	If this model had a pen, it’d write its own digits.


# 🧠 Lessons Learned

Neural networks aren’t that scary once you break them into layers (literally).
Preprocessing is 80% of the battle. (The other 20% is googling TensorFlow errors.)
More layers ≠ better model. Sometimes simple is smarter.
Activation functions are like caffeine — use wisely or crash hard.
You don’t need to be a data scientist. You just need model.fit() and vibes.




# 🤹‍♀️ Bonus Experiments I Might Pretend I Tried

Dropout for regularization
Switched optimizers (RMSprop, SGD, etc.)
Early stopping callbacks
Confused myself with CNNs (Coming Soon™)


# 💡 Final Thoughts

I now fully understand... at least 40% of what Keras is doing behind the scenes.
And that’s enough for me to sleep at night 💤
