# f-GAN-pytorch
 A pytorch implementation of "f-GAN: Training Generative Neural Samplers using Variational Divergence Minimization"


## Result

 - 1 epochs
 
    Kullback-Leibler                                | Reverse-KL                                    | Pearson-X2
    :---:                                           | :---:                                         | :---:
    <img src="./assets/f-GAN_KLD_1ep.png">			       | <img src="./assets/f-GAN_RKL_1ep.png">   	    | <img src="./assets/f-GAN_CHI_1ep.png">
    **Squared-Hellinger**                           | **Jensen-Shannon**                            | **GAN**
    <img src="./assets/f-GAN_SQH_1ep.png">			       | <img src="./assets/f-GAN_JSD_1ep.png"> 		     | <img src="./assets/f-GAN_1ep.png">
	
	
	
  - 20 epochs
  
      Kullback-Leibler                                  | Reverse-KL                                    | Pearson-X2
    :---:                                           | :---:                                         | :---:
    <img src="./assets/f-GAN_KLD_20ep.png">			       | <img src="./assets/f-GAN_RKL_20ep.png">   	    | <img src="./assets/f-GAN_CHI_20ep.png">
    **Squared-Hellinger**                           | **Jensen-Shannon**                            | **GAN**
    <img src="./assets/f-GAN_SQH_20ep.png">			       | <img src="./assets/f-GAN_JSD_20ep.png"> 		     | <img src="./assets/f-GAN_20ep.png">
	

	-  7 epochs Kullback-Leibler divergence
	
	
	<img src="./assets/f-GAN_KLD_7ep.png" width="300" height="300">
	
	Mode collapse occurs after 7 epochs for Kullback-Leibler divergence objective.<br>
	This is the result of 7 epochs result of Kullback-Leibler divergence objective.

