# EmoSync: Real-Time Stimulus Recognition and Prediction through EEG and Hand Movement Analysis

## Motivation
The problem at the heart of emotion recognition and prediction using EEG and hand movement data is the challenge of accurately identifying and anticipating a user's emotional state based on physiological signals. Traditional methods of emotion detection often rely on observable cues such as facial expressions, voice tone, and body language. However, these indicators can be easily masked or misinterpreted, leading to inaccuracies. Furthermore, individuals with certain disabilities may not express emotions in conventionally recognizable ways, which compounds the challenge.

The goal of this project is to leverage the nuanced, physiological signals captured by EEG brainwave patterns and hand movements to create a more accurate, real-time model of emotional state detection. This approach is necessitated by the limitations of current emotion recognition technologies and the potential benefits that more accurate emotional detection systems could bring to a wide range of applications. By understanding the intricate relationship between the brain's electrical activity, hand movements, and emotional states, we can develop models that offer a deeper, more nuanced understanding of human emotions.

## Significance
This project can help enhance user experience in interactive technologies. In gaming and virtual reality, understanding a player's emotional state could lead to adaptive gameplay that changes based on the user's feelings, enhancing engagement and satisfaction. For instance, a game could automatically adjust its difficulty or narrative elements in response to the player's frustration or excitement levels, creating a more personalized and immersive experience.

In addition, this project can improve assistive technologies. For individuals with disabilities, especially those affecting speech and facial expressions, emotion recognition through EEG and hand movements could provide a new means of communication and interaction with technology. This could improve the quality of life for those individuals by enabling assistive devices to better understand and respond to their needs and emotional states.

## Data
Original dataset is comming from [Brain Signals And The Corresponding Hand Movement Signals Dataset (BS-HMS-DATASET)](https://ieee-dataport.org/open-access/brain-signals-and-corresponding-hand-movement-signals-dataset-bs-hms-dataset). Given that the original dataset required some refinement, we conducted a thorough preprocessing of the data, which is now stored in the Data folder for further analysis.

### Emotiv
We utilize data obtained from Emotiv devices, interpreting column meanings directly from the Emotiv website to ensure accurate data handling. After clarifying the column names and data structure, we have neatly organized and stored the files in the "Emotiv EEG" directory. For instance, a file named EEG_Test0_1.csv indicates data from the first individual ("Test0"), with '1' denoting the first session and the first activity (watching the first video). Each participant can generate up to eight files, reflecting two sessions where each session encompasses four distinct activities.
