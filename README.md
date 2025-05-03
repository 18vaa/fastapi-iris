# IRIS Prediction using FastAPI
Implemented an iris flower predictor using ML and served as a RESTful API using FastAPI.

## How to run
You will find the required dependencies in the **requirements.txt** file. To run it, simply execute the following line in your terminal
 - **Windows**
```{bash}
pip install -r requirements.txt
```
- **MacOS/Linux**
```{bash}
pip3 install -r requirements.txt
```

To generate and save model weights, use this command:
```{python}
python train_model.py
```

The server is run using **uvicorn** .
To use the server, run the following command:

```{python}
python app.py
```
You'll see a URL for localhost. I've set the port to ```8000``` but you're welcome to change it as you wish.

I have deployed something similar and deployed it using Streamlit earlier. You can check it out [here](iris-render.streamlit.app) and the github repo can be found [here](https://github.com/18vaa/iris-render) 

## What comes next?
I've been thinking about ways to use React to deploy the API with a nice UI to go with it. I will update this repository in the future if I ever get down to it.

Thanks if you've been reading upto this point!
