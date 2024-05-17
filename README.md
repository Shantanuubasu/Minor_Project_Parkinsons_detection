# PARKINSON'S DISEASE DETECTION USING SVM MODEL

## ABSTRACT

Voice-based biomarkers can help diagnose symptoms of dementia such as Parkinson's disease, PD is a modern neurodegenerative disease affecting about 7 million people worldwide (usually adults), with about 150 thousand new scientific diagnoses performed each year. Historically, PD has been difficult to find and documents tend to focus on a few symptoms and even ignore some, depending on the scores of independent points. Due to the decline in motor manipulation which is a sign of illness, the term can be used as a means of detecting and diagnosing PD. Common sense has meant that physicians often focus on the symptoms of PD while ignoring the other. By using independent measurement scales, the term can be used to diagnose and diagnose the disease. This project presents evidence to support the concept of supervised classification, which can be used to diagnose individuals with diseases such as diabetes and pulmonary fibrosis. Support Vector Machine and Hypermetric Tuning we were able to achieve a peak accuracy of 94.91% for diagnosing pathological conditions. 

## INTRODUCTION

Parkinson's disease (PD) shows loss of life of dopaminergic neurons in substantia nigra pars compacta in the midbrain. These neurodegeneration modifications end up with numbers and symptoms that include communication problems, voice adjustment, and allergies. Dysarthria is also seen in PD sufferers; its miles are characterized by weakness, paralysis, and a lack of communication within the motor vehicle: affecting breathing, crying, speech, and prosody. The exact reason for Parkinson's disease is unknown, but it is a concept that involves complex interactions between genetics, biology, and the environment, which not only leads to the heterogeneity of PD signs and symptoms, but also to their charge of progression through the years. This brings uncertainty to sufferers' destiny first-class of existence, and it also brings challenges to treatment trials in determining successful endpoints. More and more reports of changes in peripheral immune machine function in sufferers of Parkinson's sickness. In recent years, there's evidence that a protein referred to as α-synuclein, the enteric fearful machine, and the intestinal brain axis are associated with the etiology of Parkinson's disorder, which suggests that Parkinson's ailment can also even start from the outer edge. These studies can also provide a possibility to pick out markers that are expecting the progression of Parkinson's sickness. Since signs and the disorder path vary, PD is usually now not available for decades. Therefore, there may be a need for more sophisticated diagnostic equipment to diagnose PD because, as the disease progresses, additional symptoms appear that make PD harder to deal with. The main shortcomings of PD speech are loss of depth, tone of voice and voice, reduction of pressure, hallucinations, short speech speeds, dynamic charging, blurred consonants, and a violent and breathing voice (dysphonia). The wide range of voice-related features promises a powerful tool because voice recording is non-invasive and can be done without difficulty with mobile gadgets. This business is evaluating the effectiveness of the use of  Vector Support Machines and Hypermetric Tuning for better identification of people with the disease.


## LITERATURE REVIEW

In this project, Python, alongside essential libraries like Pandas, NumPy, Matplotlib, Seaborn, and Scikit-learn, serves as the foundation, empowering seamless data manipulation, analysis, visualization, and SVM machine learning model implementation for robust insights extraction.

### Python Libraries

1.Pandas: A powerful data manipulation and analysis library for Python, providing data structures and functions to work with structured data efficiently.

2.NumPy: A fundamental package for numerical computing in Python, offering support for large, multi-dimensional arrays and matrices, along with a collection of mathematical functions.

3.Matplotlib: A comprehensive plotting library in Python, enabling the creation of a wide variety of static, animated, and interactive visualizations.

4.Seaborn: A statistical data visualization library built on top of Matplotlib, offering a high-level interface for drawing attractive and informative statistical graphics.

5.Scikit-learn: A versatile machine learning library for Python, providing simple and efficient tools for data mining and data analysis, including a wide range of supervised and unsupervised learning algorithms.


## Problem Statement / Requirement Specifications

In this project, a support vector machine model is trained with hyperparameter tuning to accurately classify patients with Parkinson's disease from those without. Leveraging Scikit-learn, the model is fine-tuned to optimize performance, aiding in the effective identification and differentiation of individuals afflicted by Parkinson's from healthy counterparts.

### Project Planning

1.Define Objectives: Clearly outline the project's goal, such as developing a support vector machine model to classify patients with Parkinson's disease.

2.Data Collection: Gather relevant datasets containing features indicative of Parkinson's disease, such as voice recordings or clinical data.

3.Data Preprocessing: Cleanse and preprocess the data to handle missing values, outliers, and normalize features for better model performance.

