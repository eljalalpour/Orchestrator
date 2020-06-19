# Orchestrator

This repository implements the Orchestrator of FTC to deploy, monitor, and recover a chain of middleboxes. FTC is
a protocol to provide fault tolerance for a chain of middleboxes.
For more information about this protocol please refer to our paper [[1]](#1)

Orchestrator contains two modules. First, the Orchestrater (can be found [here](src/main/java/org/Orchestrator))
which deploys andmonitor a chain of middleboxes. In addition, it initiates the failure recovery procedure when
a middlebox fails.
Second, the Agent runs a service at a host to communicate with the orchstrator (accessable from [here](src/main/java/org/Agent)).

# References
<a id="1">[1]</a>
Milad Ghaznavi, Elaheh Jalalpour, Bernard Wong, Raouf Boutaba, and Ali Jose Mashtizadeh. Fault tolerant service function chaining. In Proceedings of the 2020 ACM Conference on Special Interest Group on Data Communication, SIGCOMM ’20, New York, NY, USA, August 2020. Association for Computing Machinery (ACM).

