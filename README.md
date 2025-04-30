##Emotion Classifier - Multi-label Text Emotion Detection 
I tried building an emotion classifier that categorizes a sentence into a combination of 28 emotions (yes, it’s a multi-label task). The dataset used is [https://www.kaggle.com/datasets/debarshichanda/goemotions]

#### Architecture
The model is a simple deep learning stack:
- Embedding Layer
- BiLSTM
- Multi-Head attetnion (4 heads)

#### Problem Faced:
Despite:
- Adding Dropout
- Using L2 regularization
- Reducing model complexity

I still couldn't fix the overfitting:
- Train Accuracy : ~90%
- Validation Accuracy: ~28%

I ran 100s of epochs, experimented with learning rates and decay values, but the model kept failing to generalize. I realized this project was becoming a sunk cost. Like in chess — sometimes, you’ve got to sacrifice the queen to save the game.


#### Why I stil Uploaded this?:
- To decument my failed experiments
- Because failure teaches more than success
- So someone else migth pick this up and make it better
- So I can move on and focus on building greater things

  #### Repo Structure (might be messy):
I uploaded this a bit quickly - not perfect, but functional 
- ```notebook/``` : whole code used in one notebook (might be messy)
- ```model``` : The main model that I built

#### Final thoughts:
I’m still learning, and this is just one battle. I’ll be back with stronger projects, better ideas, and cleaner repos.

If you want to take this project and improve it — go ahead. If not, that’s cool too.

##### With hardwork and love - Mann
