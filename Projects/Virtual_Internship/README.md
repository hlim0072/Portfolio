## Virtual Internships - Predictors of Student Performance based on Text Messages
#### Unit: ADS2001 (2025, Semester 1)

Objective:
- Given chat log data (19,180 messages) from 75 teams that participated in Nephrotex Virtual Internships, we train models to predict student performance (final results on the internship report) and extract the predictive factors of student performance (team-level).

Main outcomes:
- Data manipulation to group data by the 75 teams instead of the original single-message level dataset,
- Natural Language Processing (NLP) to engineer additional features such as the `sentiment` of messages,
- LDA topic modelling to extract recurring topics within teams,
- Achieved 80% testing accuracy on a AdaBoostClassifier with a RandomForestClassifier weak learner.

Findings:
- High-performing teams had more evaluative and decisive language, whereas low-performing teams were more passive,
- Mentoring had little effect on team performance,
- Teams that focused on collaborative experimental testing for their project had better performance.

Please view the Final Report (`ADS2001_FinalReport_VI.pdf`) for the complete report.
