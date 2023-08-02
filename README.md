# elmo-GenerativeAI

Facing an error as:
Argument ``fetch` = <tensorflow_hub.module.Module object at 0x7c9daabace80> has invalid type "Module" must be a string or Tensor. (Can not convert a Module into a Tensor or Operation.)`

To solve this problem we researched an input placeholder to be placed without using a placeholder there are ways to move around using the "Default" key to the default embedding output from many TensorFlow Hub models.
But still getting an error  `'AutoTrackable' object is not callable` we tried to solve this too but it didn't work.

For the error  `'AutoTrackable' object is not callable` we tried to solve this too but it didn't work. In StackOverflow, it says to add `signature`. Even after adding there are issues.
link : https://stackoverflow.com/questions/59471873/autotrackable-object-is-not-callable-in-python

In the notebook `elmo_new`: two retrieval tasks have been added showing the issues we are facing 

`Due to mteb[beir] package installation issue we have been using either kaggle or google collab`


![image](https://github.com/Tanushree28/elmo-GenerativeAI/assets/59421381/4d027a1f-6d52-46bc-bc3b-39d8020e0fde)

![image](https://github.com/Tanushree28/elmo-GenerativeAI/assets/59421381/98b0549a-1cd2-4dde-ac81-12242fa4a46d)

![image](https://github.com/Tanushree28/elmo-GenerativeAI/assets/59421381/aa990f70-a19f-4ebb-a1e9-7983960950d1)


