# Introduction and Motivation

In this project, our goal is to develop models that uses EEG brainwave patterns and hand movement data for real-time stimulus detection. Integrating these biometric indicators would help create a responsive system that can enhance gaming experiences. Additionally, it has the potential to greatly improve assistive technologies and support the functional needs of individuals with disabilities. This approach would facilitate interactive technology and accessibility, making digital environments more intuitive and inclusive.

However, our project faces some challenges, particularly with the noise in EEG data, such as segments before and after videos that introduce irrelevant information. This issue reduces our model's ability to learn meaningful patterns from the EEG signals. Additionally, the limited size of the Emotiv dataset restricts model’s ability to generalize EEG signal patterns and draw reliable conclusions.

Moving forward, we would explore the Neurosky dataset and employing various feature extraction and data augmentation strategies. We will also experiment with different neural network architectures, such as artificial neural networks , which may be more suitable for the Neurosky data. Furthermore, we would like to discover more diverse categories of outcomes and see if there are any other important positions, and we would implement unsupervised learning models, which would open up new possibilities for applications in dynamic and responsive technologies.

# EmoSync: Real-Time Stimulus Recognition and Prediction through EEG and Hand Movement Analysis

## Data
Original dataset is comming from [Brain Signals And The Corresponding Hand Movement Signals Dataset (BS-HMS-DATASET)](https://ieee-dataport.org/open-access/brain-signals-and-corresponding-hand-movement-signals-dataset-bs-hms-dataset). Given that the original dataset required some refinement, we conducted a thorough preprocessing of the data, which is now stored in the Data folder for further analysis.

  ### Emotiv
  We utilize data obtained from Emotiv devices, interpreting column meanings directly from the Emotiv website to ensure accurate data handling. After clarifying the column names and data structure, we have neatly organized and stored the files in the "Emotiv EEG" directory. For instance, a file named EEG_Test0_1.csv indicates data from the first individual ("Test0"), with '1' denoting the first session and the first activity (watching the first video). Each participant can generate up to eight files, reflecting two sessions where each session encompasses four distinct activities.
