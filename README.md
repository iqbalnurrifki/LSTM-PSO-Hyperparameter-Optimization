# LSTM-PSO-Hyperparameter-Optimization
Python implementation of LSTM models combined with Particle Swarm Optimization (PSO), Genetic Algorithm (GA), and Grid Search for time series forecasting. Developed as part of the research paper: "LSTM with Hyperparameter Optimization for Time Series Forecasting."

📊 Dataset
The dataset used in this study was obtained from the **U.S. Energy Information Administration (EIA)**. We used the monthly coal production data for training and evaluation of the LSTM model. Users may directly download the dataset from the official EIA website and preprocess it using the provided pipeline in this repository.

✨ Results
This study compares three hyperparameter optimization methods applied to LSTM for coal production forecasting:
- Particle Swarm Optimization (PSO)
- Genetic Algorithm (GA)
- Grid Search

Performance was evaluated using:
- Root Mean Square Error (RMSE)
- Mean Absolute Percentage Error (MAPE)
The experiments demonstrate that PSO-optimized LSTM achieved the best forecasting accuracy, while GA and Grid Search provided competitive but less efficient results.

👩‍💻 Contributors
Muhamad Syukron – Conceptualization, Methodology 
M. Iqbal Nurrifki – Data Analysis, Validation, Visualization
Ghina Zulfa Inayah – Implementation, Draft Writing, Reviewing & Editing

📜 License
MIT License – feel free to use and modify with proper attribution.
