# An Advanced Web App for Autism Detection and Therapy Recommendation

## Abstract
The objective of this project is to develop an autism detection system that leverages diverse data sources to provide accurate and holistic assessments. The final implementation comprises four key components:

1. **Tabular Data Model:**
   * The first component involves the creation of a model that analyzes tabular data.
   * It is designed to assess various attributes and factors associated with autism risk, contributing to a comprehensive evaluation.

2. **Image Data Model:**
   * The second component is an image data model that processes video input to classify children as either autistic or non-autistic.
   * By utilizing image-based information, this model enhances the accuracy and depth of the assessment.

3. **Integration of Models:**
   * The project integrates both the tabular data model and the image data model to provide a balanced and averaged prediction.
   * This combined approach leverages the strengths of each model to deliver a more robust and reliable outcome.

4. **Therapy Recommendations:**
   * Based on the results obtained from the assessment, the system offers personalized therapy recommendations.
   * These recommendations are tailored to the individual's Autism Spectrum Quotient (ASQ) score, providing targeted guidance for therapy and support.

This multi-faceted approach to autism detection aims to improve accuracy and enhance the understanding of each child's unique needs, ultimately facilitating early intervention and support for those on the autism spectrum.

---

## Proposed System: An Advanced Autism Detection and Therapy Recommendation System
Our proposed system represents a cutting-edge solution for the detection of autism spectrum disorder (ASD) in children and offers personalized therapy recommendations. Leveraging the power of modern technology, our system combines multiple data sources, advanced machine learning models, and mobile application integration to create a comprehensive and user-friendly platform.

### Key Features and Innovations:
1. **Multimodal Approach:** Our system employs a multimodal approach, combining tabular data and image data for more accurate and reliable autism detection. This dual-model approach enhances the robustness and precision of our system.
2. **Deep Learning Models:** We utilize state-of-the-art deep learning models for both tabular and image data. These models have been trained on extensive datasets, enabling them to recognize subtle patterns and indicators of autism with high accuracy.
3. **Integration of Models:** The synergy between the tabular and image-based models is achieved through intelligent integration. By combining the predictions of these models and calculating an average, we provide a well-rounded and more reliable assessment of a child's condition.
4. **ASQ Score-Based Recommendations:** Our system assesses children's Autism Screening Questionnaire (ASQ) scores and generates tailored therapy recommendations. These recommendations are drawn from a curated selection of evidence-based therapies, ensuring that each child receives personalized care.

---

## Existing Systems: A Comparative Overview
While several existing systems address autism detection and therapy recommendation, our proposed system distinguishes itself through innovation, integration, and user-friendliness:

1. **Traditional Screening Tools:** Many existing systems rely solely on traditional screening tools and questionnaires, which can lack the accuracy and predictive power of advanced machine learning models.
2. **Limited Data Sources:** Some systems rely exclusively on a single data source, either tabular data or image data. Our system's multimodal approach provides a more comprehensive view of a child's condition.
3. **Manual Therapy Selection:** Existing systems often require healthcare professionals to manually select therapy recommendations based on assessment results. Our system automates this process, providing data-driven, personalized recommendations.
4. **User Accessibility:** Many existing systems lack user-friendly interfaces, making them less accessible to parents and caregivers. Our Android application ensures easy access and data input.
5. **Integration:** Our system integrates all components seamlessly, offering a unified platform for assessment and therapy recommendations. This integration streamlines the process and enhances user experience.

---

## Model Performance & Experimental Results

### 1. Tabular Machine Learning Models (`train_test_split` with `test_size=0.2, random_state=101`)[cite: 11]
* **Decision Tree Classifier:** Accuracy score of `0.8104265402843602` (81.04%)[cite: 7, 11]
* **Random Forest Classifier:** Accuracy score of `0.7772511848341233` (77.73%)[cite: 7, 11]
* **Gradient Boosting Classifier:** Accuracy score of `0.6255924170616114` (62.56%)[cite: 7, 11]
* **AdaBoost Classifier:** Accuracy score of `0.18009478672985782` (18.01%)[cite: 7, 11]

### 2. Deep Learning Image Models & Algorithm Comparison
* **ResNet 101V2:** Accuracy score of ~77.5%[cite: 6, 10]
* **ResNet 50:** Accuracy score of ~71.8%[cite: 6, 10]
* **ResNet 50V2:** Accuracy score of ~70.8%[cite: 6, 10]
* **VGG19:** Accuracy score of ~66.0%[cite: 6, 10]

---

## Evaluation Visualizations

### Accuracy Score Comparison
* **Description:** Bar chart comparing accuracy scores across VGG19, Resnet 50, Resnet 50V2, and Resnet 101V2 algorithms[cite: 6, 10].

<p align="center">
  <img src="outputs/accuracy_comparison.png" alt="Accuracy score Comparison" width="85%"/>
</p>

### ROC Curve
* **Description:** ROC curve visualization for evaluated image models (VGG, RESNET50, RESNET50V2, RESNET101V2)[cite: 8, 12].

<p align="center">
  <img src="outputs/roc_curve.png" alt="ROC curve" width="85%"/>
</p>

---

## Conclusion
In conclusion, our proposed system represents a significant advancement in the field of autism detection and therapy recommendation. By combining advanced technology, data integration, and user accessibility, we aim to provide a valuable tool for early diagnosis and intervention in autism spectrum disorder, ultimately improving the lives of children and their families.
