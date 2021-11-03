# Paper Reading

## Prototypical Networks for Few-shot Learning. arxiv, 2017 [pdf](https://arxiv.org/pdf/1703.05175.pdf)

### Introduction: 

Few-shot classification: a task in which a classifier must be adapted to accommodate new classes not seen in training, given only a few examples of each of these classes.
  - Art of Works:
    - Vinyals et al.[1]: Matching networks, a weighted nearest-neighbor classifier applied within an embedding space.
    - Ravi and Larochelle[2]: training an LSTM [3] to produce the updates to a classifier. Here, rather than training a single model over multiple episodes, the LSTM meta-learner learns to train a custom model for each episode.
 - Key Issue: overfiting.
 - Approach: prototypical networks, is based on the idea that there exists an embedding in which points cluster around a single prototype representation for each class.

### Prototypical Networks

  

### References
[1]Oriol Vinyals, Charles Blundell, Tim Lillicrap, Daan Wierstra, et al. Matching networks for one shot learning. In Advances in Neural Information Processing Systems, pages 3630–3638, 2016. 

[2]SachinRaviandHugoLarochelle.Optimizationasamodelforfew-shotlearning.InternationalConference on Learning Representations, 2017.

[3]SeppHochreiterandJürgenSchmidhuber.Longshort-termmemory.NeuralComputation,9(8):1735–1780, 1997.