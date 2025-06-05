# Question - Answering Using BART

# Proposed Model Arcitecture
![image](https://github.com/user-attachments/assets/58fa0e99-e1e7-4a42-8e37-9e3c81143811)

# Work Flow
![image](https://github.com/user-attachments/assets/23fce956-9818-4737-a2b5-4c612b0a7f11)

# Result 
![image](https://github.com/user-attachments/assets/f818cf1e-2c46-4816-ae6b-ad5afaf3b4bb)


## Train
```bash
   !python -m main --data_path=/kaggle/working/data/train_data_name.pkl --checkpoint_interval=100
```

## Inference
```bash
   !python -m modules.inference 
```

!python -m main --data_path=/kaggle/input/synthetic-personachat/valid.pkl --validation_path=/kaggle/input/synthetic-personachat/valid.pkl --learning_rate=1e-5


