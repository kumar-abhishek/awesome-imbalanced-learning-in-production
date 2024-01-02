<div align="center">
   <h1> Awesome Imbalanced Learning in Production</h1>
</div>

<p align="center">
  <img src="logo.png" align="center" width="350">
</p>
<p align="center">
  <a href="https://github.com/sindresorhus/awesome">
    <img alt="Awesome" src="https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg" />
  </a>
</p>

If you find this content insightful, feel free to support with a ⭐

A search for "Imbalanced data" on Google Scholar yields over [one million results](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C48&q=imbalanced+data&btnG=) in total, with approximately [17,000 results](https://scholar.google.com/scholar?as_ylo=2023&q=imbalanced+data&hl=en&as_sdt=0,48) since 2023. This raises a question: Is it merely a popular topic for academic papers, or is it a genuine challenge faced in the industry?

To shed light on this, the book includes several examples of how leading companies like Apple, Meta, and Microsoft have addressed class imbalance issues.

This GitHub repository offers a curated list of resources demonstrating how various companies have successfully tackled the challenge of imbalanced data in production settings. This repository is aimed at being an invaluable resource for professionals/researchers/enthusiasts in machine learning and data science dealing with similar challenges.


Inspired By [Awesome-System-Design](https://GitHub.com/madd86/awesome-system-design)

## Contents

- [Oversampling Methods](#oversampling-methods)
- [Undersampling Methods](#undersampling-methods)
- [Ensemble Methods](#ensemble-methods)
- [Cost-Sensitive Learning](#cost-sensitive-learning)
- [Data Imbalance in Deep Learning](#data-imbalance-in-deep-learning)
- [Data-Level Deep Learning Methods](#data-level-deep-learning-methods)
- [Algorithm-Level Deep Learning Techniques](#algorithm-level-deep-learning-techniques)
- [Hybrid Deep Learning Methods](#hybrid-deep-learning-methods)
- [Model Calibration](#model-calibration)

[Case Studies](#case-studies)

[Articles](#articles)

[Videos](#videos)

[Other general resources on the topic](#other-general-resources-on-the-topic)
- [Libraries, Tools and Frameworks](#tools-and-frameworks)
- [Datasets](#datasets)
- [Benchmarks](#benchmarks)
- [Awesome libraries on Github](#awesome-libraries-on-Github)
- [Books](#books)


### Oversampling Methods
| Technique            | Company                                                                                             |
|----------------------|-----------------------------------------------------------------------------------------------------|
| Random oversampling  | [Grab](https://engineering.grab.com/protecting-personal-data-in-grabs-imagery)                      |
| SMOTE                | [Microsoft](https://medium.com/data-science-at-microsoft/live-site-incident-escalation-forecast-566763a2178) |
| Borderline-SMOTE     | [Amazon](https://www.amazon.science/latest-news/deep-learning-machine-learning-computer-vision-applications-reducing-amazon-package-waste), [Paper](https://www.amazon.science/publications/position-paper-reducing-amazons-packaging-wasteusing-multimodal-deep-learning) |


### Undersampling Methods
| Technique              | Company                                                                                         |
|------------------------|-------------------------------------------------------------------------------------------------|
| Negative downsampling  | [Meta](https://doi.org/10.1145/2648584.2648589)                                                 |
| Negative downsampling  | [Microsoft](https://doi.org/10.1145/3041021.3054192)                                            |
| Negative downsampling  | [Uber](https://www.uber.com/blog/how-uber-optimizes-push-notifications-using-ml)                |


### Ensemble Methods
| Technique                 | Company                                                                                                 |
|---------------------------|---------------------------------------------------------------------------------------------------------|
| BalancedBaggingClassifier | [Microsoft](https://medium.com/data-science-at-microsoft/live-site-incident-escalation-forecast-566763a2178) |

### Cost-Sensitive Learning
| Technique                | Company                                                                                                           |
|--------------------------|-------------------------------------------------------------------------------------------------------------------|
| Cost-sensitive learning  | [Microsoft](https://doi.org/10.1145/3041021.3054192)                                                              |
| Cost-sensitive learning  | [Airbnb](https://medium.com/airbnb-engineering/machine-learning-powered-search-ranking-of-airbnb-experiences-110b4b1a0789) |


### Data-Level Deep Learning Methods
| Application             | Company                                                                                                               | Year |
|-----------------------|-----------------------------------------------------------------------------------------------------------------------|------|
| Real-Time Personalization | [Etsy](https://www.etsy.com/codeascraft/leveraging-real-time-user-actions-to-personalize-etsy-ads)                     | 2023 |
| Automated Image Tagging  | [Booking.com](https://booking.ai/automated-image-tagging-at-booking-com-7704f27dcc8b)                                  | 2017 |
| Shot Angle Prediction    | [Wayfair](https://www.aboutwayfair.com/tech-innovation/shot-angle-prediction-estimating-pose-angle-with-deep-learning-for-furniture-items-using-images-generated-from-3d-models) | 2020 |
| Data Protection          | [Grab](https://engineering.grab.com/protecting-personal-data-in-grabs-imagery)                                         | 2021 |
| ML Model Improvement     | [Cloudflare](https://blog.cloudflare.com/data-generation-and-sampling-strategies/)                                     | 2022 |



### Algorithm-Level Deep Learning Techniques
| Technique                | Company                                                                                                           |
|--------------------------|-------------------------------------------------------------------------------------------------------------------|
| DALL·E 2 pre-training mitigations | [OpenAI](https://openai.com/research/dall-e-2-pre-training-mitigations)                                           |
| BERT for NLP             | [Wayfair](https://www.aboutwayfair.com/tech-innovation/bert-does-business-implementing-the-bert-model-for-natural-language-processing-at-wayfair) |
| Focal loss               | [Meta](https://ai.meta.com/blog/community-standards-report)                                                       |
| Class-balanced loss      | [Apple](https://machinelearning.apple.com/research/mobile-applications-accessible)                                |

### Hybrid Deep Learning Methods
| Method                    | Company                                                                                       | Year |
|---------------------------|-----------------------------------------------------------------------------------------------|------|
| Relational Graph Learning | [Uber](https://www.uber.com/blog/fraud-detection)                                             | 2021 |
| Graph for Fraud Detection | [Grab](https://engineering.grab.com/graph-for-fraud-detection)                                | 2022 |


### Model Calibration
 | Technique           | Company                                                                                             | Year | 
|---------------------|-----------------------------------------------------------------------------------------------------|------|
| Model Calibration   | [Netflix](https://doi.org/10.1145/3240323.3240372)                                                   | 2018 |
| Model Calibration   | [Meta](https://doi.org/10.1145/2648584.2648589)                                                     | 2014 |


### Case Studies to check out

- [Source: ML system design: 300 case studies to learn from](https://www.evidentlyai.com/ml-system-design)
  
### Articles

- [Exploring Imbalanced Data Solutions](https://link-to-article)
- [Practical Guide to Handle Imbalanced Datasets](https://link-to-article)

### Videos

| Video Title | Company | Year |
|---|---|---|
| [Natalie Hockham: Machine learning with imbalanced data sets](https://www.youtube.com/watch?v=X9MZtvvQDR4) | GoCardless | 2015 |
| [PyData Tel Aviv Meetup: GANs for Imbalanced Classification Problems - Moshe Salhov](https://www.youtube.com/watch?v=jy4DVV5bFWc) | Playtika | 2018 |
| [Brendan Herger - Machine Learning Techniques for Class Imbalances & Adversaries](http://www.youtube.com/watch?v=u72FD79tsxA) | CapitalOne | 2016 |

### Other general resources on the topic

#### Libraries, Tools and Frameworks

- [imbalanced-learn](https://github.com/scikit-learn-contrib/imbalanced-learn)
- [SMOTE-variants for imbalanced learning](https://github.com/analyticalmindsltd/smote_variants)
- [imbalanced-DL: Deep Imbalanced Learning in Python](https://github.com/ntucllab/imbalanced-DL)
- [IMBENS: Class-imbalanced Ensemble Learning in Python](https://github.com/ZhiningLiu1998/imbalanced-ensemble)
- [MESA: Meta-sampler for imbalanced learning](https://github.com/ZhiningLiu1998/mesa)
- [Python-based implementations of algorithms for learning on imbalanced data](https://github.com/dialnd/imbalanced-algorithms)

#### Datasets

- [CIFAR10-LT and CIFAR100-LT](https://github.com/kaidic/LDAM-DRW/blob/master/imbalance_cifar.py)
- [Long-tailed Datasets](https://paperswithcode.com/task/long-tail-learning)
- [Deep Long-Tailed Learning: A Survey](https://arxiv.org/pdf/2110.04596.pdf): Statistics of Long-Tailed Datasets:

| Task                  | Dataset            | # Classes | # Training Data | # Test Data |
|-----------------------|--------------------|-----------|-----------------|-------------|
| Image Classification  | ImageNet-LT [15]   | 1,000     | 115,846         | 50,000      |
|                       | CIFAR100-LT [18]   | 100       | 50,000          | 10,000      |
|                       | Places-LT [15]     | 365       | 62,500          | 36,500      |
|                       | iNaturalist 2018 [23] | 8,142   | 437,513         | 24,426      |
| Object Detection/Instance Segmentation | LVIS v0.5 [36] | 1,230 | 57,000 | 20,000 |
|                       | LVIS v1 [36]       | 1,203     | 100,000         | 19,800      |
| Multi-label Classification | VOC-LT [37]   | 20        | 1,142           | 4,952       |
|                       | COCO-LT [37]       | 80        | 1,909           | 5,000       |
| Video Classification  | VideoLT [38]       | 1,004     | 179,352         | 51,244      |



#### Benchmarks
- [Leaderboard: Long-tail Learning on CIFAR-10-LT (ρ=10)](https://paperswithcode.com/sota/long-tail-learning-on-cifar-10-lt-r-10)
- [Leaderboard: Long-tail Learning on CIFAR-100-LT (ρ=100)](https://paperswithcode.com/sota/long-tail-learning-on-cifar-100-lt-r-100)
- [Long-tail Learning Benchmarks](https://paperswithcode.com/task/long-tail-learning)

#### awesome-libraries on Github

- https://github.com/Stomach-ache/awesome-long-tail-learning
- https://github.com/ZhiningLiu1998/awesome-imbalanced-learning/
- https://github.com/CoinCheung/pytorch-loss
- https://github.com/ZhugeKongan/torch-template-for-deep-learning
- https://github.com/hh-xiaohu/Image-augementation-pytorch
- https://github.com/GZWQ/Awesome-Long-Tailed
- https://github.com/danielgy/Paper-list-on-Imbalanced-Time-series-Classification-with-Deep-Learning
- https://gitee.com/liuziyang1106/awesome-imbalanced-learning

#### Books
- [Imbalanced Classification with Python: Better Metrics, Balance Skewed Classes, Cost-Sensitive Learning by by Jason Brownlee](https://www.amazon.com/Imbalanced-Classification-Python-Cost-Sensitive-Learning/dp/B09FP165TZ/)
- [Learning from Imbalanced Data by Alberto Fernández, Salvador García, Mikel Galar, et al. ](https://www.amazon.com/Learning-Imbalanced-Data-Alberto-Fern%C3%A1ndez-ebook/dp/B07FM9PLWN/)
- [Imbalanced Learning: Foundations, Algorithms, and Applications](https://www.amazon.com/Imbalanced-Learning-Foundations-Algorithms-Applications-ebook/dp/B00DAB28YM)
- [Machine Learning for Imbalanced Data: Tackle imbalanced datasets using machine learning and deep learning techniques](https://www.amazon.com/Machine-Learning-Imbalanced-Data-imbalanced/dp/1801070830/)

---

Please note that this is a living document and will be updated with more resources over time. Contributions are welcome!
