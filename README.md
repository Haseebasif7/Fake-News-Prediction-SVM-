Fake News Detection with SVM
• Overview :
This repository contains a project for detecting fake news using a Support Vector Machine (SVM) model. The dataset used is from a Kaggle competition, and the model achieved an impressive accuracy of 98.9% on the training dataset.

• Preprocessing Steps :
Handling Missing Values
Converted NaN values to empty strings to ensure consistency in text processing.

•Feature Engineering :
Created a new Content column by merging the title and author columns. This combined text was used as the feature for the model instead of the entire text column.

•Text Vectorization:
Used TF-IDF vectorization to convert the text data into numerical form, making it suitable for training the SVM model.

•Stemming :
Applied stemming to normalize words, reducing them to their root form.

•Model Training and Evaluation :

An SVM model was trained on the preprocessed data.
Achieved an accuracy of 98.9% on the training dataset.

•Dataset
The dataset used in this project is from a Kaggle competition. It contains various news articles labeled as fake(1) or real(0).

•Contribution
Contributions are welcome! If you have any improvements or suggestions, please feel free to create a pull request or open an issue. For any questions, you can reach out via the issue tracker.

•Contact
If you have any questions or need further information, please feel free to contact me.
