I updated the code to work on python 3, and in Jupyter notebook.
To run, open the "Execute" jupyter notebook.  It currently runs in 'test' mode after perfunctory training with data obtained from Simple Igor, since Igor seems to provide some excellent responses I wanted to see if a generative SNN could be taught 'by' Igor.  It is a fun project thus far.  Currently, Victor's responses are very poor indeed, due to the paucity of training data I have obtained from Igor.  My next objective is to create a comprehensive list of questions and responses from Igor that should allow Victor to learn well enough.  In order to do so, I need to remove the 'quote author' from igor's response -- a task that isn't as trivial as it first appears.  Of course, I only need to be 99.5% successful at doing this -- something I should keep in mind (perfection isn't required for prototyping early indication of success).

And, I'm getting distracted by charachter-level DNNs, and reinforcement learning.

--m4gr4th34

Original readme w/ minor mods:

# Chatbot
Victor - A generative ChatBot based on Sequential Neural Network and Deep Learning which can be trained on any desired dataset for specific purposes. Instead of ordinary ChatBots which are based on hard-coded responses, it can understand context and respond accordingly.

## Description
The fame of Deep Learning is at its epitome today. This here is a simple demonstration of what elementary level Deep Learning can achieve.
Our project, Victor is a generative chatbot that works on a sequential neural network. 

"Victor" represents one of the several possibilities that are possible by training a sequential neural network. Going into the specifications, it is constructed of three layers of the sequential neural network each containing 128 neurons. The encoder and decoder have a vocabulary size of 20,000 each. The corpus used for training is a collection of dialogues from 617 movies containing about 220,000 conversations (Cornell Movie Dialogue Corpus).  

The real "catch" about Victor is that it can be trained on any data we like, it can learn however we want it to. It gives contextual answers instead of hard-coded responses. It draws information from previous conversational exchanges and is thus, closer to how humans interact. The ability to be trained on any data is not only limited to English, it can be trained in any language we want it to any that is the real beauty of it. 

The bot performs extremely well on casual conversations that are prevalent in movies given the fact that we had a relatively short time to train it and thus, several parameters had to be compromised (number of neurons in each layer etc.). Talking about future improvements, we can train it on even a bigger dataset and use more layers or more number of neurons in each layer. Also, we could add the feature of training it simultaneously while using it which would further increase its accuracy with experience.

## Tools and Libraries used

- Tensorflow
- Tkinter
- PyCharm
- SublimeText

## Instructions to run
There are three steps involved in running the chatbot:

### To train the bot 
- a. Open the file "seq2seq.ini" 
- b. Set 'mode = train' 
- c. Run the file execute.py using the code "python execute.py"<-- not needed if running execute on jupyter --M4gr4th34

### To test the bot after training
- a. Open the file "seq2seq.ini" 
- b. Set 'mode = test' 
- c. Run the file execute.py using the code "python execute.py"<-- not needed if running execute on jupyter --M4gr4th34

### Finally to launch the chatbot in serve mode run "host.pyw" file. <-- not needed if running execute on jupyter --M4gr4th34

And, now you can enjoy the fun conversation with the chatbot !!
