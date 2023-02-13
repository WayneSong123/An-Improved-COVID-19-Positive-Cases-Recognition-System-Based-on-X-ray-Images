**Introduction**
  COVID-19 is a relatively new respiratory disease 
resulting from the infection of the 
coronavirus SARS-CoV-2 (Queensland Health, 2020). 
The virus is transported from an 
infected person to the healthy through coughing or 
sneezing. As the virus spreads down one’s 
respiratory tract, the patient may become more and 
more difficult to breathe. Therefore, 
effective measures to detect and diagnose the 
infection of COVID-19 as early as possible are 
in great need and necessary. PCR tests perform one 
widely applied technique to diagnose the 
virus. Although doing a PCR test is cheap, it could 
be tremendously inaccurate, as 
researchers from John Hopkins Medicine have shown 
that 20% of such tests might produce 
false-negative results (Bird, 2020). Some patients 
with lung diseases can still diagnose with 
COVID-19 after getting two or even three negative 
results. Thus, X-ray images are needed to 
help diagnose COVID-19. However, after the patients 
have taken their chest X-rays, they still 
need the doctors to analyze the image, which is a 
waste of time both for the patients and the 
doctors. A well-known technique to recognize the 
features of images and classify them is 
called deep neural networks. Researchers made one of 
the existing recognition systems based 
on St. John’s University technology. They used five 
convolutional layers, with ReLu as the 
activation function and softmax as a classification 
modeling tool (Ahmed, 2020). However, their model has 
not been applied to the COVID-19 diagnosis in practice 
yet. When retrying their method, our prediction accuracy is 
much lower than the data presented in their research
paper, which is only about 72%. Besides, their prediction 
accuracy varies greatly after each training 
(shown in Figure 1 and Figure 2).

<img width="464" alt="05c34b7177ec30446837a5e52884f40" src="https://user-images.githubusercontent.com/81739293/218431030-fa7a1e8d-0ce4-48c6-ab4e-0a4a72c8a2d3.png">

**Figure 1. Training and Validation Figure 2. Training and Validation Accuracy
                 Accuracy       **   

  These two problems will prevent the model from being 
applied to COVID-19 diagnosis in practice. By preprocessing 
the training data and modifying the model used to improve the 
current recognition system, our project improves its stability 
and prediction accuracy, making it more possible for the 
model to be applied to COVID-19 diagnosis in practice. The 
results of our project can be used to ease the unbalanced 
of medical resources distribution in China. Doctors can also 
liberate themselves from heavy repetitive work and focus on 
more valuable things.