4.Feature Selection/Extraction: Identify significant features correlated with Parkinson's disease to improve model accuracy and efficiency.

5.Model Selection: Choose an appropriate support vector machine algorithm and kernel type based on the nature of the data and desired outcomes.

6.Hyperparameter Tuning: Optimize the model's hyperparameters using techniques like grid search or random search to enhance its predictive capabilities.

7.Training: Train the support vector machine model on a portion of the dataset, ensuring sufficient data for both training and validation.

8.Evaluation: Assess the model's performance using appropriate evaluation metrics such as accuracy, precision, recall, and F1-score.

9.Validation: Validate the model's performance on an independent dataset to confirm its generalization ability and robustness.

10.Deployment: Deploy the trained model into a production environment, ensuring seamless integration with end-user systems or applications.

11.Monitoring and Maintenance: Continuously monitor the model's performance in real-world settings and update it periodically to adapt to changing data patterns or requirements.

### System Design

#### Design Constraints

##### Hardware requirements:

Memory: 8 GB RAM
Free Storage: 4 GB (SSD Recommended)
Screen Resolution: 1920 x 800
OS: Windows 10 (64-bit)
CPU: Intel Core i5-8400 3.0 GHz or better

##### Language used & analysis requirements:

Python
Numpy
Matplotlib
Seaborn
Github
Jupyter Notebook

##### System Architecture OR Block Diagram:
<img width="165" alt="image" src="https://github.com/Shantanuubasu/Minor_Project_Parkinsons_detection/assets/97277717/437e78b6-56bc-45ad-afd5-1fd8020dbfce">


## Implementation

A Support Vector Machine (SVM) is a supervised machine learning algorithm primarily used for classification and regression tasks. It works by finding the optimal hyperplane in a high-dimensional space that separates data points of different classes with the maximum margin, thereby maximizing the generalization ability of the model. SVMs are effective in handling both linearly separable and non-linearly separable datasets through the use of kernel functions, which map the input data into higher-dimensional feature spaces. This flexibility allows SVMs to capture complex decision boundaries and classify data accurately. SVMs are robust against overfitting, particularly in high-dimensional spaces, and can handle datasets with a large number of features efficiently. Due to these characteristics, SVMs are widely used in various fields, including bioinformatics, image recognition, text classification, and financial prediction.

### Methodology OR Proposal

In the context of a Parkinson's disease detection model, a Support Vector Machine (SVM) with hyperparameter tuning refers to a supervised machine learning approach utilized to accurately classify patients as either afflicted with Parkinson's disease or healthy. Through hyperparameter tuning, parameters such as the choice of kernel function, regularization parameter, and kernel coefficient are optimized to enhance the SVM's performance in discerning between the two classes. This optimization process aims to maximize the model's predictive accuracy while minimizing overfitting, ensuring robust and reliable detection of Parkinson's disease based on input features extracted from relevant data sources, such as clinical assessments or biomedical measurements.

### Testing OR Verification Plan:

In our Parkinson's disease detection model, we partitioned our dataset into 70% for training and 30% for testing, amounting to a total of 59 data points. Among these, 55 individuals were correctly identified as having Parkinson's disease, resulting in an accuracy rate of 94.91%. This high accuracy underscores the effectiveness of our model in accurately classifying patients, showcasing its potential as a reliable tool for Parkinson's disease diagnosis.

### Result Analysis OR Screenshots:
<img width="296" alt="image" src="https://github.com/Shantanuubasu/Minor_Project_Parkinsons_detection/assets/97277717/79328a15-792f-433b-ac96-d447383ea0b8">
<img width="235" alt="image" src="https://github.com/Shantanuubasu/Minor_Project_Parkinsons_detection/assets/97277717/fef91101-0e7b-4ed0-88df-c56a45b37b19">
<img width="212" alt="image" src="https://github.com/Shantanuubasu/Minor_Project_Parkinsons_detection/assets/97277717/d72a4f91-93ae-4c7c-b63b-f73a8090c341">


## Standards Adopted

### Design Standards :

1.User-Centric Approach: Prioritize user needs and preferences to create intuitive and user-friendly interfaces or experiences.

2.Modularity: Design the project in a modular fashion, breaking it into smaller, manageable components or modules to facilitate easier development, testing, and maintenance.

3.Scalability: Ensure the project's architecture and design can accommodate future growth and expansion without significant restructuring or performance degradation.

4.Consistency: Maintain consistency in design elements such as layout, color scheme, typography, and terminology across the project to provide a cohesive user experience.

5.Accessibility: Design with accessibility in mind to ensure all users, including those with disabilities, can access and use the project effectively.

