# Reference

Paper:

AttnGAN: Fine-Grained Text to Image Generation
with Attentional Generative Adversarial Networks

https://arxiv.org/pdf/1711.10485.pdf

Code from:

https://github.com/taoxugit/AttnGAN

# AttnGAN_Structure
![](https://github.com/ChihchengHsieh/AttnGAN_Implementation/blob/master/Img/Structure.png)

# Interesting DAMSM Loss functions 
<img src="https://github.com/ChihchengHsieh/AttnGAN_Implementation/blob/master/Img/loss-3.png" alt="img" width="300" height="200">

<img src="https://github.com/ChihchengHsieh/AttnGAN_Implementation/blob/master/Img/loss-1.png" alt="img" width="300" height="150">

<img src="https://github.com/ChihchengHsieh/AttnGAN_Implementation/blob/master/Img/loss-2.png" alt="img" width="300" height="60">



# In terms of the running time..
It took more than 1 minute to finish a batch of data. And, the batch size is 2. So, it's definitely not a toy for my laptop.
<img src="https://github.com/ChihchengHsieh/AttnGAN_Implementation/blob/master/Img/runningtime.png" alt="img" width="500" height="35">




# Simplification

everything.pickle

The code has been simplified a lot for learning purpose. Whole text data has been dumped to just one pickle file. And, one line of code
can help you to load all of them. The deployment related codes have been deleted since this implementation is just for learning the structure.
However, this simplification has hurt the flexibility.




# Use InfoGAN in this structure? (With attention) 
