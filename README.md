# MGAfold
RNA Secondary Structure Prediction Method Based on Multi-objective Genetic Algorithm
This repository is associated with our submission "MGAfold: A Novel RNA Secondary Structure Prediction Method Based on Multi-objective Genetic Algorithm and Deep Learning"

'''mermaid
      graph LR
      A[RNA sequence data] --> B[Bi-LSTM]
      B --> C[Dot-bracket representation of RNA secondary structure]
      C --> D[Multi-objective Genetic Algorithm]
      D --> E[Subsequence partitioning]
      E --> F[Calculate fitness functions]
      F --> G[Population creation]
      G --> H[Individual selection]
      H --> I[Crossover]
      I --> J[Mutation]
      J --> K[Optimal solution]
      K --> L[RNA secondary structure prediction result]
'''