6.Performance: Optimize the project for performance, considering factors such as loading times, response times, and resource utilization to deliver a responsive and efficient experience.

7.Security: Implement robust security measures to protect sensitive data, prevent unauthorized access, and mitigate potential security threats or vulnerabilities.

8.Documentation: Document the project's design decisions, architecture, components, APIs, and usage guidelines comprehensively to aid in understanding, maintenance, and future development.

9.Testing: Incorporate testing methodologies and practices throughout the design process to identify and rectify issues early, ensuring the project meets quality standards and user expectations.

10.Feedback Mechanism: Establish mechanisms for gathering feedback from stakeholders, users, and team members throughout the design and development lifecycle to iterate and improve upon the project continuously.

###  Coding Standards

1.Naming Conventions: Use descriptive and meaningful names for variables, functions, classes, and other identifiers. Follow a consistent naming convention, such as camelCase or snake_case.

2.Indentation and Formatting: Use consistent indentation (spaces or tabs) and formatting (e.g., braces placement, line length) to enhance code readability and maintainability.

3.Comments and Documentation: Include comments to explain the purpose of code blocks, complex algorithms, and non-obvious logic. Document functions, classes, and modules using docstrings to provide usage instructions and clarify behavior.

4.Code Organization: Organize code into logical modules, packages, and directories. Follow a modular and hierarchical structure to facilitate code reuse, scalability, and maintainability.

5.Error Handling: Implement robust error handling mechanisms to gracefully handle exceptions and errors, providing informative error messages and logging for debugging purposes.

6.Code Reusability: Write reusable code by breaking functionality into small, cohesive functions and classes. Avoid duplication of code and favor composition over inheritance.

7.Testing Standards: Write unit tests to verify the correctness of individual components and integration tests to validate the interactions between components. Follow test-driven development (TDD) or behavior-driven development (BDD) practices to ensure code quality and reliability.

Performance Optimization: Optimize code performance by minimizing computational complexity, avoiding unnecessary resource allocation, and utilizing efficient algorithms and data structures.

###  Testing Standards

1.Test Planning: Develop a comprehensive test plan outlining the testing approach, objectives, scope, resources, and timelines. Identify test scenarios, test cases, and testing environments based on project requirements and priorities.

2.Test Case Design: Design test cases covering functional requirements, edge cases, boundary conditions, error handling scenarios, and user interactions. Ensure test cases are clear, concise, and traceable to requirements.

3.Test Automation: Automate repetitive and time-consuming test cases using test automation frameworks and tools. Prioritize automation for regression testing, smoke testing, and critical path scenarios to increase efficiency and coverage.

4.Test Execution: Execute test cases systematically, recording test results, observations, and defects in a test management system. Perform both manual and automated testing across various platforms, browsers, and devices as needed.

5.Regression Testing: Conduct regression testing to verify that recent code changes do not adversely affect existing functionality. Prioritize regression test suites based on criticality and frequency of code changes.

6.Performance Testing: Evaluate system performance, scalability, and responsiveness under different load levels using performance testing tools. Identify and address performance bottlenecks, memory leaks, and resource utilization issues.

7.Security Testing: Perform security testing to identify vulnerabilities, weaknesses, and threats in the software application. Conduct penetration testing, vulnerability scanning, and code analysis to enhance security posture.

8.Usability Testing: Validate the user interface design, navigation flow, and overall user experience through usability testing. Gather feedback from end-users to identify usability issues and areas for improvement.

9.Compatibility Testing: Ensure compatibility across different platforms, operating systems, browsers, and devices. Test for cross-browser compatibility, screen resolutions, accessibility, and localization requirements.

10.Integration Testing: Validate the interactions and interfaces between software modules, components, and third-party systems through integration testing. Verify data exchange, communication protocols, and error handling between integrated components.

11. Acceptance Testing: Conduct acceptance testing with stakeholders to validate that the software meets specified requirements and business goals. Obtain sign-off from stakeholders before deploying the software to production.


## Conclusion and Future Scope

### Conclusion

The success of our Parkinson's disease detection model, leveraging Support Vector Machine (SVM) with hyperparameter tuning to achieve an accuracy of 94.91%, represents a significant milestone in the realm of medical diagnostics. This remarkable accuracy not only demonstrates the model's robustness but also underscores its potential as a valuable tool for early detection and intervention in Parkinson's disease cases. By accurately distinguishing individuals with Parkinson's disease from those without, our model offers healthcare professionals a reliable means of identifying the condition in its early stages, facilitating prompt treatment and management strategies.

