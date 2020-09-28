# Deep Learning 4 Human Mobility



This document aims to track the progress in the usage of Deep Learning (DL) applied to human mobility and give an overview of the state-of-the-art across the most common tasks and their corresponding datasets. In particular, we want to provide the users with a list of papers and they key characteristics (e.g., DL component(s) used in the model, metric(s) adopted for the evaluation and others) and, whenever it is open, a link to the dataset used in the paper.

Moreover, we provide a list of datasources that can be used to model human mobility (e.g., Call Detail Records, GPS trajectories, Location Based Social Networks) and others that are not representing mobility but are strictly related to it and may be taken into account to finetune predictions (e.g., weather conditions, traffic data and others).

This repository is based on the findings discussed in *A Survey of Predictive and Generative models for Human Mobilitybased on Deep Learning* a paper by Massimiliano Luca, Gianni Barlacchi, Bruno Lepri and Luca Pappalardo. If you use the content of this repository or if you want to further investigate this topic using the survey, please cite our work as

```bibtex
@article{survey,
  title={A Survey of Predictive and Generative models for Human Mobilitybased on Deep Learning},
  author={Luca, Massimiliano and Barlacchi, Gianni and Lepri, Bruno and Pappalardo, Luca},
}
```

__Table of Contents__ 
- (https://github.com/scikit-mobility/DeepLearning4HumanMobility/tree/master/Datasets)[Datasets]
  - Human Mobility 
    - Mobile Phone 
    - GPS Traces 
    - Social Media
    - Others 
  - Auxiliary
    - Spatial Aggregations 
    - Traffic
    - Environmental
    - Census and Administrative 
    - Others 
- Tasks 
  - Next-Location Prediction
  - Crowd Prediction
  - Generative Models

If you want to contribute to this repository, please open an issue and include the information according to the following guideline:

__For a paper__ 
- The BibTex of the paper 
- The name of the model proposed 
- The DL components adopted in the model (e.g., LSTM, CNN, Convolutional Layers, Attention,...) 
- The evaluation metrics adopted 
- A link to an open datasets - if any
- A link to a code repository - if any

__For a dataset__ 
- The BibTex of the publication or the link related to the datasets. Please, do not use BibTex publications that just use the dataset.
- Dataset type: auxiliary / core 
- The spatial and temporal coverage (e.g., Italy from Jan. 2020 to Apr. 2020) 
- The number of subjects covered (e.g., 500 taxis, 100k posts)
- The accessibility conditions: available / on-site  upon  project approval / upon registration
- A link to the dataset
