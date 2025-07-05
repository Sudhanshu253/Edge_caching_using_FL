# Device Selection and Data Offloading for Edge Caching in a Federated Learning Framework
This project delivers an optimization-based solution to enhance edge caching efficiency in a Federated Learning (FL) setup. It selects a resource-aware subset of edge devices for each training round to reduce communication costs, while enabling data offloading from idle devices to improve training quality. The framework is designed with real-world constraints in mind, including energy consumption, latency, and device storage capacity.

## Key Components
Federated Learning Setup: Simulated a resource-constrained FL environment using the TensorFlow Federated (TFF) framework.

Optimization Problem: Formulated and solved a device selection and data offloading problem using the CVXPY library.

Content Interaction Modeling: Constructed content request matrices using the MovieLens 1M dataset to capture user-content interaction patterns.

Resource Constraints: Incorporated system-level constraints such as energy, latency, and storage in the optimization formulation.

Planned Work: Designing a scalable framework to support intelligent device selection and adaptive caching strategies at the edge.

## Objectives
To enhance the efficiency of FL by minimizing communication overhead through selective device participation.

To improve caching decisions by leveraging offloaded data from non-selected devices, thereby boosting content diversity and learning quality.

## Technologies Used
Python

TensorFlow Federated

NumPy, Pandas

CVXPY

Matplotlib

## Outcome
Lays the foundation for a scalable and resource-efficient federated learning framework, capable of improving both model accuracy and content availability at the network edge.
