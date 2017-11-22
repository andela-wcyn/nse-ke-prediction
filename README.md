# nse-ke-prediction
Project using Linear Regression to predict stock prices from NSE in Kenya

### Prerequisites
- You should to run this code in a virtual environment
- The project has been tested with python 2.7, but you could try out python 3

### How to Run it

Make sure you are at the root of the project repo
```
$ cd nse-stock-prediction/
```

Install all the requirements:
```
$ pip install -r requirements.txt
```

Run this command to set up an IPython kernel for your virtual environment:
```
$ python -m ipykernel install --user --name <your ENVNAME> --display-name "Python (whatever you want to call it)"
```
The display name is what you will pick on the list of kernels when you run the jupyter npotebook.

Finally, run:
```
jupyter notebook
```
This will open up the directory in your default browser. Click the IPython notebook named `nse-stock-prediction.ipynb`. The notebook will open up in a new tab.
Here, it may ask you to select a kernel. Choose the kernel whose name you had indicated in the earlier command.

If not prompted to choose a kernel, you can confirm the kernel being used by looking at the top right corner of the notebook. You should see the kernel you created earlier.

To change the kernel go to the Main Menu > Kernel > Change Kernel, then click on the kernel you would like to change to.

That's all.