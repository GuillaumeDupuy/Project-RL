# Projet-RL-Project

## About the project

The objective of this project is to implement learning algorithms by reinforcement on real-time data to simulate direct interaction between an agent and an environment.

In this project we offer you to work on wireless networks to measure the quality of transmissions between a terminal and antennas.
The project aims to analyze the state of the link and converge towards a optimal state which allows maximizing the throughput of data sent by the terminals.

### About the DashBoard

The dashboard is made with Streamlit. It allows you to visualize 3 scenarios:
- The first scenario is a simulation of the environment with a 500 terminal and 4 antennas. The simulation is done with a ANN algorithm, Policy Iteration, Thompson, EXP3 and UCB.
- The second scenario is a simulation of the environment with a 1000 terminal and 8 antennas. The simulation is done with a ANN algorithm, Policy Iteration, Thompson, EXP3 and UCB.
- The third scenario is a simulation of the environment with a 5000 terminal and 16 antennas. The simulation is done with a ANN algorithm, Policy Iteration, Thompson, EXP3 and UCB.

## Getting Started

### Installation

1. In order to use our program, you have to clone the repo :

```bash
git clone https://github.com/GuillaumeDupuy/Project-RL
cd Project-RL
```

2. Install the requirements :

```bash
pip install -r requirements.txt
```

### Execution

To execute the code, follow these steps :

1. Go to the `src/` folder :

```bash
cd src
```

2. Run the main file :

```bash
python main.py
```

## Architecture of the project

The project is composed of 3 main parts:

```
├── app/
│   └── dashboard.py
│
├── requirements.txt
│
├── res/
│   ├── clustering/
│   │   └── csv_files
│   └── csv_files
│
├── src/
│    ├── app/
│    │   ├── app.py
│    │   ├── init.py
│    │   └── qos.py
│    ├── etc/
│    │   ├── ann.py
│    │   ├── exp3.py
│    │   ├── klucb.py
│    │   ├── policy_iteration.py
│    │   ├── qlearning.py
│    │   ├── random.py
│    │   ├── thompson.py
│    │   └── ucb.py
│    ├──net/
│    │    ├── device.py
│    │    ├── gateway.py
│    │    ├── packet.py
│    │    └── server.py
│    └── main.py
```

If you wish to modify or extend the code, here's a brief overview :

- `app/` : contains the dashboard and the functions used to display the results

- `res/` : contains the csv files used to display the results

- `src/` : contains the main functions of the project

- `src/app/` : contains the functions used to display the results

- `src/etc/` : contains the functions used to run the algorithms

- `src/net/` : contains the functions used to simulate the network

Feel free to explore the code and modify it as you wish !