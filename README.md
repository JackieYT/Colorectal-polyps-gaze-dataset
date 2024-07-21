# Colorectal-polyps-gaze-dataset
This colorectal polyps-gaze dataset contains NBI images of colorectal polyps and the corresponding gaze attention images (i.e., gaze attention maps and gaze attention heatmaps). 
All data collection and annotation processes are carried out by following the tenets of the Declaration of Helsinki. 
Firstly, a junior endoscopist retrospectively searched the NBI observation data of colonoscopy at Xiangyang Central Hospital from January 1, 2023, to March 10, 2024. 
The criterion for inclusion is that patients with colorectal polyps must have corresponding pathology reports, that is to say, the pathological examination is the gold standard of the diagnosis. 
According to this criterion, we collected 585 NBI images with colorectal polyps of 87 patients.
Secondly, a senior endoscopist classified the 585 NBI images into three categories based on the NICE classification method. 
During this classification process, the endoscopist’s eye movement information would be recorded and used to generate the gaze attention images. 
Finally, a patient-level data splitting was performed to develop and validate the proposed methods. 
The selected patients and their corresponding images were randomly split into three sets, of which 60% was utilized for training, 20% was used for validation and the rest was utilized for testing. 
In the training and validation sets, we had the original image and the gaze attention images which generated from eye movement information. 
In the test set, only the original NBI images were included to test the actual performance of the trained models. 

