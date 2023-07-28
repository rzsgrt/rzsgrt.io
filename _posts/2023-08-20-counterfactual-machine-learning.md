---
layout: post
title:  Counterfactual Machine Learning
categories: [counterfactual]
---
***(disclaimer: I use ChatGPT in this post to make my writing grammatically correct and easy to digest. However, any incorrect information in this post may be due to my misunderstandings. If you come across any inaccuracies, please reach out to me)***

I'll begin by discussing counterfactuals in real life. Suppose one day you ordered a coffee, and then you decided to buy a croissant. Unfortunately, it made you late for the bus stop and, consequently, late for work. Now, you wonder what the outcome would have been if you had simply ordered coffee. Would it have made you late or not? Imagining and predicting the outcome of an event if you had taken a different action is known as a counterfactual.

Let's now use a machine learning example. Suppose we have a machine learning model that predicts the likelihood of a patient developing diabetes, with one of its features is the patient's glucose level. In this scenario, the model predicts that a patient has a high likelihood of developing diabetes, based on their glucose level. Now we may wonder what glucose level would be required for the prediction to change to not indicate diabetes. To answer this question, we can run a counterfactual analysis using the machine learning model, where we simulate changing the patient's glucose level and observe how this affects the prediction.

So, with that example, we can see that counterfactual can be used for *interpreting* model (eventhough its not *casual relationship*).

On final note:
Also, I found this interesting paper [Counterfactual Explanations Can Be Manipulated](https://arxiv.org/pdf/2106.02666.pdf)
