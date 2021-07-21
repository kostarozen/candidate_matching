## Matching candidates to positions ##
The goal of this project is to automatically find best candidates for every job / position.
I first train an experience embedding model (in "Experience Embedding Training" notebook), and then use this pre-trained model in order to the find best matches for every position.
The match is based on degree level, years of experience and experience matching (that is done using cosine similarity of embeddings of the positions and of candidates).
