# city_cars
In the neroset_model will be using lr.pth and lr_1pth. This models will be using correlation method.
Base:
System - Ubuntu20.04.06lts
System - Ubuntu22.04.05lts
System - Ubuntu24.04.01lts
Programming environment - Python3.8.10.2.12
Programming environment - Python3.9.5.3
Programming environment - Python3.10.12.3
Programming environment - Python3.11.0-rc2
Programming environment -Python3.12.3
Install:
Command for install Python:
sudo apt install python3.8
sudo apt install python3.9
sudo apt install python3.10
sudo apt install python3.11
sudo apt install python3.12
Check version Python:
Python3 --version
Command for install pip:
sudo apt install python3-pip
Check version Python:
Python3 --version
Check version pip:
pip3 --version
Others.
Install:
pip3 install numpy
pip3 install pandas
pip3 install scikit-learn
pip3 install tqdm
pip3 install torch
Check install python-libs:
command python3.8
command python3.9
command python3.10
command python3.11
command python3.12
import numpy
import numpy as np
import pandas
import pandas as pd
import sklearn
import tqdm
import torch
Base:
https://www.kaggle.com/datasets/ananaymital/us-used-cars-dataset
License:
Data files © Original Authors
Database:
car.csv
car.zip # due to storage limitation of the github.com necessary of theorchive file.
30 values('listing_id', 'sp_name', 'listed_date', 'back_legroom', 'front_legroom', 'year', 'body_type', 'engine_cylinders', 'engine_displacement', 'engine_type', 'fuel_tank_volume', 'fuel_type','horsepower', 'height', 'length', 'width', 'model_name', 'major_options', 'maximum_seating', 'wheelbase', 'wheel_system', 'wheel_system_display', 'transmission', 'transmission_display', 'sp_name', 'power', 'price', 'city_fuel_economy', 'city', 'make_name')
450000 strings
target = make_name
Models:
lr.pth
lr_1.pth
File:
body_type.csv
city.csv
engine_cylinders.csv
engine_type.csv
fuel_type.csv
major_options.csv
make_name.csv
maximum_seating.csv
model_name.csv
power.csv
sp_name.csv
transmission.csv
transmission_display.csv
wheel_system.csv
wheel_system_display.csv
