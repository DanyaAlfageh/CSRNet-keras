# CSRNet-keras Original Source
This is a fork of the original https://github.com/Neerajj9/CSRNet-keras please head to the original repo to get more details regarding CSRNet.

## CSRNet-keras-with-attention
This repo was forked to be used in research to add Attention to CSRNet. The code here is modified of to the original file

The following changes have been applied
## Modifications :

| File | Modification |
| --- | --- |
| Model | we have added a dense layer and dropout layer to the Model |
| Model | We have opted for Adam optimizer in the floowing settings adam(lr = 1e-8, decay = (5*1e-4)) |
| Model | We have used mean squared error as our loss function|