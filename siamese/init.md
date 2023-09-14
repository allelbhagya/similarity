## what are siamese networks?

- neural network architecture primarily used in computer vision and similarity learning
- designed to determine the similarity or dissimilarity between pairs of data points
- idea: two identical sub networks(twins) will share same arch and weights
- subnetworks process two input data points simultaneously and produce embeddings/vector representations for each input
- compared to measure similarity 

## how they work?

- dual sub networks: same arch; images, text, other data
- feature extraction: passed through sub networks to extract meaningful features
- distance calculation: using euclidean, manhattan distance, cosine similarity
- loss function: contrastive loss/ triplet loss.
