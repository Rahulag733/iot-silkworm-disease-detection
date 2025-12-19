# IoT-Based Silkworm Disease Detection Using Machine Learning

## About This Project

Hey there! This is my final year B.E. project where I'm working on something pretty cool - using IoT sensors and machine learning to detect diseases in silkworms early. 

Silk farming (sericulture) is a big deal in Karnataka, and diseases can wipe out entire batches of silkworms, causing huge losses for farmers. So I thought, why not use technology to help catch these diseases before they spread?

## The Problem I'm Trying to Solve

Silkworm farmers face a constant challenge - by the time they notice something's wrong with their silkworms, it's often too late. Diseases spread fast, and entire crops can be lost. Traditional methods rely on visual inspection, which isn't always accurate and definitely isn't early enough.

## My Solution

I'm building a system that:
- Uses IoT sensors to continuously monitor environmental conditions
- Collects data on temperature, humidity, ammonia levels, CO2, light, and feeding patterns
- Feeds this data into a machine learning model
- Predicts whether the silkworms are healthy or showing signs of disease
- Alerts farmers early so they can take action

## How It Works

### 1. Data Collection
IoT sensors placed in the silkworm rearing environment track:
- **Temperature**: Ideal range is 24-26°C
- **Humidity**: Should be around 75-80%
- **Ammonia levels**: High ammonia = unhealthy environment
- **CO2 levels**: Important for air quality
- **Light intensity**: Affects silkworm behavior
- **Feeding rate**: How much the silkworms are eating

### 2. Data Processing
The sensor data gets preprocessed and cleaned. I use standard scaling to normalize the features so the ML model can learn better.

### 3. Machine Learning Model
I'm using a Random Forest Classifier because:
- It handles multiple features well
- It's pretty accurate for classification tasks
- It can tell me which factors are most important for disease detection

The model is trained on both healthy and diseased silkworm data to learn the patterns.

### 4. Prediction & Alert
Once trained, the model can take real-time sensor readings and predict if there's a disease risk, along with a confidence score.

## What I've Learned

Working on this project has taught me:
- How to work with IoT sensor data
- Data preprocessing and feature engineering
- Machine learning classification techniques
- The importance of early disease detection in agriculture
- Real-world application of ML in solving actual problems

## Technologies Used

- **Python**: Main programming language
- **Pandas & NumPy**: Data manipulation
- **Scikit-learn**: Machine learning
- **IoT Sensors**: DHT22 (temp/humidity), MQ-135 (ammonia), etc.
- **Raspberry Pi / Arduino**: For sensor integration (planned)

## Project Status

This is currently in development as my final year project. The ML model is working well with simulated data, and I'm in the process of integrating actual IoT hardware for real-world testing.

## Future Plans

- Deploy the model on edge devices for real-time monitoring
- Build a mobile app for farmers to receive alerts
- Add more disease types to the classification
- Test in actual sericulture farms
- Maybe add image recognition for visual disease symptoms

## Why This Matters

- Helps farmers catch diseases early
- Reduces economic losses
- Improves silk production yield
- Makes sericulture more sustainable
- Applies modern tech to traditional farming

## About Me

**Rahul A G**  
Final Year B.E. Computer Science Student  
Alvas Institute of Engineering and Technology, Mangalore

I'm passionate about using technology to solve real-world problems, especially in agriculture and security. Check out my other projects on [GitHub](https://github.com/Rahulag733)!

## Acknowledgments

Thanks to my college guides and the sericulture community for helping me understand the real challenges in silk farming. This project wouldn't be possible without their insights.

---

*This project is part of my academic learning and internship experience in IoT and Machine Learning.*
