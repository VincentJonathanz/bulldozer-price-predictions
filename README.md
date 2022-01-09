# Bulldozer Price Predictions 
 Price prediction powered by machine learning is one of the most powerful tools in any company’s toolkit.
 
 Because automated price forecasting can help you stay in sync with your market and, ultimately, improve the effectiveness of your sales process.

 In this project we're going to predict the sale price of a particular piece of heavy equiment at auction based on it's usage, equipment type, and configuration with machine learning.

## Setup
0.Install Anaconda or Miniconda [here](https://docs.anaconda.com/anaconda/install/)
 
1.Clone the repository, and navigate to the downloaded folder.
```
git clone https://github.com/VincentJonathanz/bulldozer-price-predictions.git
```
2.Create and activate enviroment.
   - **Anaconda Prompt**:
      ```
      conda env create --prefix ./env -f enviroment.yml
      conda activate bulldozer-price-predictions/env
      ```
      
   - **Powershell** (you need to run this command first then run the command above):
      ```
      conda init powershell
      Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
      ```
      
3.Start Jupyter
``` 
jupyter notebook
```



