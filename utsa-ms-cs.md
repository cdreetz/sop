
I have always been drawn towards learning and building.  Anytime I learned 
something I wanted to apply it and make something with the new knowledge, 
including the reverse where I wanted something so I learned how to make 
it.  Growing up this evolved into learning about and building various 
businesses, some successfuly and some not so much, but always a learning 
experience.  Not until near the end of my undergraduate years did I come 
to understand the power in computer science and software engineering for 
learning and building alike.  Skills that at the basic level are very 
useful for conducting data science tasks and projects, but extend to 
almost unlimited potential, far beyond just cleaning data and training 
models.  

I graduated wtih a Bachelor of Science in Statistics and Data Science from 
UTSA just last year.  My undergraduate journey was nothing to brag about 
and when you look at it on paper it only shows poor performance.  While 
there are a number of factors that played a part in my performance, some 
including having to work full time, 6AM-3PM Monday through Friday, for the 
first couple years.  Or the year I spent taking care of my dad who was 
going through some mental health issues where I would regularly get calls 
to pick him up at hospitals or from the police, during which I tried to 
get him help at a number of facilities none of which would keep him long 
before I would have to go pick him up again.  Eventually after several 
months of barely getting to go to classes or to work, I found a facility 
where he was able to stay long term.  The main contributor to my grades 
was the lack of the program teaching relevant and important skills for 
entering the workforce as a data scientist. To the point that when I 
realized I would be graduating with almost none of the basic required 
skills for data scientist positions making it seemingly impossible for me 
to get a job, I decided I wouldn't be returning halfway through my senior 
year.  Which I was comfortable with doing because I was already running a 
successful e-commerce business and continuing going to school would 
benefit me in no way. 

During this time I focused on scaling my business, hired new employees 
that allowed me to delegate my most time consuming tasks, and before long 
realized that this kind of business would never give me the satisfaction I 
got from learning about and doing more technical or data driven type work.  
I had began learning Python during my previous semester because I saw it 
was one of the most common requirements for data science jobs but at no 
point in my program was it introduced.  So during my academic sabatical I 
continued furthering my Python programming skills and learning data 
science and machine learning the way I wanted since I was no longer 
required to learn what any class wanted me to learn.  I learned how to 
write web scrapers that allowed me to collect data I wanted to analyze, I 
also started learning how to build at least the minimum graphical 
interfaces or front ends to turn the data I collected or models I built 
into usable products.  

While I have very little academic research experience, I have very 
extensive experience in independent research.  One of the more formal 
experiences was during my time with the Google Research TPU program.  I 
had spent quite a bit of time building my foundational knowledge on 
machine learning and deep learning from different network architectures, 
loss functions, optimizers, including the derivations of gradient descent 
and backpropagation.  Eventually wanting to apply theses concepts but was 
limited by the compute I had access to.  I applied for and was granted 
access to Google's TPU Research Cloud program, during which I both 
learned how to use the entire GCP platform from data storage, to training 
models, to also using common pretrained models and APIs provided by 
Google.  


In my current role, I have gained invaluable experience that resonates 
with my academci ambitions.  Among my notable accomplishments is the 
developement of a sentiment analysis pipeline using an open sourced BERT 
model 
fine-tuned for sentiment analysis.  I also developed the machine 
translation system we use for translating and transcribing audio into 
various languages as requested by clients. I had initially built this out 
also with an open source language model but switched to using Azure's 
Cognitive Services machine translation API for the sake of the speed of 
translations.  These experiences were not only made possible by my 
extenside independent study but also solidified my understanding of these 
concepts in practical applications and further fueled my desire to 
continue researching more deeply.

I have considered and researched several different graduate programs which 
helped me come to the conclusion that the CS program would be the best for 
me. After reading all of the graduate level CS courses I was able to come 
up with a complete list of the courses I would take based on both my 
interests and my weaknesses. Classes like parallel processing and cloud 
computing will be vital for the future as models continue to get larger 
and it becomes a necessity to use large distributed computing systems to 
train these models. While I have a foundation given my experiences 
training on multiple cloud platforms and hardware types, a more formal 
learning experience could be beneficial to learn more nuanced skills.  I 
also will be taking Deep Learning, Natural Language Processing, and 
Software Engineering, also while I already have experience using these 
skills practically and also through Stanford Online's Deep Learning 
courses, I would like to further my learning on the concepts.  

Some of the specific topics I plan to research further during the program 
are ensemble or MoE models, knowledge distillation, and model 
interpretability.  A large part of my interest is not in these concepts 
individually but rather how they are related.  In a lot of knowledge 
distillation or model pruning reserach it is observed that large models 
can be downsized by upwards of 90-95% of their original size while 
maintaining performance, and understanding what parts of models are kept 
and what is removed is vital to our ability to interprate large 
'black-box' models.  It is also believed that some of today's most 
successful models, including OpenAI's GPT-4 are mixture-of-expert models 
or MoE's. MoE, distillation, and task specific fine-tuning have already 
proven to be vital techniques in making the most out of state of the art 
models and I plan continue researching in this direction as we have only 
begun to scratch the surface of their potential.  


## MS CS Program

