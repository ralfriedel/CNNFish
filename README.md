# Using computer vision toward automation of fish ageing
Using AI to determine age of fish

## Highlights
Accurate age estimates of living marine resources are necessary for use in quantitative statistical age-based stock assessment are contingent on the accurate determination of age. This project had the objective of investigating the utility of computer vision in determining the ages of fish scales. By providing an alternative to manual fish age estimation this work contributes to reducing costs of fish ageing. Below is the abstract of a presentation to stakeholders and some visuals for depicting the results.

The following tools and analysis were used in this project:
- R for inferential statistics and visualizations
- Python/Tensorflow for deep learning
- Analysis of variance was the main analytical approach

## Abstract and Visuals
Estimates of fish age form the basis of calculating key biological variables for resource management. Hard structures used in age estimation are of different efforts to extract and process for reading. Of such hard structures, fish scales are among the lowest in time and dollar cost to process. Scale reading, however, still requires significant costs to complete. To assess the potential for scale reading automation in allaying such costs, the feasibility of computer vision has been assessed. Convolutional neural networks (CNN) and deep neural networks (DNN) have been used in this study to classify scale images of Gulf menhaden (Brevoortia patronus). Three datasets have been generated for testing. The first one consisted of scales estimated to be from fish ages zero and one. The second dataset was for fish ages zero to four. The last dataset was for scales ages zero, one, and two where scale readings agreed with that from otoliths for the same individual fish. Model classification of ages were best when using CNN on the first dataset. The poorest classification was for the DNN model using the second dataset. Although computer vision showed promise for fish ageing automation, the need for image preprocessing and selection of ages where scale annuli are well defined is still necessary. With the continuous enhancements of computer vision models and improvements in quality of scale images, the promise of computer vision in reducing age estimation time and increasing accuracy is not far from realization.

<img src="fig1.jpg" align="center" width="500" height="400">
Figure 1. Computer vision model architecture used in classifying Menhaden age from scales.

<img src="fig2.jpg" align="center" width="500" height="400">
Figure 2. Training and validation accuracies in each training epoch using artificial intelligence model classification of Gulf Menhaden (Brevoortia patronus) scale images. The data evaluated were S2 (ages 0 and 1 y), SC (age 0 to 4 y), and SG (only images used where scale and otolith readings agreed); models were convolutional neural networks (CNN) and deep neural networks (DNN).

<img src="fig3.jpg" align="center" width="500" height="400">
Figure 3. Group means of training accuracy (A, B) and validation accuracy (C, D) from artificial intelligence model runs for classification of Gulf Menhaden (Brevoortia patronus) scale images. The data evaluated are S2 (ages 0 and 1 y), SC (age 0 to 4 y), and SG (only images used where scale and otolith readings agreed); models were convolutional neural networks (CNN) and deep neural networks (DNN); error bars are 95% confidence intervals.

<img src="fig4.jpg" align="center" width="500" height="400">
Figure 4. Saliency maps from computer vision model runs for classification of Gulf Menhaden (Brevoortia patronus) scale images; zero values indicate no influence on outcome, one indicates maximum influence.

