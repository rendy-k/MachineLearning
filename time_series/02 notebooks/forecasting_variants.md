Time series forecasting neural networks have many variants:
1. Neural network architecture
    - Vanilla LSTM
    - Stacked LSTM
    - Bidirectional LSTM
    - CNN LSTM
    - ConvLSTM

2. The number of independent variables
    - Univariate
    - Multivariate

3. The number of dependent variables (only applies for multivariate)
    - Multiple Input Series (forecast only 1 dependent variables)
    - Multiple Parallel Series (forecast multiple dependent variables)

4. The number of forecast steps
    - Step-forward (forecast one step of time ahead)
    - Multi-step (forecast multiple step of time ahead)
        - Vector Output Model (The same as usual archtiecture)
        - Encoder-Decoder Model
