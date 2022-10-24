# RL-IoT
RL-IoT
In information systems, the presence of IoT devices is exponentially growing and
most of them are custom devices: they rely on proprietary protocols, often closed or poorly documented. Here we want to interact with such devices, by learning their protocols in an autonomous manner.
● Goal:
In the referenced paper, the author proposes RL-IoT, a system that explores how to automatically interact with possibly unknown IoT devices. Leveraging reinforcement learning to recover the semantics of protocol messages and to take control of the device to reach a given goal, while minimizing the number of interactions. Assume we know only a database of possible IoT protocol messages, whose semantics are however unknown. RL-IoT exchanges messages with the target IoT device, learning those commands that are useful to reach the given goal. A Yeelight smart bulb is in the case study.
