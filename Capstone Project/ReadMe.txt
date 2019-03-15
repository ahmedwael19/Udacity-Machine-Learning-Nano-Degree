All the libraries used


requests # This library is used to make requests to internet
zipfile # to unzip the dataset
random # to have a constant random feed
import zipfile # to unzip the dataset
import glob # Get images paths to be in a list
numpy # to work with arrays and matrices
pandas # data processing, CSV file I/O (e.g. pd.read_csv)
train_test_split ## sklearn library
confusion_matrix ## to get a heatmap
import cv2    ## image manipulation      
seaborn # visualization
%matplotlib inline # for plotting
matplotlib.image # image reading
matplotlib.pyplot# for plotting purposes
import random # to have a constant random feed
Path ## To have the path of all the directories
## keras imports #
from keras.models import load_model
from keras import  metrics
from keras.utils import np_utils 
from keras.utils import to_categorical
from keras.models import Sequential
from keras.layers import Conv2D, MaxPooling2D,GlobalAveragePooling2D,Flatten,SeparableConv2D,BatchNormalization
from keras.layers import Activation, Dropout, Dense
from keras.applications.resnet50 import ResNet50
from keras.preprocessing import image  
from keras.models import Sequential
from keras.callbacks import ModelCheckpoint  
from keras.applications.resnet50 import preprocess_input, decode_predictions
from keras.utils import np_utils 
from keras.preprocessing.image import ImageDataGenerator, array_to_img, img_to_array, load_img
from keras.callbacks import ModelCheckpoint, EarlyStopping
from keras.optimizers import Adam


## Downloading the dataset can be done using the first line in the project
!wget --header='Host: storage.googleapis.com' --header='User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/72.0.3626.121 Safari/537.36' --header='Accept: text/html,application/xhtml+xml,application/xml;q=0.9,image/webp,image/apng,*/*;q=0.8' --header='Accept-Language: en-US,en;q=0.9,ar;q=0.8' --header='Referer: https://www.kaggle.com/' 'https://storage.googleapis.com/kaggle-datasets/17810/23812/chest-xray-pneumonia.zip?GoogleAccessId=web-data@kaggle-161607.iam.gserviceaccount.com&Expires=1552439468&Signature=h%2FZbl7MsQReI9qDHTznpj7PsE%2FnZeOJucVjEbi4GO5QHr%2FfWEA8hH4QeTNFTzkCd2iYdJ%2FNKNXyx2BsakkDHQUXjEGgpE1UI2pj9%2Bq1DB3NhmlEEoFXdzWBjiW0EFHAcCJqY0pIb660dkQxHnyI8%2FMzf%2Fi1kbi3fIX%2FR8V5%2BHOfxnoi8Z7T7P%2FG9jqFpopsAZKHD6oMUm%2FyCcwjMvWnao3nmfZc6kEw2hZCQclLapTLSOh3yyzuekMQuwbY70W%2BT4yK7IgZCoS9TijCQ6IoQO3B4VbU3VLLs2mrRqqT8l6XL1t%2FZ7rTTDClHLCslDz5egB4fn0M3JidHtMA%2BFRufJA%3D%3D' -O 'chest-xray-pneumonia.zip' -c