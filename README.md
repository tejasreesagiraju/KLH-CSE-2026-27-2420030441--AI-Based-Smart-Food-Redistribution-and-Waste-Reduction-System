# Software-Defined Factory Controller Using Distributed RT Linux

## Project Title

**Software-Defined Factory Controller Using Distributed RT Linux**

## Team Members

| S. No. | Name                           | Roll Number |
| ------ | ------------------------------ | ----------- |
| 1      | Tejasree                       | 2420030441  |
| 2      | Kongara Deepthi                | 2420030484  |
| 3      | Thirumala Reddy Sagar Mounitha | 2420030330  |
| 4      | Shalini . Ch                   | 2420030284  |

## Supervisor

**Supervisor Name:** Dr Archana Kalidindi

## Abstract

The project focuses on developing a **software-defined factory controller** for an automated conveyor-based sorting process using **Distributed Real-Time Linux (RT Linux)**. The system divides the factory control functions into separate software nodes for conveyor control, object detection, and sorting operations.

Each node performs a specific control task and communicates with other nodes to coordinate the complete process. RT Linux is used to provide predictable and time-sensitive execution of control operations. The proposed system is designed as a **software-based simulation**, eliminating the need for physical hardware while demonstrating how distributed real-time control can be implemented for industrial automation.

## Objectives

* Develop a software-defined controller for an automated factory sorting process.
* Implement distributed control using separate RT Linux nodes.
* Simulate conveyor, object detection, and sorting operations.
* Enable communication between distributed control nodes.
* Process sensor inputs and generate machine-control commands in real time.
* Demonstrate predictable and coordinated operation of an industrial automation process.

## Technologies Used

* Linux / RT Linux
* Python / C / C++ *(as applicable)*
* Inter-process or network communication
* Git and GitHub
* VS Code
* Software-based factory simulation

## Repository Structure

```text
├── .gitignore
├── README.md
│
├── src/
│   └── Source code
│
├── docs/
│   └── Project documentation
│
├── data/
│   └── Dataset or documented data source
│
├── results/
│   └── Execution results and outputs
│
└── reports/
    └── Review reports and project reports
```

## Setup Instructions

### 1. Clone the Repository

```bash
git clone <REPOSITORY_URL>
cd <REPOSITORY_NAME>
```

### 2. Install Required Dependencies

Install the required software and libraries according to the project implementation.

### 3. Run the Project

Navigate to the `src` directory and execute the appropriate controller programs.

```bash
cd src
```

Then run the required modules according to the project configuration.

## Execution

The system consists of distributed software components representing:

1. **Conveyor Node** – controls the movement of objects.
2. **Detection Node** – detects and classifies incoming objects.
3. **Sorting Node** – determines the appropriate sorting action.
4. **Communication Layer** – enables coordination between the distributed nodes.

The nodes communicate with each other to perform the complete automated sorting process.

## Current Phase Status

**Current Phase:** Review 1

**Status:** Project definition, problem statement, objectives, literature survey, research gap, innovation, feasibility analysis, and initial project planning completed.

### Upcoming Work

* Implement the distributed RT Linux nodes.
* Establish communication between nodes.
* Develop the software-based conveyor and sorting simulation.
* Test real-time communication and control.
* Evaluate system performance.
* Prepare subsequent review and final deliverables.

## Project Deliverables

* Project documentation
* Source code
* Simulation results
* Review reports
* Final project report

## GitHub Contribution Policy

All team members contribute using their **individual GitHub accounts**. Progressive commits are maintained throughout the project, with meaningful commits made regularly.

Phase deliverables will be tagged appropriately, such as:

```text
review-1
review-2
final
```

## Important Note

No passwords, API keys, credentials, licensed datasets, or confidential institutional data should be uploaded to this repository.

---

**Academic Year:** 2026–2027
