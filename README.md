# Complex-SSL-SE

### Software requirements: 
* Python v == 3.6
* Numpy v == 1.19.5 
* torch v == 1.10.1 
* wandb v == 0.12.11
* SoundFile v ==0.10.2
* librosa v ==0.9.1


### Training

python3 train.py --urban_noise False (speech enhancement experiments on the DAPS dataset)

python3 train.py --urban_noise True (speech enhancement experiments on the BBC dataset)
