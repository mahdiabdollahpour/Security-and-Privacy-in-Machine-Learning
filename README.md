# Security and Privacy in Machine Learning


## Adversarial Malware Generator
  MalwareDetector.py detects malware by CNN on bytes, Adversarial_Malware_Generator.py generates an adversarial malware by appending some bytes at the end and perturbating them. Malware_DoNotExecute.exe is a malware to create adversarial example from.

## Evasion Attack and Defense
  Working around targeted and non-targeted Random noise attack, FGSM [Explaining and Harnessing Adversarial Examples](https://arxiv.org/pdf/1412.6572.pdf) and PGD [Towards Deep Learning Models Resistant to Adversarial Attacks](https://arxiv.org/pdf/1706.06083.pdf) and measuring their success rate against FGSM/PGD adversarial traning.
##  JBDA Model Stealing and Obfuscated Gradients
 Jacobian-based Dataset Augmentation from [Practical Black-Box Attacks against Machine Learning](https://www.cs.purdue.edu/homes/bb/2020-fall-cs590bb/docs/at/attacks-against-machine-learning.pdf) to approximate a surrogate model to use its gradients for atatck on target model which has obfuscated gradients defense machanism. Black-box attacks peforms better than white-box as already said in [Obfuscated Gradients Give a False Sense of Security:
Circumventing Defenses to Adversarial Examples
](https://arxiv.org/pdf/1802.00420.pdf)
 
## Membership Inference Attack
  A quick touch on [Membership Inference Attacks Against Machine Learning Models](https://www.cs.cornell.edu/~shmat/shmat_oak17.pdf), good inefrence rate was possible with only two shadow models on CIFAR10.
  
## Poisoning Attack
 Poisoning Attacks based on [Poison Frogs! Targeted Clean-Label Poisoning Attacks on Neural Networks](https://arxiv.org/pdf/1804.00792.pdf).
