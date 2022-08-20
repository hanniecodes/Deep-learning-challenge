## Deep-learning-challenge

1. **Overview** of the analysis: The nonprofit foundation Alphabet Soup asked to make a tool that can help select the applicants for funding with the best chance of success. Using machine learning and neural networks,  the features in the provided dataset  were used to create a binary classifier to predict whether applicants will be successful if funded by Alphabet Soup.

**Results**: 

 * Data Preprocessing
    1. What variable(s) are the target(s) for your model? The variable 
        * IS_SUCCESSFUL is successful. 
    2. What variable(s) are the features for your model? 
        * APPLICATION_TYPE
        * AFFILIATION
        * USE_CASE
        * ORGANIZATION
        * STATUS
        * INCOME_AMT
        * SPECIAL_CONSIDERATIONS
        * ASK_AMT
        * CLASSIFICATION
    3. What variable(s) should be removed from the input data because they are neither targets nor features?
        * EIN 
        * NAME
  
 * Compiling, Training, and Evaluating the Model <br>
    4. How many neurons, layers, and activation functions did you select for your neural network model, and why? <br>
        * Originally 110 neurons were selected.  <br>
        * Relu was selected first because it works with binary datasets best for the activation and Sigmoid for the output.  <br>
        * I chose two hidden layers initially using Relu.  <br>
    5. Were you able to achieve the target model performance? <br>
        * The first model selected was not able to achieve the target model performance.  <br>
    6. What steps did you take in your attempts to increase model performance? <br>
        * I switched all of the functions and layers to Sigmoid and except for one hidden layer to be using Relu.  <br>
        * I added an additional hidden layer.  <br>
        * I used 440 neurons in total.  <br>
        * I also kept name.  <br>
        * I also chose different cutoff points. 