# RCLSTM (Deep learning with long short-term memory for time series prediction)

The codes are consistent with the following paper:
Y. Hua, Z. Zhao, R. Li, X. Chen, Z. Liu, and H. Zhang, “Deep learning with long short-term memory for time series prediction,” *IEEE Commun. Mag.*, vol. 57, no. 6, pp. 114–119, Jun. 2019, doi: 10.1109/MCOM.2019.1800155.

We are sharing the codes under the condition that reproducing full or part of codes must cite the paper. 

## Abstract of the paper
Time series prediction can be generalized as a process that extracts useful information from historical records and then determines future values. Learning long-range dependencies that are embedded in time series is often an obstacle for most algorithms, whereas LSTM solutions, as a specific kind of scheme in deep learning, promise to effectively overcome the problem. In this article, we first give a brief introduction to the structure and forward propagation mechanism of LSTM. Then, aiming at reducing the considerable computing cost of LSTM, we put forward a RCLSTM model by introducing stochastic connectivity to conventional LSTM neurons. Therefore, RCLSTM exhibits a certain level of sparsity and leads to a decrease in computational complexity. In the field of telecommunication networks, the prediction of traffic and user mobility could directly benefit from this improvement as we leverage a realistic dataset to show that for RCLSTM, the prediction performance comparable to LSTM is available, whereas considerably less computing time is required. We strongly argue that RCLSTM is more competent than LSTM in latency-stringent or power-constrained application scenarios.
