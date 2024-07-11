
# Weed Plant Detection using AI Camera

## Introduction
With the advancement in artificial intelligence and computer vision, it's possible to detect and classify weed plants in agricultural fields. This project focuses on using an AI camera to identify and distinguish weed plants from crop plants, helping farmers manage and reduce weed growth efficiently.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Model Training](#model-training)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Features
- Real-time weed plant detection using an AI camera
- High accuracy in distinguishing weed plants from crops
- User-friendly web interface to monitor and manage detections
- Easy integration with existing agricultural equipment

## Technologies Used
- Python
- OpenCV
- TensorFlow/Keras
- Flask
- React.js
- HTML5
- CSS
- Raspberry Pi (for AI camera integration)
- AWS S3 (for storing detection images)

## Installation
1. Clone the repository:
    \`\`\`bash
    git clone https://github.com/yourusername/weed-plant-detection.git
    cd weed-plant-detection
    \`\`\`

2. Set up a virtual environment:
    \`\`\`bash
    python -m venv venv
    source venv/bin/activate   # On Windows: venv\Scripts\activate
    \`\`\`

3. Install the required packages:
    \`\`\`bash
    pip install -r requirements.txt
    \`\`\`

4. Set up the frontend:
    \`\`\`bash
    cd frontend
    npm install
    npm start
    \`\`\`

5. Set up the backend:
    \`\`\`bash
    cd backend
    python app.py
    \`\`\`

## Usage
1. Connect the AI camera to your system.
2. Start the backend server:
    \`\`\`bash
    cd backend
    python app.py
    \`\`\`
3. Start the frontend server:
    \`\`\`bash
    cd frontend
    npm start
    \`\`\`
4. Open your browser and navigate to \`http://localhost:3000\` to access the web interface.

## Model Training
1. Prepare your dataset of weed and crop images.
2. Train the model using the following script:
    \`\`\`bash
    python train_model.py --dataset /path/to/dataset --epochs 50 --batch-size 32
    \`\`\`
3. Save the trained model to the \`models/\` directory.

## Contributing
1. Fork the repository.
2. Create a new branch:
    \`\`\`bash
    git checkout -b feature-branch
    \`\`\`
3. Make your changes and commit them:
    \`\`\`bash
    git commit -m "Description of changes"
    \`\`\`
4. Push to the branch:
    \`\`\`bash
    git push origin feature-branch
    \`\`\`
5. Create a pull request.



## Contact
**Abhishek Reddy Narahari**  
Email: anvcy@umsystem.edu
