# Action Plan

### Month 1
**Goal**: Format the data so that it can be used for training and testing. Also, create a data loader that applies transforms and performs other functions to artificially inflate the data set.

**Tasks**: Finish formatting the data so that it is the correct size, apply transforms, and create tensor representations of the location of each piece of ecDNA (currently, the center point of each is in a text file. I need to expand these single points into small circles to the model is better able to learn).

**Resources**:
- https://pytorch.org/tutorials/beginner/basics/data_tutorial.html
- https://pytorch.org/docs/stable/data.html


### Month 2
**Goal**: Create the first draft of the model. Implement the U-net architecture and end with a working (but still rough) CNN.

**Tasks**: Choose a combination of linear and non linear layers and create the forward meathod. Create a loss function, optimizer, and write the training function. Then, create a function to evaluate accuracy.

**Resources**:
- https://lmb.informatik.uni-freiburg.de/people/ronneber/u-net/
- https://pytorch.org/docs/stable/nn.html

### Month 3
**Goal**: Test the model and begin to iterate. Mess around with different combinations of layers, transforms, and circle radii to find what works best

**Tasks**: Train the model using a GPU. Test the accuracy, then make changes to fix potential bugs or shortcomings. Continue to train and revise the model.

**Resources**:
- https://pytorch.org/docs/stable/nn.html

### Month 4
**Goal**: Confer with others in my research group and report on our findings. Piece together our methods and results to design a better nextwork.

**Tasks**: Examine the data preparation and architecture of each model produced by our group. Determine which strategy was most effective and draw conclusions about which methods work best. Then, build or modify an existing network with these conclusions in mind.

**Resources**:
- https://arxiv.org/abs/1712.04621 
- https://pytorch.org/docs/stable/index.html

### Month 5
**Goal**: Test and iterate this new frankensteined model. Improve performance as much as possible

**Tasks**: Train and evaluate the model. Work as a group to evaluate sucesses and shortcomings, then brainstorm ideas for improvement. Continue to train 

**Resources**:
- https://pytorch.org/docs/stable/index.html

### Month 6
**Goal**: Share the findings! Report back to the research advisor, and hopefully present it at an end-of-year conference!

**Tasks**: Create a slideshow/poster presentation to communicate our results.

**Resources**:
- https://slidesgo.com/dna