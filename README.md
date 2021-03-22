## Multi-label classification  

Often, we may encouter data that can be classified into more than one categories (for example movie genre, items in an image).  
However, typical classification tasks involve predicting a single label, as they treat classes as being mutually exclusive.   

Multi-Label Classification is the supervised learning problem where an instance may be associated with multiple labels. This is opposed to the traditional task of single-label classification (i.e., multi-class, or binary) where each instance is only associated with a single class label. 

  

### Techniques   

There are two main categorizations of methods that can be used to solve for the multi-label classification problem  
* problem transformation methods and 
* algorithm adaptation methods 

In the first case the learning task is transformed into more or single-label classification tasks. 
In the second, the algorithms are adapted so that they can handle multi-label data.   


<br />

The dataset used here is the GoEmotions.  
This is a dataset released from Google and it containes the emotions detected in those texts.  
It is the largest manually annotated dataset of 58K English Reddit comments, labeled for 27 emotion categories or neutral.  
Find the paper on [arXiv.org](https://arxiv.org/abs/2005.00547)
