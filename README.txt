Description: In this project I have implemented a character-level language model.

What I learned:

Python:
- lambda function: used to sort bigrams based on number of occurrences
- enumerate(): iterate an index with the list item
- zip(): combine multiple iterables into a single iterable of tuples
- Libraries:
  - Torch
    - Used to create a 2D array containing counts of the bigrams
    - Tensors: primary data structure in torch
    - torch.multinomial: used to sample a letter's index based on a probability distribution
    - Broadcasting: stretching the smaller tensor's shape to match the larger tensor's shape

Math:
- Probability distribution
- Maximum likelihood estimation
  - Likelihood: product of all individual parameter probabilities

AI:
- Special start and end characters (add more later)
