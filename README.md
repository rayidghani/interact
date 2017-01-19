# interact
Code borrowed and modified from Zach Reubenstein's eights repo.


Interact uses Random Forests to find feature interactions for a supervised learning (classification or regression) problem. It looks for feature sequences that occur in consecutive splits in trees within a random forest. The more trees and higher up in a tree a sequence appears in, the more important the sequence is. One use of these feature interactions is to use them in a logistic regression model.
