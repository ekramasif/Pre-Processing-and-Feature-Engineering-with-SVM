# Pre-Processing-and-Feature-Engineering-with-SVM

# General remarks
This assignment is meant to get your acquainted with Support Vector Machines (SVM). You
will also have to explore Pre-processing and Feature contribution quite a bit further (as
explained throughout the Lab classes). Additionally, you’re encouraged to experiment a
little further with report writing, by making your own choices and presenting it as a paper
like format if possible.
For the practical parts, you are asked to train and test a few models using SVM, and produce
what you think the best settings are for the data we’re using. Use the dataset (corona_data)
that we have used during our lab class. Note that you have to show the results based on
the big dataset. That is, you have to train your model using the “train.tsv” and the evaluation
of your final model would be based on the “test.tsv”. However, for tweaking your models,
you may use the small datasets.

# Default settings:
Run a support vector machine with a linear kernel on the multiclass classification
(cls = svm.SVC(kernel=’linear’, C=1.0). Use default settings and report results using
the portion of the test/development set. Just make sure you document what you have done
along with the results.

Reporting the Results (Evaluation Metrics):
As evaluation, you will have to report on the overall Accuracy as well as the class-wise
Precision/Recall and F1 score. Additionally, also include confusion metrics for each of your
experimentation. Please do not just put the results in the report. Try to explain a bit about
why you might thing the results have improved/degraded from the previous experiment(s).


# Output:
          Reading The Dataset...

          Training the Classifier...
          SVM Accuracy =  0.4

                              precision    recall  f1-score   support

          Extremely Negative      0.479     0.240     0.320       146
          Extremely Positive      0.591     0.340     0.431       162
                    Negative      0.381     0.483     0.426       302
                     Neutral      0.453     0.414     0.433       152
                    Positive      0.324     0.424     0.367       238

                    accuracy                          0.400      1000
                   macro avg      0.446     0.380     0.396      1000
                weighted avg      0.427     0.400     0.399      1000

          Naive Bayes Accuracy =  0.269

                              precision    recall  f1-score   support

          Extremely Negative      0.296     0.199     0.238       146
          Extremely Positive      0.272     0.136     0.181       162
                    Negative      0.335     0.255     0.289       302
                     Neutral      0.246     0.474     0.324       152
                    Positive      0.232     0.290     0.257       238

                    accuracy                          0.269      1000
                   macro avg      0.276     0.271     0.258      1000
                weighted avg      0.281     0.269     0.262      1000
