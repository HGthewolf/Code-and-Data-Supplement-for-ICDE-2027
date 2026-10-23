Description of Code and Data Supplement:

We select the "push-up" (named "pushup") and "drunken walking" (named "drunk") actions for demonstration purposes. For more actions, please contact hangeng5446@163.com.

Each action includes RGB videos, images, and CSV files for seven perspectives, with the first six (001 to 006) being fixed perspectives and the seventh (007) being a motion perspective. 

The CSV file contains 2D&3D joint annotations, per-joint visibility states, environmental information, and camera parameters captured for each frame of the video from the corresponding perspective. 

Environmental information for "push-up" and "drunken walking" are:

"push-up": Gender: Female. Weather: Thunder. Time: 22:09. Location: City.

"drunken walking": Gender: Male. Weather: Cloudy. Time: 19:03. Location: Mountain.

We have also uploaded the code for training different backbone models on GTA-MMP. For details regarding the specific configuration and usage of the backbone network in the code, please refer to the documentation for the baseline model, MotionBERT, at: https://github.com/Walter0807/MotionBERT/tree/main. Building on this, we have added code to the "model" folder that allows for the integration of other skeleton-based human action recognition backbone networks.

![Demo 动图演示](https://github.com/HGthewolf/Code-and-Data-Supplement-for-ICDE-2027/edit/main/pushup_001.gif)
