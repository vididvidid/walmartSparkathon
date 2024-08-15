# Select to Search

Welcome to the **Select to Search** project! This application allows users to capture screenshots of their device, select a portion of the image, and search for products on Walmart based on the selected region. The results are displayed directly within the app, making it easy to find specific products or similar items.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [System Architecture](#system-architecture)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

**Select to Search** is a powerful tool for finding products by image. Whether you're browsing another app and spot something you like or want to compare products quickly, this app simplifies the process of searching for items based on images.

## Features

- **Overlay Interface**: Seamlessly runs over other apps to capture screenshots.
- **Screenshot Capture**: Take high-quality screenshots of your screen.
- **Region Selection**: Select a specific area of the screenshot to search.
- **Image Processing**: Analyze the selected region using advanced algorithms.
- **Walmart Integration**: Query Walmart’s product database to find exact or similar items.
- **Local Storage**: Save screenshots and search results for easy access.
- **Result Display**: View search results directly within the app.

## System Architecture

![System Architecture](https://github.com/vididvidid/walmartSparkathon/blob/main/Walmart%20Sparkathon.png)


## Technologies Used

- **Android SDK**: For Android app development.
- **Android Studio**: IDE for developing and debugging the app.
- **OpenCV**: For image processing tasks.
- **TensorFlow Lite**: For on-device machine learning inference.
- **Walmart API**: To query product information from Walmart.
- **Gradle**: For dependency management.
- **SQLite/Room**: For local data storage.
- **AWS**: For hosting backend services.

## Installation

To get started with **Select to Search**, follow these steps:

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/vididvidid/walmartSparkathon.git
    ```

2. **Set Up Android Studio**:
    - Open Android Studio and import the project.
    - Ensure that you have the necessary SDKs and tools installed.

3. **Configure AWS Services**:
    - Set up AWS credentials and configure your AWS services for image processing and API integration.

4. **Build and Run the App**:
    - Build the app in Android Studio.
    - Run it on an emulator or a physical device.

## Usage

1. **Launch the App**:
   - Open **Select to Search** from your app drawer.

2. **Capture a Screenshot**:
   - Click on the overlay button to take a screenshot of your screen.

3. **Select a Region**:
   - Use the selection tool to choose the area of the screenshot you want to search.

4. **View Results**:
   - Results will be displayed with options to view product details or find similar items.

## Contributing

We welcome contributions to **Select to Search**! If you’d like to contribute:

1. **Fork the Repository**.
2. **Create a New Branch**: `git checkout -b feature/your-feature`
3. **Make Your Changes**.
4. **Commit and Push**: `git commit -am 'Add new feature'` and `git push origin feature/your-feature`
5. **Submit a Pull Request**.

## License

**Select to Search** is licensed under the [MIT License](LICENSE).

## Made By
- Yash kumar kasaudhan 
- Prakhar Kapoor 
- Ayush Gupta
