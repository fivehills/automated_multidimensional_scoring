# english_essay_grading

https://huggingface.co/Kevintu/Engessay_grading_ML

This model is primarily designed for the automatic grading of English essays, particularly those written by second language (L2) learners. The training dataset used is the English Language Learner Insight, Proficiency, and Skills Evaluation (ELLIPSE) Corpus. This freely available resource comprises approximately 6,500 writing composition samples from English language learners, each scored for overall holistic language proficiency as well as analytic scores pertaining to cohesion, syntax, vocabulary, phraseology, grammar, and conventions. The scores were obtained through assessments by a number of professional English teachers adhering to rigorous procedures. The training dataset guarantees that our model acuqires high practicality and accuracy, closely emulating professional grading standards.

The model's performance on the test dataset, which includes around 980 English essays, is summarized by the following metrics: 'accuracy'= 0.87 and 'f1 score' = 0.85.

Upon inputting an essay, the model outputs six scores corresponding to cohesion, syntax, vocabulary, phraseology, grammar, and conventions. Each score ranges from 1 to 5 or 1 to 10, with higher scores indicating greater proficiency within the essay. These dimensions collectively assess the quality of the input essay from multiple perspectives. The model serves as a valuable tool for EFL teachers and researchers, and it is also beneficial for English L2 learners and parents for self-evaluating their composition skills.
