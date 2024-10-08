# MLPDR
### About
Moroccan license plate detection &amp; recognition. Built with YOLOv3 and PyQt. + FLASK 
### Setup
Install [Python](https://www.python.org/downloads/) Use Python 3.8.

Clone this repository, cd to its directory and run the following commands:
```
# Create and activate a new virtual environment
$ python -m venv env

## Windows
$ ./env/Scripts/activate
## Linux
$ source ./env/bin/activate

# Install the project's requirements
$ pip install -r ./requirements.txt
```

Before running the project, you will need the trained weights. Considering the size of the weights and that Git LFS has a monthly limit on bandwidth, you will have to download the latest [release](https://github.com/HamzaEzzRa/MLPDR/releases/tag/v1.0.0-beta) and copy the weights folder to the cloned project.

```
# Run the project
$ python ./main.py
$ python ./api.py # to run the API
$ python ./client.py # client side code to send the picture 
```

### Screenshots
<p align="center">
  <img src="https://i.imgur.com/f7evHhw.png" />  
</p>

<p align="center">
  <img src="https://thumbs2.imgbox.com/d9/5f/uvjtaIeO_t.png" />
  
</p>

### Dataset
The network has been trained on the Moroccan license plate dataset: [https://msda.um6p.ma/msda_datasets](https://msda.um6p.ma/msda_datasets).
