# EdgeVision AI

Real-time client-side Edge Computer Vision inference engine powered by TensorFlow.js and MobileNet v2.

## Overview
EdgeVision AI is a lightweight, fully browser-based computer vision application that performs real-time object classification on live video streams directly on the user's device. By leveraging client-side edge inference, EdgeVision AI ensures low latency, zero server bandwidth usage, and high user privacy.

## Features
- **Zero Server Latency:** Runs 100% in the web browser using WebGL acceleration via TensorFlow.js.
- **Privacy First:** Video streams never leave your local device; processing happens locally.
- **Pre-trained MobileNet v2:** Uses high-accuracy MobileNet v2 architecture optimized for web and mobile edge devices.
- **Real-Time Classification UI:** Displays top classification results with live confidence percentages and progress bars.
- **Zero Build Setup:** Fully standalone HTML/JS page with CDN dependencies.

## Architecture & Tech Stack
- **Frontend Framework:** HTML5, CSS3, Modern JavaScript (ES6+)
- **Deep Learning Framework:** TensorFlow.js
- **Model Architecture:** MobileNet v2 pre-trained on ImageNet

## Setup & Local Usage
1. Clone the repository:
   git clone https://github.com/Saniya-2569/edgevision-ai.git
2. Open index.html directly in any WebGL-capable web browser.
3. Grant camera permissions when prompted and click Start Camera & Classifier.

## Live Demo
Host live deployment on GitHub Pages.
