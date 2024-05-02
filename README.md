Traditional gaming interfaces, such as keyboards, mice, and controllers, can limit player immersion and exclude individuals with different physical abilities. These interfaces often rely on complex button combinations and manual dexterity, creating a barrier for players with mobility issues or those unfamiliar with gaming hardware. Additionally, conventional gaming setups may promote sedentary behavior, leading to potential health concerns.

Here in this project we will try to develop a gesture recognition system for interactive gaming. Below are the steps:

(i) You first need to create custom data using this link "https://tinyml.seas.upenn.edu/magic_wand_capture.html" and "projectwork.ino" given in this repository.

(ii) Open the .ipynb in google collab. Train and fine tune the model and copy the .cc code created using xxd tool in the notebook.

(iii) Replace that magic_wand_model_data with the contents of .cc codes.Also don't forget to change the label number and the labels.

(iv) compile and and upload the projectwork.ino code to your Arduino Nano BLE 33.

(v) Develop the app and establish the bluetooth communication to recieve the classified gesture and take action accordingly.
