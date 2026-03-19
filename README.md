This project is conducted by a graduate student from Huazhong University of Science and Technology (HUST), China. The goal of this project is to investigate and develop a zero-shot cost model for parallelism tuning in distributed stream processing systems.

We plan to deploy Apache Flink on CloudLab clusters and conduct controlled experiments to evaluate the effectiveness of the proposed model. CloudLab provides a stable, reproducible, and configurable cluster environment, which is essential for fair and systematic performance evaluation.

Specifically, we will use hardware configurations similar to prior work (e.g., m510, c6420, and rs620 nodes), and reproduce experimental settings from existing studies such as ZeroTune (ICDE 2024), including query workloads and evaluation metrics (latency, throughput, and Q-error). This ensures that our results are directly comparable with prior approaches.

The research focuses on:
- Designing graph-based representations of streaming jobs (e.g., operator DAGs) to better capture query structure and resource allocation.
- Developing efficient data collection and training strategies to reduce the amount of required training samples.
- Building and evaluating a cost model that can generalize to unseen workloads and cluster configurations for parallelism optimization.

The experiments will involve repeated deployment of Flink clusters, workload execution, and performance measurement across different configurations. All resources will be used solely for academic research and system evaluation, in full compliance with CloudLab’s acceptable use policy.
