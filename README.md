# BuildAHackathon
This repo is a space to hold all our data sets, code, and text for the Tech Tank project. We can then roll it up for delivery and upload it to the Tech Tank GitHub along with our deck. Here are the deliverables:

1. Problem text – Text file (.txt) that provides background information, the specific problem, a description of the data, and the format for question submission. This is the problem that will be presented to participants.
2. [Participant data](https://github.com/jgendron/BuildAHackathon/blob/master/Participant Data/) - These are two files that will be provided to the participants.
	* [Training data](https://github.com/jgendron/BuildAHackathon/blob/master/Participant Data/shroom_train.csv) – These are data points that have all the features for each observation, plus the value of the target variable (the quantity you are trying to predict)
	* [Test data](https://github.com/jgendron/BuildAHackathon/blob/master/Participant Data/shroom_test.csv) – These are data points that have all the features for each observation, but no value for the target variable.
3. [Answer key](https://github.com/jgendron/BuildAHackathon/blob/master/Truth Data/shroom_answer_key.csv) – The same data points contained in the test data, but with the value of the target variable. This is often called the truth set. This file will be used internally by the Data Science Expedition platform to evaluate participant submissions.
4. [Scoring script](https://github.com/jgendron/BuildAHackathon/blob/master/Scoring Script/) – A Python script that takes a participant-submitted set of predictions, compares them against the answer key, and returns a quantitative accuracy score. This file is used internally by the Data Science Expedition platform.
5. Configuration file – A text file that contains basic information about the question including category, relevant file paths, total points, and hints. This one seems to be the vaguest, but I think they are just asking for a summary of our submission (what file is which) and hints in case people get stuck with associated penalties.
6. [Solution approach](https://github.com/jgendron/BuildAHackathon/blob/master/Solution Approach/) – A predictive model that can be used to create a submission. This can be written in any language (R, Python, Excel, etc.) using any modeling approach appropriate to the problem. The file is not used by the Data Science Expedition platform or provided to participants. It serves as proof that the question can be solved using the provided data.
