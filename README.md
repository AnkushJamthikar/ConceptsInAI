# ConceptsInAI
This repository contains common questions and their answers in several AI-related concepts

## 1. What is the difference between model.children() and model.parameters() in pytorch? 
Both are generators. model.children() returns layers in the model that can be further used to extract parameters. model.parameters() directly returns parameters in the tensor format. 

## 2. What is the difference between * and ** in python? 
'*' is the iterable unpacking operator and '**' is the dictionary unpacking operator 

## 3. How to change the diamension of the image tensor from (C,W,H) to (1,C,W,H) and vice-versa? 
torch.unsqueeze() and torch.squeeze() are two important functions that changes the diamension of the pytorch tensors
