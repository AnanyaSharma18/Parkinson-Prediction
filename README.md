# Parkinson-Prediction
Using Python and its Libraries we are detecting which of the subjects have Parkinson and which do not. The libraries used are:
1. **Numpy**:
   NumPy is a Python library used for working with arrays.It also has functions for working in the domain of linear algebra and matrices. It is an open-source project and you can use it freely.
2. **Pandas**:
   Pandas is a software library written for the Python programming language for data manipulation and analysis. In particular, it offers data structures and operations for manipulating numerical tables and time 
   series.
3. **SkLearn**:
   The most effective and reliable Python machine learning library is called Skearn (Skit-Learn). Through a Python consistency interface, it offers a variety of effective tools for statistical modeling and machine 
   learning, including classification, regression, clustering, and dimensionality reduction.
4. **SVM**:
   SVMs are utilized in web pages, intrusion detection, face identification, email categorization, gene classification, and handwriting recognition, among other applications. We utilize SVMs in machine learning for 
   some reasons, including this. Both classification and regression on linear and non-linear data are supported.
## Context
Parkinson’s Disease (PD) is a degenerative neurological disorder marked by decreased dopamine levels in the brain. It manifests itself through a deterioration of movement, including the presence of tremors and stiffness. There is commonly a marked effect on speech, including dysarthria (difficulty articulating sounds), hypophonia (lowered volume), and monotone (reduced pitch range). Additionally, cognitive impairments and changes in mood can occur, and risk of dementia is increased.
## Training and Testing
We used the training and testing split method for the model. We split the data into an 80:20 ratio where we used 80% for training data and 20% for testing data.
## Dataset Information
### Attrinute Info:
* name - ASCII subject name and recording number
* MDVP:Fo(Hz) - Average vocal fundamental frequency
* MDVP:Fhi(Hz) - Maximum vocal fundamental frequency
* MDVP:Flo(Hz) - Minimum vocal fundamental frequency
* MDVP:Jitter(%),MDVP:Jitter(Abs),MDVP:RAP,MDVP:PPQ,Jitter:DDP - Several
* measures of variation in fundamental frequency
* MDVP:Shimmer,MDVP:Shimmer(dB),Shimmer:APQ3,Shimmer:APQ5,MDVP:APQ,Shimmer:DDA - Several measures of variation in amplitude
* NHR,HNR - Two measures of ratio of noise to tonal components in the voice
* status -
   *  Health status of the subject (one)
   *  Parkinson's, (zero) - healthy
* RPDE,D2 - Two nonlinear dynamical complexity measures
* DFA - Signal fractal scaling exponent
* spread1,spread2,PPE - Three nonlinear measures of fundamental frequency variation

### Graphical Representation :

![Screenshot (462)](https://github.com/AnanyaSharma18/Parkinson-Prediction-Using-ML/assets/158341446/3a85a744-699f-4ef2-b0ab-905c2800b8cd)

![Screenshot (461)](https://github.com/AnanyaSharma18/Parkinson-Prediction-Using-ML/assets/158341446/978dc122-66eb-4336-8dbd-32c8565808a2)
