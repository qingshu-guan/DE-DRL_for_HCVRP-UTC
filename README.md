# Dynamic Embedding-based Deep Reinforcement Learning for Heterogeneous Capacitated VRPs with Unloading Time Constraints
Abstract: Capacitated vehicle routing problems (CVRPs) have garnered growing attention due to their extensive applications across various fields. However, existing deep reinforcement learning (DRL) approaches often cope with homogeneous vehicle fleets, failing to account for differences in vehicle capacities and speeds. Moreover, these methods typically overlook the real-life constraint of unloading time, where vehicles cannot depart until all goods are delivered. These limitations intrinsically restrict their practical applications.
To address these issues, we introduce a heterogeneous CVRP with unloading time constraints (HCVRP-UTC) and propose a dynamic embedding-based DRL (DE-DRL) for tackling it. Our approach leverages an innovative encoder-updater-decoder (EUD) framework. Specifically, the encoder generates feature embeddings for both customer nodes and heterogeneous vehicles, while the updater iteratively refines these embeddings, incorporating both static customer data and dynamic vehicle information, to capture the real-time state variation and provide sufficient clues for decision-making. Subsequently, the decoder decouples the complicated problem into a series of recursive vehicle-selection and vehicle-specific node-selection tasks, enhancing the precision and efficiency of route planning. 
Finally, we evaluate the proposed approach on both synthetic and real-world datasets of varying scales and distributions. Experimental results demonstrate that our DE-DRL consistently outperforms heuristic and state-of-the-art DRL-based methods, reducing optimality gaps by up to 13.53\%. Notably, DE-DRL also exhibits superior generalization performance, extending its applicability to broader real-world scenarios.

## Paper
This paper is submitted to Expert Systems With Applications.

## Highlights
1. A practical and challenging HCVRP-UTC is concerned and formulated.
2. A dynamic embedding-based deep reinforcement learning approach is proposed to tackle HCVRP-UTC.
3. An innovative encoder-updater-decoder framework is designed for sequential decision-making.
4. Promising performance is achieved on both synthetic and real-world datasets.

## Dependencies
1. Python>=3.7
2. NumPy
3. SciPy
4. PyTorch=1.3.0
5. tqdm
6. tensorboard_logger
7. Matplotlib (optional, only for plotting)

## Details
For more details, please see the fleet_v3 and fleet_v5 for HCVRP with three vehicles and five vehicles, respectively.
