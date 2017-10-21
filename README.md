# This notebook implements a keras LSTM in R in comparison to the python implementation

It is not yet well known that keras is available for R. See details on this topic at https://tensorflow.rstudio.com/keras/ where there is also installation instructions.

It is even possible to start tensorboard from within R, see https://tensorflow.rstudio.com/keras/articles/training_visualization.html and more on tensorboard at https://www.tensorflow.org/get_started/summaries_and_tensorboard. The video "Hands-on TensorBoard (TensorFlow Dev Summit 2017)"  https://www.youtube.com/watch?v=eBbEDRsCmv4 is a great starting point.


The original implementation in python is located at https://github.com/Azure/lstms_for_predictive_maintenance 


## Learned lessons
- it seems easier to scale the data using python's preprocessing.MinMaxScaler
- the data generator of python is handy, could not find something similar for R, let me know if there is something
- data wrangling seems to be easier with R, but maybe that opinion is due to my limited knowledge of python
- At least for me (on a mac) i had to select the "view in browser" option in the RStudio window which opens at the command ""tensorboard("logs")" for tensorboard. The RStudio window kept empty.
