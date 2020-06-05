# Portfolio
Overview of Data Science projects to date

## [Project 1: Fraud Detection]
Created a Model to detect instances of Online Credit Card Fraud, implementing solutions that fullfilled the additional requirement for interpretability, and addressed the specific nuances of Fraud Detection.

* Exploratory Data Analysis and Data Wrangling.
* Evaluation and subsequent rejection of Principle Component Analysis.
* Oversampling to address Data Balance.
* Evaluation of Metrics, and Precision/Recall tradeoff.
* Feature Engineering motivated by findings from EDA.
* Comparision and Assessment of various Models, Considering Success Metrics, Interpretibility and Computational Expense.
* Conclusion to Implement Random Forest model using Engineered Features.
* Grid Search for Hypyerparameter Tuning.
* Discussion of Practical Implementation into a Bank's Strategy.

![Decision Tree](Images/decision_tree_limited.PNG)


## [Project 2: Musical Genre Classification]
Created and compared 2 Neural Networks to classify a database of 1000 audio tracks into their 10 musical genres: A convolutional neural network trained on visual representations of the audio, and a linear neural network based on extracted musical featues.

* Pre-processed the audio files using functions to pad and crop.
* Extracted key features of the Audio using the Librosa package, e.g. spectral bandwidth.
* Outlier detection to reveal and remove corrupted files.
* for interest, compared musical genres using cosine similarity, created a function to identify similar songs (resulted in tracks by the same artist).

**Convolutional Neural Network**
* Converted audio files to Mel-Spectograms for visual representation.
* Trained a Convolutional Neural Network using Pytorch using ReLU activation functions and dropout.
* Use of model to predict individual tracks, outputting probabilty of each genre.


**Linear Neural Network**
* Used extracted key features to predict labels after addressing multi-colinearity.
* Achieved higher accuracy using extracted features than the visual representation.
* Use of model to predict individual tracks, outputting probabilty of each genre.

![Mel-Spectogram](Images/melspectogram.PNG)

## [Project 3: DOTA 2 Dashboard]
Created a dashboard in R Shiny with multiple features for analytics of 50,000 DOTA 2 Matches.
The anaylsis is desgined to assist with hero drafting, showing multiple hero win-rates, association rules and neural networks to predict the final pick in any game based on previous picks.

* Data Wrangling for each tab, retaining only matches that contained a full set of players.
    * Tab for win rates and pick rates, allowing the user to compare and contrast heroes.
    * Tab for Association Rules showing Support, Confidence and Lift. Allows the User to see common, implied and niche picks for any selected heroes.
    * Tab showing common words in the chat for winning and losing games.
    * Tab incorporating a Linear and a Long-Short-Term-Memory Neural Network to predict the final pick of a game based on previous picks. The reticulate package was used to link to Python code.

![lift_example](Images/lift_example.PNG)
![LTSM_Example](Images/LTSM_Example.PNG)


## [Project 4: Energy Price Modelling]
*
*
*

### Packages Used
*
*
*

## [Project 5: Image Recognition]
*
*
*

### Packages Used
*
*
*


# [Project 2: Image Recognition]
*
*
*

### Packages Used
*
*
*
