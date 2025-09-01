# Signal-Based Wind Turbine Fault Prediction and Modeling

This project focuses on **wind turbine fault prediction and performance modeling** using SCADA (Supervisory Control and Data Acquisition) data.


## Data Description
- **SCADA Signals**: Generator RPM, bearing and winding temperatures, hydraulic and gearbox oil temperatures, rotor speed, nacelle and ambient conditions, wind speed and direction, pitch angle, power output, reactive power, transformer temperatures, grid voltage/current/frequency, etc.:contentReference[oaicite:2]{index=2}  
- **Turbine Datasheet**: Provides rated power, rotor diameter, hub height, cut-in/cut-out speeds, and other technical specifications of the turbines:contentReference[oaicite:3]{index=3}.  
- **Failure Data**: Historical failure logs linked with SCADA signals for supervised learning.  
- **Training/Testing Sets**: Separate CSV files for signals, met mast data, and failure records.  


## Project Tasks
1. **Data Preprocessing**  
   - Handle missing values, outliers, and resample SCADA data.  
   - Normalize features for model training.  

2. **Feature Engineering**  
   - Extract relevant features from SCADA signals (e.g., rolling statistics, averages, standard deviations).  

3. **Modeling**  
   - Train classification models to predict failure events.  
   - Use training data for model fitting and testing data for validation.  

4. **Evaluation**  
   - Assess model accuracy and precision using the provided test datasets.  


## Expected Outcome
- Identification of critical SCADA signals related to turbine failures.  
- Predictive models that can forecast potential failures based on signal patterns.  
- Support for condition monitoring and maintenance planning in wind farms.  
