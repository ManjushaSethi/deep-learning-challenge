# deep-learning-challenge
# Overview of the analysis: 
Purpose of the Analysis is to provide a machine learning model to the non profit foundation Alphabet Soup so they can use to predict which organization to provide funds to based on their previous experiences so they can make best use of their funds.
# What variable(s) are the target(s) for your model?
Target is column IS_SUCCESSFUL
![image](https://github.com/ManjushaSethi/deep-learning-challenge/assets/143744238/f22f2230-e736-439a-b887-f1788d700742)

#What variable(s) are the features for your model?
Features are all the columns except EIN and NAME
![image](https://github.com/ManjushaSethi/deep-learning-challenge/assets/143744238/f22f2230-e736-439a-b887-f1788d700742)

#What variable(s) should be removed from the input data because they are neither targets nor features?
EIN and NAME
#How many neurons, layers, and activation functions did you select for your neural network model, and why?
Initially used two hidden layers with 80, and 30 Neuron respectively and used Output layer of 1.  you cannot analytically calculate the number of layers or the number of nodes to use per layer in an artificial neural network to address a specific real-world predictive modeling problem. So it was experimentation.
<img width="1047" alt="Screenshot 2024-02-12 at 9 43 59 PM" src="https://github.com/ManjushaSethi/deep-learning-challenge/assets/143744238/5eae3a30-4dda-4c22-a42c-88aa85202bb0">

# Were you able to achieve the target model performance?
Sorry I was not able to achieve the target model performance.
<img width="857" alt="Screenshot 2024-02-12 at 9 55 07 PM" src="https://github.com/ManjushaSethi/deep-learning-challenge/assets/143744238/12b746b1-ed25-4b26-8c10-e3176685af7b">


# What steps did you take in your attempts to increase model performance?
1.Increased the Hidden layer
<img width="961" alt="Screenshot 2024-02-12 at 10 10 15 PM" src="https://github.com/ManjushaSethi/deep-learning-challenge/assets/143744238/179ae5d3-5094-4c51-ab45-dcf34d233092">

2. Increased the neurons
3. <img width="961" alt="Screenshot 2024-02-12 at 10 10 15 PM" src="https://github.com/ManjushaSethi/deep-learning-challenge/assets/143744238/21fd44f2-4ddd-40f0-8103-2db8d6b03e23">

4. Increased the epochs
   <img width="622" alt="Screenshot 2024-02-12 at 10 11 32 PM" src="https://github.com/ManjushaSethi/deep-learning-challenge/assets/143744238/8681782d-d140-40fe-b38b-e2e962a6f6a2">

6. Also removed the status column as only 5 were inactive
   <img width="762" alt="Screenshot 2024-02-12 at 10 12 16 PM" src="https://github.com/ManjushaSethi/deep-learning-challenge/assets/143744238/6cdf1bf7-e1f8-4542-91b6-d38e40ee50f9">

But still did not increase the accuracy to 75%
With all 4 changes the accuracy was still 72%
<img width="884" alt="Screenshot 2024-02-12 at 10 03 40 PM" src="https://github.com/ManjushaSethi/deep-learning-challenge/assets/143744238/a08e50be-197f-49c2-8172-7e78926eb6c8">

#Describe how you could use a different model to solve the same problem, and explain why you would use that model 
1. May be adding more neural layers and more epoch
2. Recurrent Neural Networks







