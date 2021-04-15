# powerforecast


As renewable power sources has gotten more popular in the past years, the operation of power networks became more complex. This is caused by the fluctuating nature of these renewable sources like solar and wind power. Compared to the steady generation of power with coal power plants and gas turbines, wind speed and cloud cover are highly variable, causing the power generation to vary too.

To succesfully manage the power networks, a bidding system is introduced to the power market where electricity generators and consumers can submit how much power they predict they will generate or consume the following day and for which price. Thus, to make the most profit, generators and consumers try to predict the day ahead energy price to make the most profitable biddings for the day head.

The authors of “Deep Learning-Based Multivariate Probabilistic Forecasting for Short-Term Scheduling in Power Markets”[1] propose to use a bidirectional LSTM network to predict the future price of energy. In this blogpost (https://gist.github.com/janvandorth/d4739cf3050ca3c836bc4736c36a5c71), this bidirectional LSTM network will be build from scratch using the parameters and the model architecture proposed in the paper. The code is found in this repository.
