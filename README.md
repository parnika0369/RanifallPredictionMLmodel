This repository contains a rainfall prediction system built using a Long Short-Term Memory (LSTM) neural network trained on historical weather data. The model focuses on learning long-term seasonal patterns and improving forecast accuracy by experimenting with multiple epoch cycles to optimize training performance.


Key Features:

1.LSTM-based time series prediction for accurate rainfall forecasting

2.Epoch-driven training pipeline, allowing performance comparison across various epoch counts

3.Preprocessing pipeline including normalization, windowing, and sequence generation

4.Model evaluation using MAE/MSE and custom visualizations

5.Easy-to-modify architecture and hyperparameters

6.Exportable model for deployment or further experimentation

Tech Stack:

Python, 
NumPy, 
Pandas, 
TensorFlow, 
Matplotlib, 
Seaborn





Description of the Projected Temperature Change Chart:

The chart illustrates the projected temperature change (in °C) for future years compared to the recent historical average. Each bar represents how much warmer a particular year is expected to be relative to the long-term mean.
The values show a sharp and consistent upward trend, with temperature changes ranging from +21.56°C to over +1900°C. The largest spikes appear in the later years, indicating increasingly extreme warming in the model's predictions.
Overall, the visualization emphasizes a significant rise in temperature deviations, highlighting how future projections far exceed the historical baseline.


<img width="1220" height="486" alt="Screenshot 2025-11-25 134659" src="https://github.com/user-attachments/assets/37caeffc-f4b6-4bbe-ab5b-e90162f61b28" />


Code review:
The screenshot presents a Forecast Summary showing predicted temperature values from 2016 to 2030 based on a model trained using historical temperature data up to 2015.
For each forecasted year, the model outputs a temperature (in °C), followed by a note indicating that the predicted value is “significantly warmer than recent average.”
The predictions show a consistent upward trend, with temperatures rising sharply over the 15-year period.
The summary concludes with a comparison stating that the average temperature over the previous 396 years was 1368.24°C, highlighting how drastically higher the predicted values are.

<img width="685" height="420" alt="Screenshot 2025-11-25 134832" src="https://github.com/user-attachments/assets/9b1c854b-a2c9-462c-a155-593a062be870" />


Loss Function:
The chart visualizes the Mean Squared Error (MSE) loss values for three different target values — 2000, 2500, and 3000.
It uses a bar graph to compare how the loss increases as the target value increases.
The first bar (blue) represents the target value 2000, with an MSE loss of 1,163,649.39.
The second bar (green) shows the target value 2500, with a higher loss of 2,002,640.49.
The third bar (red) corresponds to the target value 3000, with the highest loss of 3,341,631.59.


<img width="816" height="529" alt="Screenshot 2025-11-25 134938" src="https://github.com/user-attachments/assets/b70af2aa-2b88-4499-92fe-74e11b3ac769" />
