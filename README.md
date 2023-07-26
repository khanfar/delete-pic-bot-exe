# delete-pic-bot-exe


# Khanfar Deletion Bot

![Screenshot 2023-07-27 012140](https://github.com/khanfar/delete-pic-bot-exe/assets/16803586/e9793d17-353c-4942-8a78-22c0e2509b26)


The Khanfar Deletion Bot is a Python-based application that automates the process of deleting images from a specified directory. It provides a graphical user interface (GUI) for easy interaction and control. 

## Features

1. **Automated Deletion**: The bot automatically deletes images from the specified directory based on the time frame set by the user.

2. **Custom Time Frame**: Users can set a custom time frame for deletion. The bot supports time frames in seconds, minutes, and hours.

3. **Directory Selection**: Users can choose the directory for deletion. They can use the current path, browse to a new path, or use a saved path.

4. **Deletion Counter**: The bot keeps a count of the number of images deleted, which is displayed in the GUI.

5. **Status Updates**: The bot provides status updates in a terminal box within the GUI. The terminal box displays messages such as the deletion status of each image, errors, and other relevant information.

6. **Start/Stop Control**: Users can start or stop the deletion process at any time using the Start and Stop buttons in the GUI.

7. **Dark Theme**: The bot features a dark-themed GUI for a comfortable user experience.

## Installation and Setup

The Khanfar Deletion Bot requires Python 3 and the following Python libraries:

- tkinter
- threading
- queue
- pickle

You can install Python 3 from the official Python website. Once Python is installed, you can install the required libraries using pip, which is a package manager for Python. Open a terminal or command prompt and run the following command:

```bash
pip install tkinter threading queue pickle
```

After installing the required libraries, you can run the bot by executing the Python script. 

Please note that the bot will only delete images with the extensions .jpg and .jpeg. Make sure to back up important images before running the bot.

## Usage

To use the bot, follow these steps:

1. Run the Python script to launch the GUI.
2. Enter the time frame for deletion in the provided field and select the unit (seconds, minutes, or hours) from the dropdown menu.
3. Select the directory for deletion. You can use the current path, browse to a new path, or use a saved path.
4. Click the Start button to start the deletion process. The bot will start deleting images from the specified directory based on the set time frame.
5. You can stop the deletion process at any time by clicking the Stop button.
6. The terminal box in the GUI will display status updates and the number of images deleted.

## Disclaimer

Please use this bot responsibly. The bot will permanently delete images from the specified directory. Always make sure to back up important images before running the bot. The developer is not responsible for any loss of data.
