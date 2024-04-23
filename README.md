## Orchestrating Mixed Precision Models on a Shared Precision-Scalable NPU

> ##### the 25th ACM SIGPLAN/SIGBED International Conference on Languages, Compilers, and Tools for Embedded Systems
> 
> _LCTES'24, June 24-28, Copenhagen, Denmark_

### Abstract
#### Under-utilization of precision-scalable NPU
Mixed-precision quantization can reduce the computational requirements of Deep Neural Network (DNN) models with minimal loss of accuracy.
As executing mixed-precision DNN models on Neural Processing Units (NPUs) incurs significant under-utilization of computational resources, Precision-Scalable NPUs (PSNPUs) which can process multiple low-precision layers simultaneously have been proposed.
However, the under-utilization still remains significant due to the lack of adequate scheduling algorithms to support multiple mixed-precision models on PSNPUs.
Therefore, in this paper, we propose a dynamic programming-based scheduling algorithm for the operations of multiple mixed-precision models.
Our scheduling algorithm finds the optimal execution plan that exploits the precision-scalable MACs to improve the end-to-end inference latency of mixed-precision models.
We evaluate the performance of this algorithm in terms of hardware utilization, inference latency, and schedule search time compared to baseline scheduling algorithms. 
The experimental results show 1.23x inference latency improvements over the baseline algorithms within the allowed minutes.

### Unleash the potential of precision-scalable NPU
#### System Overview
#### DP-based Scheduling

### Paper
- https://doi.org/10.1145/3652032.3657571

### Contact
- Kiung Jung, kiung@yonsei.ac.kr
- Seok Namkoong, seoknamkoong@yonsei.ac.kr
- Hongjun Um, hongjunum@hanyang.ac.kr
- Hyejun Kim, hyejunkim@yonsei.ac.kr
- Youngsok Kim, youngsok@yonsei.ac.kr
- Yongjun Park, yongjunpark@yonsei.ac.kr
