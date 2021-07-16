## Customer Message Domain Classification

Haptik is one of the world's largest conversational AI platforms.
It is a personal assistant mobile app, powered by a combination of artificial intelligence and human assistance.
It has its domain in multiple fields including customer support, feedback, order status and live chat.

We have with us the dataset of Haptik containing the messages it receives from the customers and which topic(class) the messages refer to.

We created a model predicting which class a particular message belongs to using NLP.
Additionally used techniques like LSA (Latent Semantic Analysis) and LDA (Latent Dirichlet Allocation) to assign topics to new messages.

### About the dataset

The dataset has details of 40000 messages. We predict the category.

The label encoding of the category column:

{0: 'casual',
 1: 'food',
 2: 'movies',
 3: 'nearby',
 4: 'other',
 5: 'recharge',
 6: 'reminders',
 7: 'support',
 8: 'travel'}

### Evaluation metrics

For this particular dataset, we have used simple F1 score(average="macro") as the evaluation metric. 

### Outcomes

I applied the following skills:

    Text preprocessing techniques like tokenization, vectorization, etc.

    Implementation of Logistic Regression, Naive Bayes and Linear SVM.

    Topic modelling with LSA (Latent Semantic Analysis) and LDA (Latent Dirichlet Allocation)
