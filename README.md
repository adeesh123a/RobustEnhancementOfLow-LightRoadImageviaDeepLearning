# RobustEnhancementOfLow-LightRoadImageviaDeepLearning
The aim is to design, implement, and rigorously evaluate a novel multi-stage enhancement architecture that effectively mitigates image degradation in low-light road environments. The model to be used will be a series of several sequential stages through which it will process the images starting with a preliminary pre-enhancement stage that normalizes the illumination, then a structural restoration stage that extracts the details, and finally, a refinement stage that enhances colour quality and perceptual realism. The multi-stage approach, which divides the problem into different aspects of the low-light condition, thus yielding clearer, more natural, and more realistic images of the road, has been chosen over the single enhancement step. The ultimate objective is to enhance the images to enable safer and more reliable perception tasks for autonomous vehicles during challenging low-light driving scenarios.

## Objectives:
- To analyse existing low-light image enhancement techniques and identify their limitations in road environments.
- To design a hybrid enhancement framework that merges illumination estimation with generative refinement for the enhancement of night-time road images of a high-quality.
- To evaluate the model’s enhancement quality using objective metrics such as PSNR, SSIM, LPIPS, and NIQE across multiple low-light driving datasets.
- To compare the proposed model against established LLIE methods through both objective metrics and visual evaluation.
- To analyse model generalization by evaluating performance across diverse datasets, covering varying levels of illumination, noise, and road conditions. 
