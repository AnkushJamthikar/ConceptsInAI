# ConceptsInAI
This repository contains common questions and their answers in several AI-related concepts

# 1. What is the difference between model.children() and model.parameters() in pytorch? 
Answer: Both are generators. model.children() returns layers in the model that can be further used to extract parameters. model.parameters() directly returns parameters in the tensor format. 
