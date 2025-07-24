
### ✅ `README.md`

````markdown
# Deep Q-Learning Agent for Traffic Signal Control

> 🛠️ This repository is a modified version of the original implementation by [Andrea Vidali](https://github.com/AndreaVidali/Deep-QLearning-Agent-for-Traffic-Signal-Control).  
> Changes were made to simplify usage and improve setup for local testing and educational purposes.

## Project Overview

This project implements a Deep Q-Learning agent to optimize traffic signal control in a four-way intersection scenario. The simulation environment is built using the SUMO traffic simulator, and the learning model is developed in Python using TensorFlow and OpenAI Gym-like interfaces.

---

## Quick Setup

```bash
# Clone this repository
git clone https://github.com/vik090/deep-Q-Learning-Agent-for-Traffic-signal-Control.git
cd deep-Q-Learning-Agent-for-Traffic-signal-Control

# Create and activate virtual environment
python -m venv venv
venv\Scripts\activate     # On Windows

# Install dependencies
pip install -r requirements.txt

# Run training script
python training_main.py
````

---

## Requirements

Install SUMO and ensure it's available in your PATH. Then install Python dependencies using:

```bash
pip install -r requirements.txt
```

---

## Project Structure

```
.
├── README.md
├── training_main.py
├── test_model.py
├── generator.py
├── model/
│   ├── model.py
│   └── ...
├── tools/
│   ├── utils.py
│   └── ...
├── episodes/
│   └── ...
└── requirements.txt
```

---

## How It Works

1. Vehicles are generated and routed in a simulated traffic intersection using SUMO.
2. The environment is built to simulate the state, actions, and rewards of a traffic controller.
3. A Deep Q-Learning model is trained to select optimal light signals that reduce waiting times and congestion.

---

## Author

* **Pothula Vikram** – *Adapted and maintained*
* Based on original work by **Andrea Vidali** – University of Milano-Bicocca

---

## License

MIT License. See [LICENSE](LICENSE) for more information.
