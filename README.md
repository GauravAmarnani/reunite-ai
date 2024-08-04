# ReUnite AI

## Introduction

ReUnite AI is a project developed by the Department of Computer Engineering at Vivekanand Education Society’s Institute of Technology in Chembur, India. The project aims to harness face detection and age progression technologies to aid in identifying missing persons.

## Abstract

The ReUnite AI project utilizes deep learning algorithms to analyze facial features of missing individuals and generate updated representations of their appearances over time using age progression models. The system is trained on a comprehensive dataset of facial images to ensure robust performance across diverse demographics and aging trajectories.

## Contributors

- [Mr. Gaurav Amarnani](https://github.com/GauravAmarnani)
- [Mr. Chetaniya Bajaj](https://github.com/ChetaniyaBajaj)
- [Mr. Kaplesh Mulchandani](https://github.com/KapleshMulchandani)
- [Mr. Jayesh Repale](https://gitlab.com/jayeshrepale2002)


## System Architecture

![System Architecture](https://github.com/GauravAmarnani/reunite-ai/blob/main/images/Architecture.png)

ReUnite AI functions as an integrated platform designed to facilitate the identification of missing persons through a user-friendly interface. Users can upload images of missing individuals or those they suspect might be missing. The system then initiates a series of automated processes to analyze the uploaded content.

## Reporting Missing Persons

![Reporting Missing Person](https://github.com/GauravAmarnani/reunite-ai/blob/main/images/Report_Missing_Details.png)

![Confirmation of Missing Person Details](https://github.com/GauravAmarnani/reunite-ai/blob/main/images/Report_Missing_Details_Confirmation.png)

Users can report a missing individual by providing comprehensive information, including the individual's name, age, gender, and Aadhar card details, along with the most recent available image. The system undergoes thorough validation processes before securely storing the data within the missing persons database.

## Reporting Found Persons

![Reporting Found Person](https://github.com/GauravAmarnani/reunite-ai/blob/main/images/Report_Missing_Found.png)

![Results of System Check](https://github.com/GauravAmarnani/reunite-ai/blob/main/images/Report_Missing_Found_Final_Page.png)

When users report a found individual, they can submit up to 10 images of the individual. The system utilizes these images for training to determine whether the found person matches any existing entries within the missing persons database. Users are promptly notified of any matches or the absence thereof.

## Age Progression

![Age Progression](https://github.com/GauravAmarnani/reunite-ai/blob/main/images/Age_Progression.png)

For images older than 5 years, the system employs sophisticated age progression techniques to generate an updated image reflecting the potential appearance of the individual at the current time. This augmented image is compared with the original for comprehensive comparative analysis.

## Dataset

![Olivetti Dataset](https://github.com/GauravAmarnani/reunite-ai/blob/main/images/Olivetti_dataset.png)

The dataset used for training the model is the Olivetti dataset, consisting of grayscale facial images of 40 distinct subjects, with 10 images per subject. Each image is 92 pixels wide and 112 pixels tall, captured in a controlled environment with consistent lighting conditions and facial expressions.

## Results and Evaluation

The classification results for various machine learning models applied to the dataset are as follows:

| Machine Learning Algorithm | Accuracy Score |
|----------------------------|----------------|
| Linear Discriminant Analysis (LDA) | 0.93 |
| Linear Regression (LR) | 0.93 |
| Naïve Bayes (NB) | 0.86 |
| K-Nearest Neighbour (KNN) | 0.70 |
| Decision Tree (DT) | 0.66 |
| Support Vector Machine (SVM) | 0.92 |

## Conclusion and Future Work

The ReUnite AI project represents a beacon of hope in utilizing advanced technologies to tackle the challenge of locating missing individuals. Future work includes exploring ways to integrate real-time data sources, such as social media platforms or surveillance footage, to enhance the system's effectiveness in dynamic situations.
