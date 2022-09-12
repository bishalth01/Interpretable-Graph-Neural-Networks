# Graph Neural Network for Brain Network Analysis
 This is a customized implementation of of BrainGNN. We are using a private ABCD resting-state fMRI data with 53 features.
## Usage
### Setup
**pip**

See the `requirements.txt` for environment configuration. 
```bash
pip install -r requirements.txt
```
**PYG**

To install pyg library, [please refer to the document](https://pytorch-geometric.readthedocs.io/en/latest/notes/installation.html)

### Dataset 
**ABCD**

Each subject is considered as a single graph, ROI's as nodes and partial correlation strength as edges.



## Reference

This is a implementation of Interpretable Graph Neural Networks - https://www.sciencedirect.com/science/article/pii/S1361841521002784
