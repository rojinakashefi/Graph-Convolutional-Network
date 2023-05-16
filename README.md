# Graph Convolutional Network Projects

### Why graphs?

1. In image we have up, down, left and right tesors and in text we have left and right words, however in graphs there is no direction.

2. Neural networks : input(graphs), output(classification, prediction and ... )

3. Feature engineering is eliminated instead we have Representation learning which automatically learn the features.

4. Map nodes to d-dimenstional embeddings, similar nodes are embedded close together.

### Applications of Graph ML

1. Node classifciation 

2. Link prediction 

3. Graph classification

4. Clustering

5. Graph generation 

6. Graph evolution

## Text classification on FHIR dataset using Graph Convolutional Network

This project focuses on applying the Text Graph Convolutional Network (Text-GCN) to the task of FHIR data classification. FHIR (Fast Healthcare Interoperability Resources) is a standard for exchanging electronic health records, developed by the Health Level Seven International organization. 

Project aims:

1. Modeling global word co-occurence using PMI

2. Modeling the relationship between document and words using TF-ID

3. Predict patients condition based on the procedure and medication based on Graph convolution networks.

![](https://github.com/rojinakashefi/GCN-Projects/blob/main/images/GCN.png)

![](https://github.com/rojinakashefi/GCN-Projects/blob/main/images/graph2.png)

**Dataset:** [FHIR dataset](https://github.com/rojinakashefi/GCN-Projects/tree/main/dataset)

**Requriements:**

1. PyTorch

**Refrences:**

[1] [Kipf & Welling, Semi-Supervised Classification with Graph Convolutional Networks, 2016](https://arxiv.org/abs/1609.02907)


## Finding Mature Language in Twitch with Label Propagation

1. Using label propagation tells who your friends are
   
   **Concepts**: Adjancey matrix, Transition Matrices, Label Propagation Algorithm
   
   **Libraries:** networkx
   
   **Dataset:** [Twitch Dataset](https://github.com/benedekrozemberczki/datasets)

## Node classification using Graph Convolutional Network

1. Learn features of Nodes using GCN
   
   Concepts: Adjancey matrix, symmetric normalizing
   
   Libraries: networkx

----

Resources : [GraphML](https://antonsruberts.github.io/graph/)
