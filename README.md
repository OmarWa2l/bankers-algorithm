# Banker's Algorithm using pyqt5

This project is an implementation of the Banker's algorithm using a graphical user interface (GUI). The Banker's algorithm is a resource allocation and deadlock avoidance algorithm used in operating systems. It allows processes to request resources without causing deadlock, by checking whether granting the request would leave the system in a safe state.

The GUI allows users to interact with the Banker's algorithm and visualize the state of the system. The GUI  shows the current state of the system, including the available resources and the maximum resources required by each process. The user can add procces request

## Getting started

To use this project, you will need to have Python 3 and the PyQt5 library installed on your system. You can install PyQt5 using pip:

```
pip install PyQt5
```

Once you have the necessary dependencies, you can run the program by running the `rawcode.py` script:

```
python rawcode.py
```

## Usage

When you run the `rawcode.py` script, a window will appear showing the current state of the system. You can use the following controls to interact with the system:

- **input the number of resources and processes**: Click the "generate" button to intialize the tables. You have to enter the maximum resource requirements for the process before pressing the "generate button.
- ![Main GUI](/images/1.png "Main GUI")
- **Filling the max ,Allocation and total tables**: put the numbers for each mentioned table then press"enter" button.
- **user entry**:user can add additional resource request by giving the procces and resource id and the amount of process needed then press the "user entry" button.
- **press enter**:press enter button to update the need and avalaible table to be ready to check the system after the user entry input(you can skip this step if u skipped the previous one).
- **the system state and the safe sequence**: Simply press "check" button to show the results.

The GUI will update to show the new state of the system after each action.


