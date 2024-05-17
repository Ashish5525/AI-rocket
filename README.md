# AI-rocket

This project implements a Deep Q-Learning (DQN) agent to control a lunar lander in the "LunarLander-v2" environment from OpenAI's Gymnasium. The goal is to train an AI agent capable of safely landing the lunar module between two flags on the moon.

## Installation

1. **Clone the repository:** ```git clone https://github.com/yourusername/deep-q-learning-lunar-lander.git
cd deep-q-learning-lunar-lander```

2. **Install the required packages:**
- `pip install gymnasium`
- `pip install "gymnasium[atari, accept-rom-license]"`
- `apt-get install -y swig`
- `pip install "gymnasium[box2d]"`
- `pip install torch numpy matplotlib imageio`

## Usage

1. **Run the Colab Notebook:**

Open the provided Google Colab notebook or run the script directly on your local machine to train the DQN agent.

`python train.py`

## Training the agent:
To train the DQN agent, execute the following command: `python train.py`

The script will initialize the environment, set up the DQN agent, and begin the training process. The training progress and average scores will be displayed in the console.

## Visualizing the Results

After training, generate and view a video of the trained agent by running: `python visualize.py`

This script will create a video of the trained agent performing in the "LunarLander-v2" environment.

## Outcome:

https://github.com/Ashish5525/AI-rocket/assets/70592535/033df0bb-533e-4b98-bc73-f9b1a3dda229


https://github.com/Ashish5525/AI-rocket/assets/70592535/8987c6b8-a508-453a-a05d-b9e122fb6408



