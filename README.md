# covidfs-aihc
## Abstract
The world is still under the threat of different strains of the coronavirus and the pandemic situation is far from over. The method, that is widely used for the detection of COVID-19 is Reverse Transcription Polymerase chain reaction (RT-PCR), which is a time-consuming method and is prone to manual errors, and has poor precision. Although many nations across the globe have begun the mass-immunization procedure, the COVID-19 vaccine will take a long time to reach everyone. The application of Artificial Intelligence (AI) and Computer-Aided Diagnosis (CAD) has been used in the domain of medical imaging for a long period. It is quite evident that the use of CAD in the detection of COVID-19 is inevitable. The main objective of this paper is to use Convolutional Neural Networks (CNN) and a novel feature selection technique to analyze Chest X-Ray (CXR) images for the detection of COVID-19. We propose a novel two-tier feature selection method, which increases the accuracy of the overall classification model used for screening COVID-19 CXRs. Filter feature selection models are often more effective than wrapper methods as wrapper methods tend to be computationally more expensive and are not useful for large datasets dealing with a large number of features. However, most filter methods do not take into consideration how a group of features would work together, rather they just look at the features individually and decide on a score. We have used approximate Shapley value, a concept of Coalition game theory, to deal with this problem. Further, in the case of a large dataset, it is important to work with shorter embeddings of the features. We have used CUR decomposition and Nystrom sampling to further reduce the feature space. To check the efficacy of this two-tier feature selection method, we have applied it to the features extracted by three standard deep learning models, namely *VGG16*, *Xception* and *InceptionV3*, where the features have been extracted from the CXR images of COVID-19 datasets and we have found that the selection procedure works quite well for the features extracted by *Xception* and *InceptionV3*

## Citation
If you find our proposed methodology useful, please consider citing it
```
@inproceedings{lecuyer2014xray,
  title={Xray: Enhancing the web’s transparency with differential correlation},
  author={L{\'e}cuyer, Mathias and Ducoffe, Guillaume and Lan, Francis and Papancea, Andrei and Petsios, Theofilos and Spahn, Riley and Chaintreau, Augustin and Geambasu, Roxana},
  booktitle={23rd $\{$USENIX$\}$ Security Symposium ($\{$USENIX$\}$ Security 14)},
  pages={49--64},
  year={2014}
}
```
## Contact
In case of doubt or further collaboration, feel free to email us ! 😊
- [Subhankar Sen (subhankarsen2001@gmail.com) ](mailto:subhankarsen2001@gmail.com)
- [Pratik Bhowal (pratikbhowal1999@gmail.com)](mailto:pratikbhowal1999@gmail.com)
- [Prof. Ram Sarkar (ramjucse@gmail.com)](mailto:ramjucse@gmail.com)
