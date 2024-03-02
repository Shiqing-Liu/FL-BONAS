# FL-BONAS
This is the official repository of our CEC 2023 paper: [Federated Bayesian Optimization for Privacy-preserving Neural Architecture Search](https://ieeexplore.ieee.org/abstract/document/10254155)

## Keywords

Federated Learning, Bayesian Optimization, Neural Architecture Search

## Highlights

This work proposes a federated Bayesian optimization NAS approach called FL-BONAS. Instead of uploading the original weight values to the server during each round, the clients cooperatively train an ensemble surrogate model as the neural predictor, and each client searches for its own architectures via Bayesian optimization without revealing either the local raw data or the architectures. 

![image](https://github.com/Shiqing-Liu/FL-BONAS/blob/main/FL-BONAS-framework.jpg)

## Cite
```
@inproceedings{liu2023federated,
  title={Federated Bayesian Optimization for Privacy-Preserving Neural Architecture Search},
  author={Liu, Shiqing and Wang, Xilu and Jin, Yaochu},
  booktitle={2023 IEEE Congress on Evolutionary Computation (CEC)},
  pages={1--8},
  year={2023},
  organization={IEEE}
}
```
