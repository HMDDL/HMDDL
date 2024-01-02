### Hi there 👋

<!--
Accelerated 4D free-breathing whole-liver water-fat MRI with deep dictionary learning and chemical shift modeling
Background
Multi-echo chemical shift encoded MRI has been widely used for fat suppression and fat quantification in clinical liver examinations. 
Clinical liver water-fat imaging typically requires breath-hold acquisitions. Free-breathing acquisition is more desirable for patient comfort. 
However, the acquisition for free-breathing imaging could take up to several minutes. 
The purpose of this study is to accelerate 4D free-breathing whole-liver water-fat MRI by jointly using high-dimensional deep dictionary learning and model-guided reconstruction.

Methods
In this work, a high-dimensional model-guided deep dictionary learning (HMDDL) algorithm is proposed for the acceleration. 
The HMDDL combines the powers of high-dimensional dictionary learning neural network and chemical shift model. 
The neural network utilizes the prior information of the dynamic multi-echo data in spatial, respiratory motion, and echo dimensions to exploit the features of images. 
The chemical shift model is used to guide the reconstruction of field maps,  maps, water images, and fat images. 
Eleven healthy subjects and twelve subjects with clinically diagnosed nonalcoholic fatty liver disease (NAFLD) were used as the training and validation sets.
Five healthy subjects and five NAFLD subjects were used as the test set. 
The performance of the HMDDL was evaluated in comparison with the compressed sensing-based water-fat separation (CS-WF) algorithm 
and the parallel non-Cartesian recurrent neural networks (PNCRNN) algorithm on the prospectively undersampled radial data.

Results
Four-dimensional water/fat images with ten motion states for whole-liver are demonstrated at several R values. 
Compared with the CS-WF and Unet-WF, the HMDDL improves the mean PSNR of images by 9.94 dB and 2.31 dB, respectively, 
and improves the mean SSIM of images by 0.059 and 0.009, respectively, at R = 10. 
The paired t-test shows that there is no significant difference between HMDDL and ground truth for proton density fat fraction (PDFF) and  values at R up to 10.

Conclusions
The proposed HMDDL enables exploiting the features of water images and fat images from the highly undersampled multi-echo data along spatial, respiratory motion, and echo dimensions, 
leading to improved performance in the accelerated 4D free-breathing water-fat imaging.
-->
