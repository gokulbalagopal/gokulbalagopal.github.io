---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---
[Download Resume](https://gokulbalagopal.github.io/files/Resume_GB.pdf){: .btn .btn--info}
[Download Research Poster](https://gokulbalagopal.github.io/files/Resume_GB.pdf){: .btn .btn--info}

{% include base_path %}

## 📧 Contact
- Email: [gokul3194@gmail.com]()
- LinkedIn: [linkedin.com/in/gokul-balagopal/](https://www.linkedin.com/in/gokul-balagopal/)
- GitHub: [github.com/gokulbalagopal/](https://github.com/gokulbalagopal/)


## 💼 Experience
### University of Texas at Dallas
***Research Assistant***

*January 2020 - Present, Dallas, TX*

- Developed a methodology for measuring rapid variations in particulate matter (PM) concentration within an hour, applied in Joppa,one of DFW's most polluted area, using geostatistical   variogram analysis for optimal measurement frequency.
- Achieved measurement intervals of 1-2 minutes in polluted areas, optimizing air quality monitor power usage.
- Utilized the HYSPLIT model for tracking polluted air parcels to identify pollution sources across DFW.
- Enhanced air quality monitoring in low-income neighborhoods by calibrating low-cost sensors with research-grade sensors using machine learning, significantly improving accuracy and reducing costs.
- Implemented stacking regression models with a correlation coefficient of 0.99 for precise PM level prediction, proving more efficient than deep neural networks.
- Created live dashboards with Plotly for real-time data visualization, enabling efficient anomaly detection and sensor management.
*Supervisor: Professor David Lary*

### University of Houston
***Research Assistant***

*August 2017 - August 2018, Houston, TX*

- Conducted neural network analysis on 17 years of Texas air pollution data to predict regional pollution levels based on environmental factors.
- Managed over 200 GB of data for comprehensive analysis.
- Automated Python and R script execution on the Opuntia Cluster using shell scripting for efficient data processing.

*Supervisor: Professor Peggy Lindner*
  
### QBurst
***Software Engineer***

*June 2015 - June 2016, Kerala, India*

- Developed an IoT platform as part of a team of 4 using AngularJS, enabling the connection of machines and sensors to the cloud for advanced monitoring and analytics.
- Implemented data extraction, analysis, visualization, and cloud integration to provide comprehensive insights from device-generated data.
- Contributed to a multi-million-dollar CMS application project for Uniqlo Co. Ltd., focusing on providing APIs for managing promo codes,   popular products, and email communication.
- Led the development of the user interface (UI) and REST-based APIs responsible for managing the distribution of promo code-related information via email.
- Played a crucial role in a CMS application project, estimated at approximately 1.5 million USD, aimed at creating platform-independent components for Uniqlo Co. Ltd websites, based on Google's material design principles.
- Utilized React-Redux scripting to design and generate components with attributes and aspects in alignment with Google's material-UI.
- Worked as a front-end developer using HTML, CSS, and ReactJS on a web application focused on analyzing social media data to gain insights into current trends and public sentiments related to various commercial brands.
- Utilized Facebook and Twitter APIs to provide analytical solutions for raw social media data, contributing to trend analysis and sentiment evaluation.

*Manager: Sunil PK* 


## 🎓 Education
### University of Texas at Dallas
**PhD in Electrical Engineering (STEM), 2024**
- GPA: 3.53/4.00
- Coursework: Big Data and Machine Learning, Statistical Methods in Data Science, Scientific Computing

### University of Houston
**Master's in Electrical Engineering (STEM), 2018**
- GPA: 3.70/4.00
- Dean's Merit Scholarship (for 2 out of 3 attended semesters)
- Coursework: Artificial Intelligence, Automatic Learning and Data Mining
- Certification: High Performace Computing

## 📝 Projects and Articles
### Classification of Deepsat-4 dataset from Kaggle (Python) - [Project Link](https://github.com/gokulbalagopal/DeepSAT)
*Objective: The goal of this project was to classify all the DeepSat4 satellite images into four broad land covers which include barren land, trees, grassland and a class that consists of all land cover classes other than the above three.*
- Processed data with over 4 million data points as batches of 1000s. Reshaped the data to 28 x 28 x 4 format, with Red, Green, Blue and Near InfraRed (NIR) channels.
- Neglected the NIR channels and normalized the data to obtain the color images to obtain clarity on how the satellite images differ.
- Created gray scale images after reshaping the data into 4,000,000 x 28 x 28 x 1 matrix. 
- Singular Value Decomposition (SVD) was used to find that only 10 components were needed to explain more than 90% of the data. These 10 components were taken from the matrix obtained after doing SVD. The count 10 was obtained from the knee point in the SVD plot.
- Red, Blue, Green mean values for each of the images were also used as additional features. 
- Used various machine learning classifiers like Logistic regression, Support Vector, Liner Discriminant Analyzer, Decision Tree, and Random Forest. 
- Best performance of 96% was obtained using Random Forest. 


### Text Mining and Visualization of Factiva-News Paper articles in R - [Project Link](https://github.com/gokulbalagopal/Text-Mining-of-Factiva-Newspaper-article-using-R-programming)
*Objective: My task was to help a journalist with data analysis to investigate the usage of certain words in newspaper articles. Media analysis focuses on text mining and therefore, our data will be text based. The goal is to run topic modeling on the data. We don’t need to know how topic modeling works, since we will just have to run a function.*
- Implemented the pipeline to extract documents from Factiva and generate the corpus.
- Cleaned up the corpus and created a document term matrix.
- Used Latent Dirichlet Allocation topic modelling to classify the data from the document term matrix.
- Classified text contained the most relevant topics.
- Created word clouds that highlights the most important topics.

## 🤖 Skills
- **Programming:** Python (NumPy, Pandas, Scikit-learn, PyTorch), R, SQL, C++, MATLAB, Julia.
- **Data Handling:** Data Visulaization, Data Wrangling, Sentiment Analysis, Summarization.
- **Machine Learning:**  Supervised Learning, Unsupervised Learning, Deep Learning, Reinforcement Learning.
- **Neural Networks:** Convolutional Neural Networks (CNN), Feedforward Neural Networks.
- **Frameworks and Libraries:** TensorFlow, PyTorch, Keras, Scikit-learn, NumPy, Pandas, Matplotlib, ggplot.
- **Data Mining Techniques:** Classification, Clustering, Association Rule Learning, Regression, Neural Networks, Decision Trees, Random Forests, Support Vector Machines (SVM), Principal Component Analysis (PCA), Gradient Boosting Machines (GBM).
- **Natural Language Processing (NLP):** Sentiment Analysis, Summarization.
- **Computer Vision:** Image Classification, Object Detection.
- **Operating Systems:** Unix, Linux, Windows.
- **Version Control Systems:** GitHub, GitLab.
- **Algorithms and DataStructures:** Trees, Graphs, Linked List, Stacks, Arrays, Hashmaps 
- **Distributed Systems:** Opuntia, Europa, Docker.
- **Assembly Language and Low-Level Programming:** Understanding of processor architectures (MSP432, ARM, MIPS).
- **Scripting Languages:** Shell Scripting, Perl.
  
Publications (To Be Puiblished)
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
<!-- Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams -->
