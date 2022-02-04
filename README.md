# Graph Learning Meetings

# 4/15/2022, lead: Koby 

## Agenda

- TBD


# 4/1/2022, lead: Alok 

## Agenda

- High-performance graph sampling for GNN training
- https://arxiv.org/pdf/2009.06693.pdf

# 3/18/2022, lead: Can and Nick S. 

## Agenda

- Numerical optimization for GNN training
- Parallelization of the new optimization method


# 3/4/2022, lead: Yu-Hang

## Agenda

- Model compression (low rank, etc) for neural networks 


# 2/18/2022, lead: Vivek and Aydin

## Agenda

- SIGN (Scalable Inception Graph Neural Networks)
- https://arxiv.org/abs/2004.11198

- OGB large-scale challenge
- https://arxiv.org/abs/2103.09430
- https://ogb.stanford.edu/kddcup2021/


# 2/4/2022, lead: all

## Agenda

- Organizational meeting


# 12/2/2021, lead: Andrew

## Agenda

- Hyperbolic embeddings
- https://arxiv.org/pdf/1804.03329.pdf

- And here's a good introduction to the paper from the authors
https://dawn.cs.stanford.edu/2018/03/19/hyperbolics/

- You should only need to understand the Poincaré disk, which the above resources cover. But, if you want some more background on hyperbolic geometry, this book chapter is good:
http://library.msri.org/books/Book31/files/cannon.pdf

- For those curious to know more about hyperbolic neural networks, here are some more papers on this topic

- Hyperbolic NNs:
https://arxiv.org/abs/1805.09112

- Fully hyperbolic NNs i.e. no tangent space projection:
https://arxiv.org/abs/2105.14686

- Hyperbolic attention networks. I haven't read this yet, but it would be remiss of me not at least mention something about attention
https://arxiv.org/abs/1805.09786


# 10/29/2021, lead: Yu-Hang.

## Agenda

- Equivariant GNNs:
- https://arxiv.org/abs/2102.09844


# 8/20/2021, lead: Nick S.

## Agenda

- Alphafold2 or Baker Lab variant:
- https://www.nature.com/articles/s41586-021-03819-2
- https://science.sciencemag.org/content/early/2021/07/14/science.abj8754.full


# 8/6/2021, lead: Koby

## Agenda

- Graphs, simplicial complexes, and hypergraphs for data modeling: https://arxiv.org/abs/2006.02870
- and hypergraph learning: https://vision.cornell.edu/se3/wp-content/uploads/2014/09/icml06.pdf


# 7/16/2021, lead: Aydin

## Agenda

- A General Graph Neural Network Framework for Link Prediction: https://arxiv.org/pdf/2106.06935.pdf
- Path Problems in Networks: https://user.eng.umd.edu/~baras/publications/Books/S00245ED1V01Y201001CNT003.pdf


# 7/9/2021, lead: Aditi and Nick

## Agenda

- Ensemble learning


# 5/7/2021, lead: Yu-Hang

## Agenda

- Graph Neural Tangent Kernels: https://openreview.net/pdf/dd6097df468d83341c8f74f3a83470866d994965.pdf


# 4/30/2021, lead: Aydin

## Agenda

- Weisfeiler-Leman Heuristic and associated Graph Kernels: https://www.jmlr.org/papers/volume12/shervashidze11a/shervashidze11a.pdf


# 4/16/2021, lead: Prashant

## Agenda
 
- Graph Attention Networks: https://arxiv.org/abs/1710.10903

# 3/12/2021, lead: Aditi

## Agenda
 
- Topological Graph Neural Networks: https://arxiv.org/pdf/2102.07835.pdf


# 2/26/2021, lead: Nick B.

## Agenda
 
- MSA Transformer: https://www.biorxiv.org/content/10.1101/2021.02.12.430858v1.full.pdf

# 2/12/2021, lead: Nick S.

## Agenda
 
- Learning from Protein Structure with Geometric Vector Perceptrons: https://openreview.net/forum?id=1YLJDvSx6J4


# 1/29/2021, lead: none

## Agenda 

- How Neural Networks Extrapolate: From Feedforward to Graph Neural Networks https://openreview.net/forum?id=UH-cmocLJC

## Minutes

- Solving a series of successively harder DP problems with GNNs.
  * Needleman-Wunsch on pairs of reads
  * Smith-Waterman on pairs of reads
  * Sequence to graph alignment (potentially useful for pangenomes)
  * Many-to-many sequence alignment
  * Assembly on error-free reads
  * Assembly on erroneous reads


# 1/15/2021, lead: none
## Agenda 

- https://www.reddit.com/r/MachineLearning/comments/kqazpd/d_why_im_lukewarm_on_graph_neural_networks/
- https://towardsdatascience.com/predictions-and-hopes-for-graph-ml-in-2021-6af2121c3e3d
- Combining Label Propagation and Simple Models out-performs Graph Neural Networks: https://openreview.net/forum?id=8E1-f3VhX1o

## Minutes

- Discussion on GNNs vs CNNs, Transformers vs GNNs, and whether we need any induction bias. 
- Discussion on whether the test cases in the Correct&Smooth paper are too simple. 
- Discussion on whether the proposed C&S model is any easier to tune and/or run compared to GNNs. 
- We also talked about the issues with the authors' understanding of the topic in the Reddit post
- Paper for potential future reading: https://arxiv.org/pdf/1806.01261.pdf



