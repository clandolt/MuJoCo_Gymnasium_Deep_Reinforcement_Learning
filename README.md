# MuJoCo_Gymnasium_Deep_Reinforcement_Learning

This repository contains my submission in EVA Deep Reinforcement Learning in MSE Data Science.
The repository contains the automatic learning of the Humanoid Standup Task using the MuJoCo Advanced physics simulation, Gymnasium and Stable-Baselines3.

## Requirements

- Linux Operating System
- Python 3.10
- Jupyter Notebook

## Installation and Usage

Running this repository requires that you have [Python 3.10](https://www.python.org/downloads/) and [Jupyter Notebook](https://jupyter.org/install) installed. Please install both if you have not already. All cells and their outputs are saved, so it is not necessary to run the training of the agents to see their performance.

Please note that this repository is designed to be run on a Linux operating system.

1. Clone the repository:
   ```
   git clone https://github.com/clandolt/MuJoCo_Gymnasium_Deep_Reinforcement_Learning.git
   ```
   ```
   cd MuJoCo_Gymnasium_Deep_Reinforcement_Learning
   ```
2. You need to install some dependencies. Run the following commands in your terminal:
    ```bash
    sudo apt-get install -y \
        libgl1-mesa-dev \
        libgl1-mesa-glx \
        libglew-dev \
        libosmesa6-dev \
        software-properties-common
    sudo apt-get install -y patchelf
    sudo apt-get install -y libx11-dev
    sudo apt-get install -y build-essential

3. Create a virtual environment and activate it.

    ```
    python3 -m venv env
    ```
    ```
    source env/bin/activate
    ```

4. Install the requirements from the `requirements.txt` file.
    ```
    pip install -r requirements.txt
    ```

5. Start Jupyter Notebook:
   ```
   jupyter notebook
    ```

6. Open `HumanoidStandup.ipynb` and run the cells.