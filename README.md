<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SENSORPROJECT01 README</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        /* Custom styles for badges, not easily done with simple Tailwind classes */
        .badge {
            display: inline-flex;
            align-items: center;
            padding: 0.25rem 0.75rem;
            border-radius: 0.375rem; /* Slightly rounded corners for badges */
            font-size: 0.875rem;
            font-weight: 600;
            margin: 0.25rem;
            color: white;
        }
    </style>
    <script>
        // Optional: Script to manually toggle dark mode for testing if preferred-color-scheme doesn't work directly in some viewers
        // This is not strictly necessary for the 'dark:' variant to work based on system preferences,
        // but can be added for a user-controlled toggle.
        // For actual system preference detection, Tailwind's 'dark:' variant automatically handles it.
        // You can uncomment and modify this if you want a manual switch.
        /*
        if (localStorage.theme === 'dark' || (!('theme' in localStorage) && window.matchMedia('(prefers-color-scheme: dark)').matches)) {
            document.documentElement.classList.add('dark')
        } else {
            document.documentElement.classList.remove('dark')
        }
        */
    </script>
</head>
<body class="bg-gray-100 dark:bg-gray-900 flex justify-center items-start min-h-screen p-8 box-border font-inter">
    <div class="container bg-white dark:bg-gray-800 p-10 rounded-xl shadow-lg max-w-3xl w-full text-center">
        <!-- Main Title -->
        <h1 class="text-5xl font-extrabold text-gray-800 dark:text-gray-100 mb-6 tracking-wide">
            SENSORPROJECT01
        </h1>

        <!-- Subtitle -->
        <p class="text-2xl italic text-gray-600 dark:text-gray-300 mb-10">
            Transforming Sensor Data into Actionable Insights
        </p>

        <!-- GitHub-like Badges -->
        <div class="flex flex-wrap justify-center items-center mb-10">
            <span class="badge bg-gray-700">last commit <span class="ml-1 bg-blue-500 rounded px-2 py-0.5">today</span></span>
            <span class="badge bg-blue-600">python <span class="ml-1 bg-blue-800 rounded px-2 py-0.5">89.5%</span></span>
            <span class="badge bg-gray-700">languages <span class="ml-1 bg-blue-500 rounded px-2 py-0.5">3</span></span>
        </div>

        <!-- Built With Section Title -->
        <p class="text-xl italic text-gray-700 dark:text-gray-300 mb-8">
            Built with the tools and technologies:
        </p>

        <!-- Tool Badges -->
        <div class="flex flex-wrap justify-center items-center gap-4">
            <span class="badge bg-black text-white">
                <svg class="w-4 h-4 mr-1" fill="currentColor" viewBox="0 0 20 20"><path d="M10 2a8 8 0 100 16 8 8 0 000-16zM8 7a1 1 0 11-2 0 1 1 0 012 0zm5 0a1 1 0 11-2 0 1 1 0 012 0zM5.5 12c.745 2.146 3.125 3.5 4.5 3.5s3.755-1.354 4.5-3.5H5.5z"></path></svg>
                Flask
            </span>
            <span class="badge bg-gray-800 text-white">
                <svg class="w-4 h-4 mr-1" fill="currentColor" viewBox="0 0 20 20"><path d="M16 10a6 6 0 11-12 0 6 6 0 0112 0zm-2 0a4 4 0 10-8 0 4 4 0 008 0zm-4 4a2 2 0 100-4 2 2 0 000 4z"></path></svg>
                Markdown
            </span>
            <span class="badge bg-blue-600 text-white">
                <svg class="w-4 h-4 mr-1" fill="currentColor" viewBox="0 0 20 20"><path d="M10 2a8 8 0 100 16 8 8 0 000-16zM8 7a1 1 0 11-2 0 1 1 0 012 0zm5 0a1 1 0 11-2 0 1 1 0 012 0zM5.5 12c.745 2.146 3.125 3.5 4.5 3.5s3.755-1.354 4.5-3.5H5.5z"></path></svg>
                Python
            </span>
            <span class="badge bg-red-600 text-white">
                <svg class="w-4 h-4 mr-1" fill="currentColor" viewBox="0 0 20 20"><path d="M10 2a8 8 0 100 16 8 8 0 000-16zM8 7a1 1 0 11-2 0 1 1 0 012 0zm5 0a1 1 0 11-2 0 1 1 0 012 0zM5.5 12c.745 2.146 3.125 3.5 4.5 3.5s3.755-1.354 4.5-3.5H5.5z"></path></svg>
                YAML
            </span>
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


