# Zoom Bot
## Script Automate zoom to attend meetings automatically

This is a script in python to automate zoom for attending scheduled meetings automatically.

### Libraries used:
* [Pyautogui](https://pypi.org/project/PyAutoGUI/)
* [subprocess](https://docs.python.org/3/library/subprocess.html)

### Install Requirements

Run the follwing in cmd to install the requirements for the script
Ensure you have python >= 3.5 version
```
pip install subprocess
pip install pyautogui
pip install time
pip install pandas

```

## How to use the script for automating the stuff?
#### Step 1 - Open Schedule.csv and make the following changes
- Write Timings (in 24:00 HR format)
- Enter Meedtingid of the meeting
- Enter meeting password 
- Enter Duration of the meeting in minutes

#### Step 2 - Running the program
- Open CMD or Terminal and direct to the main.py file
- Enter
```
python3 main.py
```
- The program will run and automatically joins the meeting at the scheduled time

## Use Case
Enter Timings,meedtingid,meetingpswd in schedule.csv
![Screenshot 2020-10-29 224216](https://user-images.githubusercontent.com/59971890/97608318-32efd000-1a38-11eb-8f41-2ae1b2d4cb69.png)

Run the program as stated above and zoom window will open up 
![zoomwindow](https://user-images.githubusercontent.com/59971890/97608594-8eba5900-1a38-11eb-89ea-abc99cf73a05.png)

The meeting will start and end according to the specifications gievn by you.