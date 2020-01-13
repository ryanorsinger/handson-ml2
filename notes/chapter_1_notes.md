online vs. batch (on the fly vs pretrained)
what is instance vs model based learning?
how to evaluate a model
how to tune a model - how do I choose what to tune and what settings do I tune so it's not trial and error
accuracy = (TP + TN) / total observations
how to do association rule learning

AlphaGo would play all possibilities based on current state space against itself (RNN) to obtain a policy


## Diagrams/Images to add to my collection
figure 1-1 from HOML, other diagrams from chapter 1 in HOML
classical vs. ml diagram from Deep Learning in Python
"Dewey Defeats Truman" picture w/ Truman 

Learning rate is tunable (sensitivity to new data)


2 types of genearalization
    - instance based learning: load training data, then measure similarity of new datapoints
    - model based Learning: load training data, build a model, then use model to predict Y for new datapoints X


To evaluate a model, we can build a fitness function to measure how good the model is. or a cost function to see how bad it is.
For example, OLS is a cost function since we're trying to minimize the size of the residual

Sampling Bais ==> "Dewey Defeats Truman" b/c the pollsters called people meaning they only talked to folks w/ phones who answered. The people they called also came from magazine subscription lists and club memberships, rather than anyone from anywhere.


How to address overfitting
- Siplify the model by selecting fewer parameters, reducing the number of attributes, or by constraining the model
- Gather more training data
- Reduce noise in the training data

2 parameters means 2 degrees of freedom
