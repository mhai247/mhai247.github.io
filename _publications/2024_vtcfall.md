---
title: "LoGra: an LSTM-DDPG Integrated MPQUIC Scheduler for Mobile Video Streaming"
collection: publications
category: conferences
permalink: /publication/2024_vtcfall
excerpt: '**Minh Hai Vu**, Trung Thanh Nguyen, Thi Ha Ly Dinh, Phi Le Nguyen, Kien Nguyen'
venue: '2024 IEEE 100th Vehicular Technology Conference (VTC2024-Fall) (Accepted)'
# slidesurl: 'http://mhai247.github.io/files/vtc2024.bib'
# paperurl: 'https://ieeexplore.ieee.org/abstract/document/10454897'
---
With the increasing demand for video streaming services, efficient video streaming with MPQUIC in mobile wireless networks is gaining interest. Although MPQUIC can leverage multiple network connections (e.g., Wi-Fi, 5G) for simultaneous transfer, improving bandwidth and resilience, its performance is heavily dependent on the MPQUIC scheduler. In mobile scenarios, network fluctuations challenge the scheduler to adapt to dynamic conditions while maintaining good video streaming quality. Addressing this issue, this paper proposes a novel MPQUIC scheduler named LoGra (i.e., LSTM-DDPG integrated MPQUIC Scheduler) with two advanced features. First, LoGra utilizes Long Short-Term Memory (LSTM) to model the temporal correlation of network conditions over time and handle the challenges posed by mobility patterns. Second, it leverages the Deep Deterministic Policy Gradient (DDPG), with its self-learning capabilities and the strength of deep neural networks, to analyze the informative temporal feature vector to influence scheduling decisions. We have implemented the proposed scheduler and compared it to existing ones. The results show that the LoGra scheduler effectively manages multipath communication in heterogeneous wireless networks under mobility scenarios. Moreover, compared to existing schedulers, LoGra achieves significant improvements in data transmission, both in general metrics (loss, goodput) and streaming-related metrics (bitrate, freezing time).