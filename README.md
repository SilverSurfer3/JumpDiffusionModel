# JumpDiffusionModel


The provided Python script implements an enhanced Jump Diffusion Model for forecasting stock prices, using MRNA (Moderna Inc.) as an example.
The script fetches historical stock data from Yahoo Finance, including adjusted closing prices and sentiment analysis scores derived from hypothetical news headlines. 
It defines a function for the Jump Diffusion Model, incorporating sentiment analysis, external risk factors, and event-driven jumps. 
Parameters for the model, such as initial stock price, drift, volatility, jump intensity, and time horizon, are specified. 
Additionally, the script sets up external factors, event-driven jump factors, and weights for sentiment analysis and external risk factors.
The model is then run for 100 simulations, and the percentage of values above a threshold (70.05) is printed. 
The resulting stock price trajectories are visualized in a matplotlib chart, with annotations 
indicating mean stock prices at specific time points, offering insights into the model's behavior and potential enhancements. 
The script includes error handling to prevent index errors when attempting to annotate points where the condition is not satisfied. 
This comprehensive script provides a versatile framework for exploring and enhancing Jump Diffusion Models in financial forecasting.
