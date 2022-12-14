This is a PyTorch implementation of the paper [Anomal-E](https://arxiv.org/pdf/2207.06819.pdf).

Abstract

This paper investigates graph neural networks (GNNs) applied for self-supervised intrusion and anomaly detection in computer networks. GNNs are a deep learning approach for graph-based data that incorporate graph structures into learning to generalise graph representations and output embeddings. As traffic flows in computer networks naturally exhibit a graph structure, GNNs are a suitable fit in this context. The majority of current implementations of GNN-based network intrusion detection systems (NIDSs) rely on labelled network traffic. This limits the volume and structure of input traffic and restricts the NIDSs’ potential to adapt to unseen attacks. These systems also rely on the use of node features, which may reduce the detection accuracy of these systems, as important edge (packet-level) information is not leveraged. To overcome these restrictions, we present Anomal-E, a GNN approach to intrusion and anomaly detection that leverages edge features and a graph topological structure in a self-supervised manner. This approach is, to the best of our knowledge, the first successful and practical approach to network intrusion detection that utilises network flows in a self-supervised, edge-leveraging GNN. Experimental results on two modern benchmark NIDS datasets display a significant improvement when using Anomal-E compared to raw features and other baseline algorithms. This additionally posits the potential Anomal-E has for intrusion detection on real-world network traffic.



## Prerequisites

- [Pytorch](http://pytorch.org/)
- [DGL](https://www.dgl.ai/)


### If you think this work is helpful, please cite
```latex
@article{caville2022anomal,
  title={Anomal-E: A self-supervised network intrusion detection system based on graph neural networks},
  author={Caville, Evan and Lo, Wai Weng and Layeghy, Siamak and Portmann, Marius},
  journal={Knowledge-Based Systems},
  volume={258},
  pages={110030},
  year={2022},
  publisher={Elsevier}
}
```
