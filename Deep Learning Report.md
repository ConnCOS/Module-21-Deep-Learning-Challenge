# Overview of analysis
Using a css file containing information on more than 34,000 organizations that have received funding from a nonprofit called Alphabet Soup, the data analysis conducted will determine the applicants for funding with the best chance of success. Using machine learning and neural networks, a target and features are identified from 11 columns of data concerning applicants, their application type, income classification, amount requested and whether the money was used successfully.
 
## Data Processing
Variable for the target was the'Is successful' column, while other columns, such as name, application type, affiliation, classification and use case were variables.

Dropped variable was EIN, which was not needed for analysis.\

## Compiling, Training and Evaluating the Model\
During the optimization phase, many variations were run, with adjustments to number of neurons, number of hidden layers, activation layers and changes to classification cutoff. Using three hidden nodes improved accuracy without compromising data loss. As the value in hidden nodes climbed, improving accuracy, it also created a higher loss of data, often resulting in a loss of more than 55%. Using three layers, with a moderate number assigned to hidden nodes and better fitting the scale/size of data improved accuracy and resulted in a lower loss of data. Target model performance was achieved at 79.3%
