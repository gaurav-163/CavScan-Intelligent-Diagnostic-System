# CavScan: Intelligent-Diagnostic-System

CavScan is an AI-powered dental diagnostic system that automates the detection and reporting of common dental anomalies. By utilizing advanced machine learning techniques, CavScan aims to enhance diagnostic accuracy and efficiency, ultimately assisting clinicians in providing improved patient care.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Evaluation](#evaluation)
- [Future Work](#future-work)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Features

- **Automated Detection**: Utilizes a fine-tuned VGG16 convolutional neural network (CNN) to identify dental conditions.
- **Common Conditions**: Detects six prevalent dental issues:
  - Calculus
  - Caries
  - Gingivitis
  - Hypodontia
  - Mouth Ulcer
  - Tooth Discoloration
- **Structured Reporting**: Integrates with Crewai and the Gemini API to generate detailed diagnostic reports, providing insights into anomaly severity and probability.

## Installation

To set up CavScan on your local machine, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/cavscan.git
   cd cavscan

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt

3. Run the application:
   ```bash
   python app.py

## Usage

Once the application is running, you can upload dental images for analysis. CavScan will process the images and provide structured reports detailing detected conditions and their severity.

### Example
To analyze an image, simply navigate to the upload section in the interface and select a dental image file. The system will return a report within moments.

## Evaluation
CavScan has been evaluated through experimental validation, demonstrating its efficiency, scalability, and real-time diagnostic capabilities. Results indicate significant improvements in accuracy compared to traditional methods.

## Future Work
Future developments will focus on:
 * Enhancing model accuracy through further refinement of algorithms.
 * Expanding the dataset to include a wider variety of dental conditions.
 * Exploring additional features for improved user experience.

## License
This project is licensed under the MIT License. See the LICENSE file for details.