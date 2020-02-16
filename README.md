# f-GAN-pytorch
 A pytorch implementation of "f-GAN: Training Generative Neural Samplers using Variational Divergence Minimization"


## Result


### 1 epochs
 
    Kullback-Leibler                                | Reverse-KL                                    | Pearson-X2
    :---:                                           | :---:                                         | :---:
    <img src="./assets/f-GAN_KLD_1ep.png">			| <img src="./assets/f-GAN_RKL_1ep.png">   	    | <img src="./assets/f-GAN_CHI_1ep.png">
    **Squared-Hellinger**                           | **Jensen-Shannon**                            | **GAN**
    <img src="./assets/f-GAN_SQH_1ep.png">			| <img src="./assets/f-GAN_JSD_1ep.png"> 		| <img src="./assets/f-GAN_1ep.png">

