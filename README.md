# FAKE-PROFILE-DETECTION

The project's main aim is defined in reducing of fake accounts in social network by involving of ANN process. 

The objectives are –

•	To identify of fake accounts in social networks

•	To apply the ANNs through machine learning technique

![image](https://github.com/Prathima5/FAKE-PROFILE-DETECTION/assets/154850398/ab5dee7e-ca83-4302-a7c9-aab63484ccf0)


**PROJECT SCOPE**

In seeing the present condition, online social networks are engaging with most of the people. From child to adult, all are spending a considerable time on these platforms either by exchanging information or making efficient communication with others. But nowadays, these social networking sites are suffering from a lot of fake accounts in taking advantage of vulnerabilities, either taking the benefits or targeting accounts attempting cybercrimes.


**IMPLEMENTATION:**

**MODULES:**

**Module Details:**

1.Upload Social Network Profiles Dataset:

Using this module we will upload dataset to application

2.Preprocess Dataset:

Using this module, we will apply processing technique such as removing missing values and then split dataset into train and test where application use 80% dataset to train ANN and 20% dataset to test ANN prediction accuracy

3.Run ANN Algorithm:

Using this module, we will train ANN algorithm with train and test data and then train model will be generated and we can use this train model to predict fake accounts from new dataset.

4.ANN Accuracy & Loss Graph:

To train ANN model we are taking 200 epoch/iterations and then in graph we will plot accuracy/loss performance of ANN at each epoch/iteration.

5.Predict Fake/Genuine Profile using ANN: using this module we will upload new test data and then apply ANN train model to predict whether test data is genuine or fake.


In regards to this, an "artificial neural network" system has been introduced as a part of the computer system. It is designed for simulating in a way in which the human brain possesses and analyses information.The inductive research approach can be considered for this type. In viewing the existing process and situations this can be observed through the patterns and system regularities. In taking the technical advantage ANN model need to be used effectively. 

It can be described as a foundation of artificial intelligence which will solve the problem in proving the difficulty according to human standards. Therefore "artificial neural networks" (ANNs) are introduced as a process of modeling, allowing the human nervous system through learning technique. 

By depending on the prediction, this detection process is revealing about the "user-level activities”. User influence is also vital in reporting about the abnormalities. The social influence upon users can be assessed with the two types of factors. One is to find the user's impact upon others, and the other is to give the user importance. The evaluation is also based on the "fine-grained feature’.

**System Requirements**

Hardware Requirement
                                
                                System : Pentium IV 2.4 GHz
                                
                                Hard Disk : 40 GB.
                                
                                Floppy Drive : 1.44 Mb.
                                
                                Monitor : 15 VGA Colour.
                                
                                Mouse : Logitech.
                                
                                Ram : 512 Mb.

Software Requirement
                                 
                                 Operating System : Windows
                                 
                                 Coding Language : Python 3.7 



**PROJECT PLAN**

![image](https://github.com/Prathima5/FAKE-PROFILE-DETECTION/assets/154850398/d5d70137-ad00-4350-9634-cd13e1d4f873)

**SYSTEM TEST**

**Unit Testing:** Validates internal logic of individual software units. Tests conducted post-unit completion before integration, focusing on specific business processes.

**Integration Testing:** Ensures integrated software components run seamlessly as one program. Detects issues arising from component combinations through event-driven testing.

**Functional Testing:** Demonstrates systematic adherence to business and technical requirements. Tests include valid and invalid input, exercising functions, and evaluating system outputs.

**System Testing:** Confirms the entire integrated software system meets specified requirements. Emphasizes configuration-oriented system integration tests and pre-driven process links.

**White Box Testing:** Tester has knowledge of software's inner workings and structure. Tests areas inaccessible from a black box level, emphasizing understanding of software internals.

**Black Box Testing:** Tests software without knowledge of inner workings or structure. Inputs and outputs evaluated without consideration of software's internal mechanisms.

**Acceptance Testing:** Critical phase involving end user participation. Ensures the system meets functional requirements. All test cases passed successfully with no defects encountered.

**WORKING OF PROJECT**

To run project double click on ‘run.bat’ file to get below screen

![image](https://github.com/Prathima5/FAKE-PROFILE-DETECTION/assets/154850398/084c2ffd-1d49-4c62-a7ae-f8c21add41b0)

In above screen click on ‘Upload Social Network Profiles Dataset’ button and upload dataset

![image](https://github.com/Prathima5/FAKE-PROFILE-DETECTION/assets/154850398/ae0e2ec2-5f16-4247-8ac8-b8fa884feff6)

In above screen selecting and uploading ‘dataset.txt’ file and then click on ‘Open’ button to load dataset and to get below screen

![image](https://github.com/Prathima5/FAKE-PROFILE-DETECTION/assets/154850398/0d6fb0d4-11c2-455d-8aca-5f754ea008fa)

In above screen dataset loaded and displaying few records from dataset and now click on ‘Preprocess Dataset’ button to remove missing values and to split dataset into train and test part

![image](https://github.com/Prathima5/FAKE-PROFILE-DETECTION/assets/154850398/f6c260a4-d440-42e4-921c-dba1347b0092)

In above screen we can see dataset contains total 600 records and application using 480 records for training and 120 records to test ANN and now dataset is ready and now click on ‘Run ANN Algorithm’ button to ANN algorithm

![image](https://github.com/Prathima5/FAKE-PROFILE-DETECTION/assets/154850398/589e1400-d7b0-41ea-a9e6-12dd042cf5d6)

In above screen we can see ANN start iterating model generation and at each increasing epoch we can see accuracy is getting increase and loss getting decrease.

![image](https://github.com/Prathima5/FAKE-PROFILE-DETECTION/assets/154850398/403b51ce-289c-413d-95b3-12dd888f5040)

In above screen we can see after 200 epoch ANN got 100% accuracy and in below screen we can see final ANN accuracy

![image](https://github.com/Prathima5/FAKE-PROFILE-DETECTION/assets/154850398/5d597897-e8e8-4771-998a-d2513da90dd9)

In above screen ANN model generated and now click on ‘ANN Accuracy & Loss Graph’ button to get below graph

![image](https://github.com/Prathima5/FAKE-PROFILE-DETECTION/assets/154850398/9eb34542-b017-46c0-a642-7422c1874b4d)

In above graph x-axis represents epoch and y-axis represents accuracy/loss value and in above graph green line represents accuracy and blue line represents loss value and we can see accuracy was increase from 0.90 to 1 and loss value decrease from 7 to 0.1. Now model is ready and now click on ‘Predict Fake/Genuine Profile using ANN’ button to upload test data and then ANN will predict below result

![image](https://github.com/Prathima5/FAKE-PROFILE-DETECTION/assets/154850398/174a5eef-bb50-4dd6-b052-cee7da35325d)

In above screen we are selecting and uploading ‘test.txt’ file and then click on ‘Open’ button to load test data and to get below prediction result

![image](https://github.com/Prathima5/FAKE-PROFILE-DETECTION/assets/154850398/a590bfa8-6627-4898-809b-97d86f1ba6e3)

In above screen in square bracket we can see uploaded test data and after square bracket we can see ANN prediction result as genuine or fake
