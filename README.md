
# Parkinson's Disease Detection

Parkinson’s disease is a neurological disorder with more than 6 million people worldwide suffering from it.It is commonly diagnosed using clinical assessments and progression scale which usually depends on the medical practitioner’s expertise ,and accuracy varies greatly between various examiners which also takes a long time to accurately diagnose.

# Notebook

Refer to Parkinson's Disease Detection.ipynb for the code.

# Attribute Information:

Matrix column entries (attributes):

1. name - ASCII subject name and recording number

2. MDVP:Fo(Hz) - Average vocal fundamental frequency
3. MDVP:Fhi(Hz) - Maximum vocal fundamental frequency
4. MDVP:Flo(Hz) - Minimum vocal fundamental frequency
5. MDVP:Jitter(%),MDVP:Jitter(Abs),MDVP:RAP,MDVP:PPQ,Jitter:DDP - Several measures of variation in fundamental frequency
6. MDVP:Shimmer,MDVP:Shimmer(dB),Shimmer:APQ3,Shimmer:APQ5,MDVP:APQ,Shimmer:DDA - Several measures of variation in amplitude
7. NHR,HNR - Two measures of ratio of noise to tonal components in the voice
8. status - Health status of the subject (one) - Parkinson's, (zero) - healthy
9. RPDE,D2 - Two nonlinear dynamical complexity measures
10. DFA - Signal fractal scaling exponent
11. spread1,spread2,PPE - Three nonlinear measures of fundamental frequency variation 


## Installation

Install credentials with requirements.txt

```bash
  pip install -r requirements.txt
```
    
## Screenshots

![parkinson](https://user-images.githubusercontent.com/66559862/140806479-322027d2-2c4f-4b7e-b890-020185f120ee.JPG)
![parkinson2](https://user-images.githubusercontent.com/66559862/140806486-721b5e61-df62-44fb-b429-f81da7b443c4.JPG)


