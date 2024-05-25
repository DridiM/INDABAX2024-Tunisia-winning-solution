
# INDABAX DeepLearning 2025 Tunisia Winning solution



The indabaX Tunisia is the most prestigious and challenging deep learning hackathon in Tunisia. The 2024 edition was held at Sup'com on May 18-19, and the challenge focused on object detection in dental imagery. I'm thrilled to share my solution, which achieved the best score in the competition.
![GameChanger-Dental Image Tooth Localization and Numbering Challenge by IndabaX Tunisia 2024](https://github.com/DridiM/INDABAX2024-Tunisia-winning-solution/assets/144357717/c5dc14b9-ec2f-477f-a51e-4c14635a6187)

## Model

The model used is YOLOv8 with stratified k-folds (k = 5).


## Solution
![pipeline](https://github.com/DridiM/INDABAX2024-Tunisia-winning-solution/assets/144357717/b80111a9-d195-4e8e-b0bd-5ee630cfc6df)


## How to use

To run tests, run the following command

```bash
connect to Weights and biases with your account

try:
    api_key = "Enter your WandB API here"
    wandb.login(key=api_key)
except:
    print('If you want to use your W&B account, go to Add-ons -> Secrets and provide your W&B access token. '
          'Use the Label name as wandb_api. \nGet your W&B access token from here: https://wandb.ai/authorize')
  ```
```bash
Import libraries
```
```bash
Run the notebook.
```
## Acknowledgements

 - Special thanks to indabaX and Udini for hosting this challenging hackathon .
