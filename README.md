# SignLanguage

A sign language recognition system based on a **CNN** for gesture similarity learning and classification.

---

## Overview

This project implements a **CNN** architecture to recognize sign language 

The system aims to help bridge communication between deaf and hearing individuals by translating sign language into text or commands.

---

## Features

- Uses a CNN Neural Network for learning gesture similarity.
- Learns effective feature embeddings from pairs of sign language images.
- Handles limited training data efficiently by comparing pairs instead of relying on large labeled datasets.
- Real-time gesture detection and comparison.
- Supports both training and inference modes.
  
---

## Getting Started

### Prerequisites

- Python 3.7+
- TensorFlow or PyTorch (depending on implementation)
- OpenCV
- NumPy
- Matplotlib (optional for visualization)
- Other dependencies listed in `requirements.txt`

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/youssefelzahar/signlanguage.git
   cd signlanguage
