# Differentiate Quality of Experience scheduling for Deep Learning Applications with Docker Containers in the Cloud 

In this project, we present DQoES a differentiate quality of experience based scheduler for containerized deep learning allications. 
It enables user-specified objectives to the cloud system and attempts to meet multiple clients’ specifications in the same cluster. When deploying a learning model in the cloud, DQoES accepts a targeted QoE value from each client. This value is analyzed by DQoES, which would increase or decrease its resource limit in order to achieve the target. When multiple models reside in a cluster, DQoES is able to respect to their individual QoE objectives and approach user-specified QoEs through dynamical adjustment on the resource allocation at runtime. DQoES is implemented as a plugin to Docker Swarm. Based on extensive, cloud executed experiments, it demonstrates its capability to react to different workload patterns and achieves up to 8x times more satisfied models as compared to the existing system.
