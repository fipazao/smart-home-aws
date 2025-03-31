# Smart Home Automation System (AWS IoT + NVIDIA CUDA)

Experience the power of a fully-connected smart home that lets you remotely manage appliances, monitor sensor data, and leverage AI for enhanced security—all integrated with AWS and NVIDIA CUDA.

## Key Features
- **Remote Appliance Control:** Seamlessly control your home's devices through AWS IoT Core.
- **AI-Enhanced Security:** Utilize NVIDIA CUDA for real-time motion detection and facial recognition.
- **Real-Time Dashboard:** Visualize temperature, motion, and light levels with an interactive web dashboard.
- **Data Logging:** Automatically store sensor data on AWS S3 and DynamoDB for analysis and record-keeping.

## Quick Start Guide
1. **Upload Arduino Code:** Flash the contents of the `arduino-code/` directory to your Arduino Uno.
2. **Deploy AWS Lambda Functions:** Set up and deploy the functions in the `aws-lambda/` directory to AWS.
3. **Launch the Web Dashboard:** Install necessary Python dependencies with `pip install -r requirements.txt` and run the Flask app.
4. **Test the AI Security Model:** Execute `ai-security/cuda_motion.py` to initiate security detection features.

This streamlined approach helps you get up and running quickly while demonstrating the seamless integration of IoT, cloud services, and AI-powered security. Enjoy building your smart home solution!