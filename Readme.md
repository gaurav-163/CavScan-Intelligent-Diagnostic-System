# CavScan

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