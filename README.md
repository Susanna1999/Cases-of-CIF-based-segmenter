# Cases-of-CIF-based-segmenter

We propose a Continuous Integrate-and-Fire (CIF)-based speech segmentation method for two-pass streaming E2E ASR. 
Compared with VAD, the CIF estimator reuses the large encoder of ASR and optimizes jointly with ASR, which has a stronger modeling ability.
In addition, the CIF participates in the generation of token embedding in Paraformer, so the weight can also reflect the decoder's dependence on acoustic information contained in each frame. 
Continuous zero appearing in the CIF weight will be segmented. 
Furthermore, convolutional processing is adopted to detect the middle of the silent segment. 

Please go [github page](https://susanna1999.github.io/) check the demo page.
