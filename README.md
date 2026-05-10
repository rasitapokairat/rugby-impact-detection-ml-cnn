# Impact and Fall Detection from Instrumented Rugby Vest and Mouthguard

Master’s Dissertation Project — MSc Data Science, University of Bath (2022)

Developed an end-to-end deep learning pipeline using wearable sensor data from an instrumented rugby vest and mouthguard to detect impact events and player falls in rugby matches. The system combined multiple CNN-based learners with ensemble learning techniques and presented outputs through an interactive dashboard for real-time player safety monitoring.



## Project Overview

Player safety is a major concern in contact sports such as rugby, where repeated impacts and falls can lead to severe injuries and long-term health risks.

This project investigated whether wearable sensor devices could be used to automatically detect:
- High-impact collision events
- Player falls
- Potential safety risks requiring immediate coaching intervention

The research utilised:
- Instrumented rugby vest
- Instrumented mouthguard
- Accelerometer and motion sensor data
- Deep learning classification models

The final solution aimed to support coaching staff in monitoring player well-being and making faster substitution decisions during gameplay.



## Objectives

- Detect rugby impact events using wearable sensor data
- Detect player falls using motion signals
- Compare multiple CNN learner models
- Evaluate ensemble learning performance
- Visualise player safety metrics through an interactive dashboard
- Assess usability of the rugby vest prototype



## Dataset

### Sensor Sources
- Instrumented rugby vest
- Instrumented mouthguard

### Data Characteristics
- Multivariate time-series sensor data
- Motion and acceleration signals
- Impact and non-impact labelled events
- Fall and non-fall labelled events

### Challenges
- Limited dataset size
- Low diversity of training samples
- Sensor noise and variability between players



## Tech Stack

### Machine Learning
- Python
- TensorFlow / Keras
- CNN (Convolutional Neural Networks)
- Ensemble Learning

### Data Processing
- NumPy
- Pandas

### Visualisation
- Plotly
- Dashboard visualisation



## Workflow

```text
Wearable Sensors
        ↓
Signal Collection
        ↓
Preprocessing & Segmentation
        ↓
CNN Training
        ↓
Impact/Fall Prediction
        ↓
Ensemble Learning
        ↓
Dashboard Visualisation
```



## Model Performance

| Task | Validation Accuracy | Test Accuracy |
|---|---|---|
| Impact Detection | >95% | >95% |
| Fall Detection | >95% | >95% |

### Key Findings
- Individual CNN learners performed strongly on classification tasks
- Ensemble learning did not significantly improve final accuracy
- Limited dataset diversity reduced ensemble effectiveness
- Wearable sensors demonstrated potential for real-time safety monitoring



## Dashboard Features

The final dashboard included:
- Player impact monitoring
- Fall event tracking
- Interactive event visualisation
- Sensor activity graphs
- Safety-focused performance insights

This enabled coaching staff to monitor player well-being during gameplay.



## Research Contributions

This project demonstrated:
- Practical application of wearable AI in sports analytics
- Deep learning for biomechanical event detection
- Real-time safety monitoring concepts
- Integration of hardware sensor systems with ML pipelines

The dissertation also proposed future improvements for the next generation of the instrumented rugby vest prototype.



## Author

Rasita Pokairat

MSc Data Science — University of Bath

LinkedIn: [www.linkedin.com/in/rasitapokairat]
