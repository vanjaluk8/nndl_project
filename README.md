# nndl_project


# UVOD

Ovaj projekt zamišljen je da odrađuje klasifikaciju sličica nogometaša iz Prve hrvatske nogometne lige. Koristi ručno prikupljen dataset raspoređen u 10 klasa (ukupni broj klubova koji su igrali u sezoni 2023/2024.)

# KOJI RESURSI SU POTREBNI?
1. python verzije 3.9
2. virtualenv u koji će pip instalirati sve potrebne podatke
3. juypter server
4. CUDA podrška ako se koristi GPU
5. u slučaju da se notebook vrti na neGUI serveru za prikaz plotova treba odraditi slijedeće
```
import os
os.environ.pop('MPLBACKEND', None)
import matplotlib
matplotlib.use('Agg')  
%matplotlib inline 
import matplotlib.pyplot as plt
```


# KAKO SE KORISTI NOTEBOOK?

Potrebno je pratiti upute i izvršavati red po red.

# KAKO JE SLOŽEN NOTEBOOK?

## 1. PRIPREMA I DATASET
### PRIREMA OKOLINE
### DATASET
#### PREUZIMANJE PODATAKA LOKALNO
### PRIPREMA PODATAKA
## 2. MODELI
### ALPHA
### BETA
### GAMA
### DELTA
### EPSILON
### TRANSFER LEARNING
## 3. TESTIRANJE MODELA
### TESTIRANJE EPSILON MODELA
### TESTIRANJE TRANSFER LEARNING MODELA