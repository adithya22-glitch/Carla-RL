# Carla-RL
Reinforcement Learning codebase for self-driving car in Carla

CUDA 11.6 used with Cudnn 8.4.1
Visual studio

1. Edit settings in settings.py
2. Run with train.py
Play.py is under development but its just to play around

Add your own models via sources/models.py

The libraries I used at the time of upload

absl-py                      2.1.0
astunparse                   1.6.3
carla                        0.9.15
certifi                      2022.12.7
cloudpickle                  2.2.1
colorama                     0.4.6
cycler                       0.11.0
flatbuffers                  25.2.10
fonttools                    4.38.0
gast                         0.4.0
google-auth                  2.38.0
google-auth-oauthlib         0.4.6
google-pasta                 0.2.0
grpcio                       1.62.3
gym                          0.21.0
h5py                         3.8.0
idna                         3.10
importlib-metadata           4.13.0
keras                        2.10.0
Keras-Preprocessing          1.1.2
kiwisolver                   1.4.5
libclang                     18.1.1
Markdown                     3.4.4
MarkupSafe                   2.1.5
matplotlib                   3.5.3
numpy                        1.21.6
oauthlib                     3.2.2
opencv-python                4.11.0.86
opt-einsum                   3.3.0
packaging                    24.0
pandas                       1.3.5
Pillow                       9.5.0
pip                          22.3.1
protobuf                     3.19.6
psutil                       7.0.0
pyasn1                       0.5.1
pyasn1-modules               0.3.0
pyparsing                    3.1.4
python-dateutil              2.9.0.post0
pytz                         2025.2
requests                     2.31.0
requests-oauthlib            2.0.0
rsa                          4.9
setuptools                   65.6.3
six                          1.17.0
stable-baselines3            1.6.2
tensorboard                  2.10.1
tensorboard-data-server      0.6.1
tensorboard-plugin-wit       1.8.1
tensorflow-estimator         2.10.0
tensorflow-gpu               2.10.0
tensorflow-io-gcs-filesystem 0.31.0
termcolor                    2.3.0
torch                        1.13.1
urllib3                      2.0.7
Werkzeug                     2.2.3
wheel                        0.38.4
wincertstore                 0.2
wrapt                        1.16.0
zipp                         3.15.0

I downloaded Carla 5 and in the future I will look to downgrade Carla version for more efficient and stable product creation.
A seperate unreal engine 4.26.2 from epicgames will be used for more customisation of environment and also to make it more realistic.
Based on the performed experiment, in my opinion, there is no tweaks in source code that can be done, either on carla seperate unreal engime that will help us in running RL algorithms on these simulator using Nvidia Geforce GTX 1050ti. Much more stronger GPUs are required to get a decent training time or for the training to atleast work