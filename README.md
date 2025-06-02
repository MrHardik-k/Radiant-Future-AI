# Radiant Future AI

## Overview

The Radiant Future AI project is an AI-driven solution designed to provide personalized recommendations for solar panel installations. At the core of this project is an **advanced machine learning model** that predicts solar panel requirements with remarkable accuracy. This feature is the highlight of our system, leveraging techniques to ensure precise and reliable predictions.

### Core Features

1. **Solar Panel Requirements Prediction**
   - **Advanced Machine Learning Model**: Our prediction model utilizes **Random Forest Regression (RFR)**, chosen after extensive evaluations against models like **Stochastic Gradient Descent (SGD)** and **Multi-Layer Perceptron (MLP)**. The RFR model stood out for its superior performance, ensuring high accuracy and robustness in predictions.
   - **Dataset**: The model is trained on a meticulously curated dataset comprising historical solar energy production data, geographical information, and weather patterns. Data preprocessing steps included normalization, handling missing values, and feature selection to enhance model performance.
   - **Model Tuning**: Hyperparameter tuning was performed using grid search to optimize the number of trees, depth, and other parameters, ensuring the model's efficiency and accuracy.
   - **Evaluation Metrics**: The model's performance was rigorously evaluated using metrics such as **R2 score**, **Mean Absolute Error (MAE)**, and **Root Mean Squared Error (RMSE)** to ensure it surpasses industry standards.

2. **Energy Consumption Prediction**
   - An intelligent system that forecasts energy consumption based on historical data and user inputs, helping users plan their energy needs effectively.

3. **Weather-Driven Insights**
   - Integrates real-time weather data to provide actionable insights on solar energy generation, allowing users to optimize their energy usage and panel positioning.

4. **ROI Analysis**
   - A comprehensive analysis tool that offers detailed charts and visualizations, including metrics like daily energy generation, monthly energy consumption, and installation costs, to help users understand the financial benefits of their investment.

5. **Installation Pricing**
   - A pricing calculator that factors in various parameters to provide accurate cost estimates for solar panel installations.

6. **Carbon Footprint Reduction Estimation**
   - Estimates the reduction in carbon footprint achieved through the adoption of solar energy, promoting sustainable energy practices.

### Technologies Used

- **Machine Learning**: Random Forest Regression (RFR), Stochastic Gradient Descent (SGD), Multi-Layer Perceptron (MLP).
- **Evaluation Metrics**: R2 score, Mean Absolute Error (MAE), Root Mean Squared Error (RMSE).
- **Frontend**: HTML, CSS, JavaScript.
- **Backend**: JavaScript, Firebase Authentication, MongoDB Database.
- **APIs**: 
   - **Open Weather API**: For real-time weather data.
   - **Geocode API**: For geographical data.
   - **Peak Sunny Hours by NASA API**: To accurately predict solar energy potential.

### Project Architecture

- **Frontend**: The user interface is built using **HTML**, **CSS**, and **JavaScript**, providing a responsive and interactive user experience.
- **Backend**: Powered by **Node.js**, the backend ensures secure and efficient handling of user data and interactions. **Firebase Authentication** manages user access, while **MongoDB** serves as the database for storing and retrieving user and project data.
- **APIs**: Integration of various APIs allows real-time data fetching, enhancing the predictive accuracy and user experience.

### How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/soumya-1712/radiant-future-ai.git
    ```
2. Install dependencies:
     ```bash
      cd radiant-future-ai
      npm install
    ```
3. Run the application:
     ```bash
      npm start
    ```
4. Access the application at `http://localhost:3000`.

### Contributors
- [Soumya Dhakad](https://github.com/soumya-1712)
- [Hardik Kanzariya](https://github.com/MrHardik-k)
- [Aman Raj](https://github.com/Amanraj4482)
- [Priyanshu Pandey](https://github.com/Harshpf)

---
