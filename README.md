# Module 13 Challenge - Neuro Networking 

For this challenge I assumed the role of a risk management associate at Alphabet Soup, a ficitious venture capital firm. This business team recieves many funding applications from startups daily. This team has tasked me to create a model that predicts whether applicants will become successful if funded by Alphabet Soup. 

### Project Findings
The original model Results were a loss of 0.555 and had an accuracy rate of 0.728. These findings weren't the greatest, we the goal was to have an loss of closer to 1. Having a loss of 0.555 indicates my model wasn't able to predict which start up companies will become successful. It also indicates the algorithm of modeling my dataset can be better.

Alternative Model 1:
I tried to tweak the model by adding more hidden layers hoping the machine can learn better in a more complex represenation considering the dataset was large. Which the loss slightly increased, which was a good sign.

Alternative Model 2:
In this model, I decieded to keep the 3 hidden layers but added 4 output neurions and increased the epochs hoping the machine can learn better. Which the machine did slightly bettwe by increasing to 0.5809 but the accuracy decreased.

### In conclusion
If I had more time to play around with this model, I would have tweaked the features, removing some and seeing if it would result in better loss and accuracy. I chose to tweak the epochs, hidden layers and output because it was the faster alternative to see any changes within the model. But in reality adding more hidden layers isn't always the best route because it requires more power to run the model. 