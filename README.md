# Bengali_Ai_Handwritten_Grapheme_Classification
Bengali is the 5th most spoken language in the world with hundreds of million of speakers. It’s the official language of Bangladesh and the second most spoken language in India. Considering its reach, there’s significant business and educational interest in developing AI that can optically recognize images of the language handwritten. This model hopes to improve on approaches to Bengali recognition. Bengali’s alphabet is made up of 11 vowels, 7 consonants, and 168 grapheme roots. This results in ~13,000 different character variations; compared English’s 250 characters variations.
# Installation commands
No specific software is required. Code can be executed in google colaboratory.
# Software/Hardware Requirement
Google colaboratory OR any other notebook which supports Python
# **Instructions to run model**
## Two Methods
### **1.  First Method**

- Download kaggle.json file (already uploaded on Git)
- Open File 'Colab_Model.ipynb' and Start Runing Cells 
- Downloaded kaggle.json file needs to be ulpoaded in Colab
![kuchnhi](https://user-images.githubusercontent.com/47919271/82045498-ce7cc680-96cc-11ea-81cd-0c043754f0b0.PNG)


### **2. Second Method** 

- Download files of folder 'Trained_Model' 
- Download File 'Using_preTrained_Model.ipynb'
- Download Data Set From <a href="https://www.kaggle.com/c/bengaliai-cv19/data" target="_blank">DataSet</a>

# **Keras Sequential Model**
![index](https://user-images.githubusercontent.com/47919271/82033946-1b57a180-96bb-11ea-9abe-890e2c05fc65.png)
# **Result**
## **Loss corresponding to 3 components**
![grapheme](https://user-images.githubusercontent.com/47919271/82035795-a9cd2280-96bd-11ea-9ebe-61de0a385649.PNG)
![vowels](https://user-images.githubusercontent.com/47919271/82035802-ab96e600-96bd-11ea-8e7e-14cc287d22b7.PNG)
![conso](https://user-images.githubusercontent.com/47919271/82035803-acc81300-96bd-11ea-8e3e-51dc9100bd0b.PNG)
## **Accuracy corresponding to 3 components**
![conso_acc](https://user-images.githubusercontent.com/47919271/82035242-e5b3b800-96bc-11ea-8903-319297bbf4b7.PNG)
![grapheme_acc](https://user-images.githubusercontent.com/47919271/82035252-e77d7b80-96bc-11ea-804d-f2cf35e1e9f2.PNG)
![vowels_acc](https://user-images.githubusercontent.com/47919271/82035262-e8aea880-96bc-11ea-97fe-537eea330356.PNG)
### **Kaggle Submission**
![kaggle_submission](https://user-images.githubusercontent.com/47919271/82035501-35927f00-96bd-11ea-90f7-afd3cefbc0f3.PNG)

