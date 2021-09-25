# MedBot
### Abstract: 

In India, the ratio of doctors to patients is over 10000 to 1 whereas the recommended is 1000 to 1. Due to the same, patients often tend to misjudge the type of doctor they should go to which costs them their time, resources, and they might even compromise on their health in the case there is a misdiagnosis or if the medicines do not work. This amplifies in a relief or medical camp where time is of the essence, doctors are scarce and the patients desperately need help. 

The answer? MEDBOT, an AI based project which suggests you the type of doctor you should go to and also, shows you a list of nearby top doctors on the basis of the symptoms provided by the user. MEDBOT also provides the concerned doctor with the disease the program suspects the patient has to help the doctor diagnose the patient both, accurately and efficiently while maintaining a record of the patient's previous medical records. 

The project has been reviewed and verified by a licenced medical practitioner and has also been tried and tested on a varying group of patients with the model showing an accuracy of 92.3% in disease and doctor suggestion. 

MEDBOT focuses on the accurate diagnosis of a patient and to save the time and resources of both the patient and the doctor majorly in cases like a relief camp where the stakes are very high and the system needs to be as efficient as possible


### Procedure : 

Firstly, the user has to log in to the website(Coded in python using flask) and put in their symptoms and temperature to be diagnosed by the program. 

This data is then fed into Decision Tree and KNN (K-Nearest Neighbours) AI algorithms coded in Python which basically gives an output of which disease it is and which type of doctor to consult. These models were found to be the best fitting for the project after analysing the data and accuracy from each model. The models form groups of possible outcomes and find the best fitting match according to the data provided by the user. The Temperature field acts as a quantitative measure for the user which helps in more accurately diagnosing the patient.

Finally, the type of doctor along with the best doctors in the users area are displayed to the user on the basis of their rating and amount of reviews online. The disease identified by the program is also sent to the selected doctor along with a list of the symptoms provided by the user and the 3 most probable diseases via email to help with the process of diagnosis.  

A kiosk prototype has also been constructed which can be installed in places where there is a lack of medical services and doctors are scarce. The kiosk consists of a LED touch screen and a mini pc (NUC) installed within the kiosk. 


### Findings: 

It was found that the program is 92.3% accurate in suggesting the disease and doctor for the patients on the basis of symptoms provided by them and the dataset has also been validated by a practising professional. The students have found that MEDBOT can help save huge amounts of time and greatly improve the process of diagnosis. It could be really helpful in medical camps where the diagnosis and treatment process needs to be as efficient as possible and misdiagnosing the disease is not an option. 

### Learning Outcome : 

The dataset was made from scratch by the students by reading MBBS Medical Books and verifying the data from various practitioners. Their interest in Artificial Intelligence grew unmeasurably and they truly understood the applications of the technology of the future. The project required meticulous data research and drawing analysis from that data. The Students were truly amazed by what an amazing and vast world can be unlocked by using AI. 
