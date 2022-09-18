# Data-Science-Project on modeling the dynamics of disease transmission and human behavior
COVID-19 has caused a global impact since its outbreak in 2019. Various of efforts have been spent to predict and prevent the transmission of the virus. Some conducted time-series predicting of COVID-19 cases and deaths based on daily confirmed cases and deaths using deep neural network (Alassafi, Madini O et al., 2022). Others also incorporated features indicating human interactions, human mobility, and socioeconomic compositions of countries to make the prediction (Vahedi, B., Karimzadeh, M. & Zoraghein, H., 2021). Here in this project, we explored and examined the effectiveness of predicting COVID-19 cases using Google trends. Given its potentially sensitive and fast reaction, Google trend pattern could provide important signals for the following changes in the number of COVID-19 cases and deaths.

We have two goals to achieve:

Use the Google search activity trends data within a certain window to predict the COVID-19 confirmed cases trends.

Recognize the complications of COVID-19 through Google search trends. This secondary goal can be achieved by interpreting the model for the first goal and identify important features.

Test the generalizability of the model (cross-states, cross-diseases)

We propose applying neural network models including simple RNN, LSTM, and bidirectional LSTM to predict the confirmed COVID-19 cases for the following 5 days based on the Google trend data within 2 weeks. We focus on predictions for three states including California, New York, and Massachusetts, which are metropolitan representatives of the eastern and western U.S. The large populations in these states provide a clear picture of the transmission pattern of the virus over time. Moreover, we are also interested in the most predictive trends for these states and whether the model built from one state could generalize to the other two states.
