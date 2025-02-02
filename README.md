# AnomaLLMy

AnomaLLMy transforms Industrial Control Systems (ICS) network security by using Local Large Language Models (LLMs) to detect and analyze anomalous connections. This tool automates the process of interpreting network data, identifying potential threats, and generating actionable reports for cybersecurity teams.

## Setup

Follow these steps to set up your environment for AnomaLLMy:

### Prerequisites

- Python 3.11 or higher
- Git
- Jupyter Lab

### 1. Create a directory for the project:

```bash
mkdir AnomaLLMy-project
cd AnomaLLMy-project
```

### 2. Create a virtual environment:

```bash
python3 -m venv AnomaLLMy-venv
```

### 3. Clone the AnomaLLMy repository:

```bash
git clone https://github.com/IAES-Repo/AnomaLLMy.git
```

### 4. Activate the virtual environment:

On Windows:

```bash
AnomaLLMy-venv\Scripts\activate
```

On macOS and Linux:

```bash
source AnomaLLMy-venv/bin/activate
```

### 5. Navigate to the project directory and install dependencies:

```bash
cd AnomaLLMy
pip install -r requirements.txt
```

## Ollama Installation

To use LLMs with AnomaLLMy, you need to install Ollama. Follow these steps:

Download the installer from the [Ollama website](https://ollama.com/download) and follow the installation instructions.

### Verify the installation:

```bash
ollama --version
```

## Ollama Models

To use specific models with AnomaLLMy, follow these steps:

### Download the required models:

Visit the [Ollama Models Repository](https://ollama.com/models) and download the models you need.


