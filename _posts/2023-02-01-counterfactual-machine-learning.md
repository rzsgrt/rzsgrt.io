---
layout: post
title:  Counterfactual Machine Learning
categories: [counterfactual]
---
***(disclaimer: I use ChatGPT in this post to make my writing grammatically correct. However, any incorrect information in this post may be due to my misunderstandings. If you come across any inaccuracies, please reach out to me)***

I'll begin by discussing counterfactuals in real life. Suppose one day you ordered an Americano at Starbucks, but it caused you to be late for work and your project being ruined. You wonder what would have happened if you had ordered an Asian Dolce Latte instead. Imagining and predicting the outcome of an event if you had taken a different action is known as a counterfactual."

Let's now use a machine learning example. Suppose we have a machine learning model that predicts the likelihood of a patient developing diabetes, and one of its features is the patient's glucose level. In this scenario, if the model predicts that a patient has a high likelihood of developing diabetes, based on their glucose level being above a certain threshold, we may wonder what glucose level would be required for the prediction to change to not indicate diabetes. To answer this question, we can run a counterfactual analysis using the machine learning model, where we simulate changing the patient's glucose level and observe how this affects the prediction.
