# NLP_Classification (compairing 3 models)
This NLP classification project focuses on addressing consumer complaints by utilizing machine learning techniques. The dataset, sourced from the Consumer Financial Protection Bureau (CFPB) in the USA, spans from 2022 to 2023, providing a year's worth of substantial data for analysis.

To tackle the classification problem, three different models—LinearSVC, MultinomialNB, and ComplementNB—were considered. The NLP methodology was employed, leveraging the TfidfVectorizer to convert textual data into a numerical format that machine learning models can interpret. The vectorization process considered parameters such as stop_words to eliminate unnecessary words and ngram_range to determine the length of consecutive word sequences in the text.

Each model was incorporated into a separate pipeline, streamlining the process of training and prediction. After comprehensive evaluations, it was determined that LinearSVC exhibited superior performance, achieving an accuracy of 92%. To delve deeper into the model's insights, a confusion matrix and classification report were generated, providing a detailed understanding of actual versus predicted outcomes.

In an effort to enhance predictive capabilities further, a voting classifier was implemented. Through hard voting, this classifier leverages the collective decisions of all machine learning models to forecast the output class based on the highest likelihood of occurrence.

## Lesson Learn
This project not only underscores the efficacy of utilizing NLP techniques for consumer complaint classification but also emphasizes the importance of model selection and comprehensive evaluation metrics for informed decision-making in real-world applications.
