# Ohtu, Autum 2022 - Transpilation methods for quantum computers

## About the project:
 
The goal of the project was to create a transpiler for quantum circuits based on the research of Arianne Meijer-van de Griend. The goal of the project was to implement a client's Steiner Tree-based compilation method to the IBM's [Qiskit Library](https://github.com/Qiskit).

### PermRowColSynthesis Transpiler

The client's research is focused on the efficient compilation methods of qubits in quantum circuits. The algorithm PermRowCol is designed to run a certain quantum circuit under those constraints, the qubits need to be re-allocated to adequate registers and multi-qubit operations need to be re-routed. In quantum computing, more there are gates, more there is a risk of producing inaccurate results.

Currently in use is SWAP-based methods, but PermRowCol uses a bridge template, which results in fewer CNOTs, and thus reduces the risk of inaccuracies in quantum computing.



#### Research paper

[Meijer-van de Griend, A & Li, S M 2022, 'Dynamic Qubit Allocation and Routing for Constrained Topologies by CNOT Circuit Re-synthesis'](https://arxiv.org/pdf/2205.00724.pdf)

### Links:

[Groups fork/woking GitHub repository](https://github.com/Helsinki-Qubits/qiskit-terra)

[Product Backlog](https://helsinkifi-my.sharepoint.com/:x:/g/personal/millakel_ad_helsinki_fi/EXi4j8V7nzRDk9hke33-PnQBdSgH0LGj_gx1z-O67_ME9g?e=ECd0pN)

[Sprint Backlog](https://helsinkifi-my.sharepoint.com/:x:/g/personal/millakel_ad_helsinki_fi/EeZEZVaocW9JlxgAM4hoWEAB5jBttrr-e5zZI2D5XtpHEg?e=3urt0Z)

[Qiskit homepage](https://qiskit.org/)



## Documentation:

[DoD](https://github.com/Helsinki-Qubits/Ohtu-A2022-Transpilation_methods_for_quantum_computers/blob/main/Documentation/DoD.md)

[User-DoD](https://github.com/Helsinki-Qubits/Ohtu-A2022-Transpilation_methods_for_quantum_computers/blob/main/Documentation/User-DoD.md)


## How the project was executed by the group:

The project was executed by using scrum -methods. In such, the time was devided on sprints, where the time differs between from a week to two weeks, depending on the nature of the tasks, and the clients wishes; in the begining of the project the lenght of the sprints were one week, changing into two weeks, and shifting back to one in the end of the project. Each sprint started with client meeting where group presents the progress of the project to the client, and after discussing on upcoming tasks. Afterwrds group held the sprint review, and sprint planning for the next sprint.

Group kept two to three daily meetings in a week, usually keeping a another "planning" meeting right after. In these, group discussed what they have achieved between the daily meetings, and if there were any identified blockers. With this, group got to seize the knowledge of each group member, and by working together got many difficult parts onwards.

Group members haven't got much of an experience on operating projects with using scrum methods, but got usefull experience. 

Group worked in english.


### Implementing code:

Group decided to work on one main separating those into smaller branches for each task, merging those with main after the code has been validated. In start of the project, group decided there should be at least three members who has reviewed the pull request, but later decided to lower it into two. Also client was added to be able to see the requests as well, and be able to give comments on the code to make process go forward more easier.