Moreover, the implications of such high accuracy extend beyond individual patient care. Early diagnosis of Parkinson's disease can contribute to broader research efforts aimed at understanding the disease's progression, identifying risk factors, and developing targeted therapies. By providing clinicians and researchers with a precise and efficient diagnostic tool, our model has the potential to catalyze advancements in Parkinson's disease research and ultimately improve patient outcomes.

Looking ahead, further refinement and validation of the model are essential to ensure its reliability and effectiveness across diverse patient populations and clinical settings. This involves ongoing evaluation of the model's performance using independent datasets, as well as collaboration with medical professionals to integrate the model into clinical workflows seamlessly. Additionally, continued exploration of advanced machine learning techniques and incorporation of additional features or biomarkers may enhance the model's predictive power and versatility.

In summary, our Parkinson's disease detection model represents a significant step forward in leveraging machine learning for medical diagnostics. With its impressive accuracy and potential impact on patient care and research, the model stands as a testament to the transformative potential of data-driven approaches in healthcare. By continuing to innovate and collaborate, we can harness the full potential of this model to advance our understanding and management of Parkinson's disease and improve the lives of those affected by it.

###	Future Scope:

The future scope for our Parkinson's disease detection model, which leverages Support Vector Machine (SVM) with hyperparameter tuning to achieve an impressive accuracy of 94.91% with a dataset comprising 59 data points, holds immense potential for further advancement and impact. Some avenues for future exploration and enhancement include:

1. *Expansion of Dataset*: Increasing the size and diversity of the dataset by collecting data from multiple sources and incorporating various demographic factors, genetic markers, and biomarkers associated with Parkinson's disease. This would enable the model to learn from a broader range of patient profiles and improve its generalization capability.

2. *Feature Engineering*: Exploring advanced feature engineering techniques to identify novel biomarkers or combinations of features that contribute significantly to the accurate detection of Parkinson's disease. This could involve leveraging techniques such as feature selection, dimensionality reduction, and signal processing to extract informative features from raw data.

3. *Fine-Tuning Hyperparameters*: Continuously refining the hyperparameter tuning process to optimize the model's performance further. This includes exploring different kernel functions, regularization parameters, and optimization algorithms to fine-tune the SVM model for better accuracy, precision, and recall.

4. *Ensemble Learning Approaches*: Investigating ensemble learning approaches such as bagging, boosting, and stacking to combine multiple SVM models or other classifiers effectively. Ensemble methods can enhance the model's robustness and stability by leveraging diverse models and capturing different aspects of the data.

5. *Integration with Clinical Systems*: Integrating the Parkinson's disease detection model into existing clinical systems and workflows to facilitate seamless adoption by healthcare professionals. This would involve developing user-friendly interfaces, interoperability with electronic health records (EHRs), and compliance with regulatory standards and guidelines.

6. *Real-Time Monitoring and Prediction*: Extending the model's capabilities to enable real-time monitoring and prediction of Parkinson's disease progression or response to treatment. This could involve deploying the model on edge devices or cloud platforms to analyze streaming data from wearable sensors or remote monitoring systems.

7. *Collaboration with Healthcare Providers*: Collaborating closely with healthcare providers, researchers, and patient advocacy groups to validate the model's performance in clinical settings, conduct prospective studies, and gather feedback for continuous improvement. This would ensure the model's relevance, accuracy, and usability in real-world healthcare scenarios.

8. *Ethical and Regulatory Considerations*: Addressing ethical and regulatory considerations related to data privacy, patient consent, algorithm transparency, and bias mitigation. Ensuring compliance with regulatory frameworks such as GDPR, HIPAA, and FDA regulations is essential to maintain trust and accountability in healthcare AI applications.

By pursuing these avenues for future scope, our Parkinson's disease detection model has the potential to become a valuable tool for early diagnosis, personalized treatment, and improved management of Parkinson's disease, ultimately benefiting patients, healthcare providers, and society as a whole.


## REFERENCES

1)https://www.kaggle.com/datasets/sagarbapodara/Parkinson's-csv

2)https://github.com/Abis47/Parkinson's_Detection-KNN_WebApp

3)https://archive.ics.uci.edu/dataset/174/Parkinson'ss

4)https://www.sciencedirect.com/science/article/pii/S1877050923000078


### NOTE: This project was created for academic usage by:

<a href="https://github.com/Shantanuubasu">Shantanuubasu</a>
<a href="https://github.com/ankit221209">Ankit Ghosh</a>
<a href="https://github.com/ChaitanyaPunja">Chaitanya Punja</a>
<a href="https://github.com/Sashank08">Sashank Patnaik</a>
<a href="https://github.com/Sayanjones">Sayan Mandal</a>