### Focus Areas
The concentrations for the MS-CS program are Cybersecurity, Software Engineering and Data 
Science.  Some of the faculty research areas include algorithms, high performance computing, 
parallel and distributed systems, and software engineering, along with many others.


### Possible Research Topics

- Hierarchial Ensembles will be able to perform similarly to large MoE models with the 
efficiency of energy management systems.  HE are applicable to embedded systems for the 
energy aspect and applicable to server hosted systems for latency and accuracy 
performance.  Airport security cameras use a system that activates models in the order of 
1 Object Detection: Faces 2 Generalized Object Classification to segment people of 
interest 3 Fine Tuned Object Classification to ID individual with a higher confidence 
than general classification.  Each model is an Expert at its respective step in the 
hierarchy.  Minimize the possible distribution of outcomes a model has to estimate for.  
One large model has millions of possible outcomes to consider.  When split up model 1 
has 2 object or no object and model 2 has POI or no POI and model 3 has classify from 
list of 10 POI


### Faculty

Dhireesha Kudithipudi
Cheetah: Mixed low-precision hardware & software co-design framework for DNNs on the edge
- Quantization will play a huge roll in the availability of LLMs to those with limited 
GPU memory, and harnessing quantization will allow for deploying LLMs on home devices, 
laptops, phones, and increasingly smaller devices

ACTION: Automated Hardware-Software Codesign Framework for Low-precision Numerical Format 
SelecTION in TinyML
- This is important because the current state of deciding on a level of low-precision is 
dependent on iteratively experimenting with all precisions which can be costly due to 
retraining already expensive models.  A framework to determine the best precision would 
save orgs the cost of having to try every precision and just train the best


Sumit Jha
BLOOM Large Language Models and the Chomsky Hierarchy
- LLM interpretability is a major interest of mine and an increasingly important research 
topic as we progress with LLMs

Integrating Symbolic and Statistical Methods for Testing Intelligent Systems


Xiaoyin Wang
Leveraging code generation to improve code retrieval and summarization via duel learning
- It has only come more apparant that language models are best pretrained on a wide range 
of tasks or with entirely unsupervised learning and code generation is a particularly 
interesting application of lanugae models for myself

Mining readme files to support automatic building of java projects in software 
repositories


Boosting Complete-Code Tool for Partion Programs
- System dependecy graphs for partial programs would be an interesting topic to reapply 
given more advanced language models to see how they can better build complex programs 
with an established dependency graph


Dakai Zhu
The effects of energy management on reliability in real-time embedded systems
- With the increasing size and compute requirements of large models being able to use 
them in embedded systems will be heavily dependent on also developing around energy 
management and hierarchal model activation schemes
*- I strongly believe hierarchial model systems will play a large part in productionizing 
large models not only for energy efficiency but for latency and even accuracy
*- The idea plays directly into my belief that hierarchial ensembles of small fine tuned 
models will end up being the best performing and most efficient model systems ie. MoE 
ChatGPT

Fatma Arslan
Improved flipped classroom teaching for electromagnetic engineering course
- Adapting to new learning styles is just as important as adapting to new technologies 
today.  The downside is that students are able to adapt to new technologies if they 
choose by going out of there way to learn on their own, but students have no control to 
new classroom learning styles as they are at the mercy of their instructors, some of 
which may or may not have an interest in providing the best teaching they can.

Anandi Dutta
Tweets about Self Driving Cars: Deep Sentiment Analysis Using LSTM
- As someone who has performed sentiment analysis at my job it would be interesting to 
learn more about sentiment analysis from sentiment researchers

Amanda Fernandez
Progressive Data Dropout: An Adaptive Training Strategy for Large-Schol Supervised 
Learning
- Foundation LLMs today are often trained for extended periods of time of weeks because 
the length of training has proved to boost performance compared to models trained for 
shorter time periods.  Due to the large computational requirements at some point the 
models are determined to no longer be worth continuining training largely to free up 
organizations compute for other experiements.  A new dropout scheme could be implemented 
for LLM pretraining to allow for continued training while freeing up resources 
progressively.  Pretrain on 100% of compute for 2 weeks or until return being to 
decrease, allow for progressive data dropout to decrease data size after the 2 weeks 
allowing for training to continue on 60% of compute and freeing up the other 40%.

Murtuza Jadliwala
Zoom on the Keystrokes: Exploiting Video Calls for Keystroke Inference Attacks


### Courses

*5893 AI Practicum (Would like to assist with the practicum) 

6643 Parallel Processing - Prasad, Sushil

*6243 Machine Learning - Markopoulos, Panagiotis

*5633 Analysis of Algorithms - Gibson, Matthew

5573 Cloud Computing - Lama, Palden

*5523 Operating Systems - Zhu, Dakai

*5513 Computer Architecture - Wang, Wei

5243 Computer Vision - Desai, Kevin

*5103 Software Engineering
OR
5233 Artificial Intelligence

Concentration (Is a concentration a requirement?)

5163 Data Science 

5473 Data Mining 

Not seen on ASAP but would like to take

6283 Deep Learning

6263 Natural Language Processing

*5931 Internship in Computer Science
