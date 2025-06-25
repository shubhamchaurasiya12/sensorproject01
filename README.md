<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SENSORPROJECT01</title>
    
    <!-- Tailwind CSS for styling -->
    <script src="https://cdn.tailwindcss.com"></script>
    
    <!-- Google Fonts: Inter -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;700&display=swap" rel="stylesheet">
    
    <script>
        // Custom configuration for Tailwind to use the "Inter" font family
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                    },
                }
            }
        }
    </script>
    <style>
        /* Basic style to ensure body takes full height */
        html, body {
            height: 100%;
            font-family: 'Inter', sans-serif;
        }
    </style>
</head>
<body class="bg-gray-50 dark:bg-gray-900 transition-colors duration-500">

    <!-- Main container to center content -->
    <div class="min-h-screen flex flex-col items-center justify-center p-4">
        
        <!-- Content wrapper -->
        <div class="text-center space-y-8 max-w-2xl w-full">

            <!-- Main Title -->
            <h1 class="text-5xl md:text-6xl font-bold text-gray-800 dark:text-white">
                SENSORPROJECT01
            </h1>

            <!-- Subtitle -->
            <p class="text-lg md:text-xl text-gray-600 dark:text-gray-300">
                Transforming Sensor Data into Actionable Insights
            </p>

            <!-- Status Badges -->
            <div class="flex items-center justify-center flex-wrap gap-2">
                <span class="bg-gray-700 text-white text-sm font-medium px-3 py-1 rounded-md">
                    last commit &nbsp; <span class="font-bold text-green-400">today</span>
                </span>
                <span class="bg-blue-600 text-white text-sm font-medium px-3 py-1 rounded-md">
                    python &nbsp; <span class="font-bold">89.5%</span>
                </span>
                <span class="bg-blue-600 text-white text-sm font-medium px-3 py-1 rounded-md">
                    languages &nbsp; <span class="font-bold">3</span>
                </span>
            </div>

            <!-- "Built With" Section -->
            <div class="space-y-4 pt-6">
                <h2 class="text-md text-gray-500 dark:text-gray-400">
                    Built with the tools and technologies:
                </h2>
                
                <!-- Technology Badges -->
                <div class="flex items-center justify-center flex-wrap gap-3">
                    <span class="bg-gray-900 dark:bg-gray-200 text-white dark:text-black text-sm font-bold px-4 py-2 rounded-lg shadow-md">
                        Flask
                    </span>
                    <span class="bg-gray-200 dark:bg-gray-700 text-gray-800 dark:text-gray-200 text-sm font-bold px-4 py-2 rounded-lg shadow-md">
                        Markdown
                    </span>
                    <span class="bg-blue-500 text-white text-sm font-bold px-4 py-2 rounded-lg shadow-md">
                        Python
                    </span>
                    <span class="bg-red-500 text-white text-sm font-bold px-4 py-2 rounded-lg shadow-md">
                        YAML
                    </span>
                </div>
            </div>

        </div>
    </div>

</body>
</html>

---

## 📚 Table of Contents

- [Overview](#overview)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Testing](#testing)

---

## 🚀 Overview

`sensorproject01` is an all-in-one developer toolkit for building scalable machine learning solutions in fault detection and predictive analytics. It integrates data ingestion, preprocessing, model training, and deployment within a cohesive architecture, all accessible through a user-friendly web interface.

### 🔍 Why sensorproject01?

- **Web-based Interaction**: Easily trigger training and generate predictions via Flask web endpoints.  
- **Modular Data Pipelines**: Seamlessly ingest, transform, and manage sensor data from CSV files to MongoDB.  
- **Automated Model Training**: Experiment with multiple algorithms, tune hyperparameters, and select the best model for deployment.  
- **Robust Logging & Error Handling**: Maintain high reliability with centralized logs and detailed exception management.  
- **End-to-End Workflow**: Orchestrate data processing, model evaluation, and inference in a scalable, maintainable manner.

---

## 🛠️ Getting Started

### ✅ Prerequisites

This project requires the following dependencies:

- **Programming Language**: Python  
- **Package Manager**: pip  

---

### 📦 Installation

Build `sensorproject01` from the source and install dependencies:

```bash
# Clone the repository
git clone https://github.com/shubhamchaurasiya12/sensorproject01

# Navigate to the project directory
cd sensorproject01

# Install the dependencies
pip install -r requirements.txt

```
## 🚀 Usage

Run the project with:

```bash
python app.py
```

# 🧪 Testing
```bash
pytest tests/


