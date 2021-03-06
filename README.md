# Maximising Robustness and Diversity for Improving the Deep Neural Network Safety

![image](https://user-images.githubusercontent.com/29665874/156284104-9d21d5b9-901f-459b-8451-dd308c20d3de.png)


This article proposes a novel yet efficient defence method against adversarial attack(er)s aimed to improve the safety of deep neural networks. Removing the adversarial noise by refining adversarial samples as a defence strategy is widely investigated in previous works. Such methods are simply broken if an attacker has access to both main and refiner networks. To cope with this weakness, the authors propose to refine the input samples relying on a set of encoder–decoders, which are trained in such a way to reconstruct the samples on completely different feature spaces. To this end, the authors learn several encoder–decoder networks and force their latent spaces to have a maximum diversion. In this way, if attacker gets access to one of the refiner networks, other ones can play as a defence network. The evaluation of the proposed method confirms its performance against adversarial samples.
