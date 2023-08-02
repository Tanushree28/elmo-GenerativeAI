# elmo-GenerativeAI

Facing an error as:
Argument ``fetch` = <tensorflow_hub.module.Module object at 0x7c9daabace80> has invalid type "Module" must be a string or Tensor. (Can not convert a Module into a Tensor or Operation.)`

To solve this problem we researched an input placeholder to be placed without using a placeholder there are ways to move around using the "Default" key to the default embedding output from many TensorFlow Hub models.
But still getting an error  `'AutoTrackable' object is not callable` we tried to solve this too but it didn't work.

In the notebook `elmo_new`: two retrieval tasks have been added showing the issues we are facing 
