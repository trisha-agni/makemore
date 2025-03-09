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
- Probability distribution: gives the probabilities of all possible outcomes
- Likelihood: product of all individual parameter probabilities
  - Log-likelihood is often easier to work with

AI:
- Special start and end characters
  - Ex: "." + word + "."
  - Tells model the starting and ending points of each word
- One-hot encoding: used to eliminate ordinality of inputs
