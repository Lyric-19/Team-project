# Team-project

Project objective: According to the voltage image output by the heart simulator, judge whether there is phase base point and predict the position of phase base point


Project content: 1. Data preprocessing: divide the data set and extract labels from the probe voltage value and timestamp file output by the heart simulator, and take the 2d probe voltage image as a unit in 10ms, perform unit cutting based on the probe coordinates of x axis and the probe coordinates of Y axis respectively to obtain the unit columns of X axis and Y axis. 2. Feature extraction: feature extraction in time domain and phase of X-axis and Y-axis element columns respectively. 3. Training model: Two random forest models are used to classify the x axis probe coordinates and y axis probe coordinates of the training set respectively, and make predictions in the validation data set.
Responsibilities: promoting project progress, assigning specific code modules and report contents, writing core code modules and writing part of project reports.


Project Gains: Compared common models such as random forest, Unet and CNN in image processing, mastered the application of random forest model and the complete process of data analysis, and accumulated the research process and corresponding project management experience of related projects.
