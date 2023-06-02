
![image](https://img.shields.io/badge/Python-3.8.9-blue)
![image](https://img.shields.io/github/v/tag/akhi07rx/File-Uploader-for-Google-Drive)
![image](https://img.shields.io/github/repo-size/akhi07rx/File-Uploader-for-Google-Drive)
![image](https://img.shields.io/github/languages/code-size/akhi07rx/File-Uploader-for-Google-Drive)
![image](https://img.shields.io/badge/Google-Drive-brightgreen)
[![GitHub license](https://img.shields.io/github/license/Naereen/StrapDown.js.svg)](https://github.com/akhi07rx/File-Uploader-for-Google-Drive/blob/main/LICENSE)
![image](https://img.shields.io/badge/Made%20with-JUPYTER-orange)
![Safe](https://img.shields.io/badge/Stay-Safe-red?logo=data:image/svg%2bxml;base64,PHN2ZyBpZD0iTGF5ZXJfMSIgZW5hYmxlLWJhY2tncm91bmQ9Im5ldyAwIDAgNTEwIDUxMCIgaGVpZ2h0PSI1MTIiIHZpZXdCb3g9IjAgMCA1MTAgNTEwIiB3aWR0aD0iNTEyIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciPjxnPjxnPjxwYXRoIGQ9Im0xNzQuNjEgMzAwYy0yMC41OCAwLTQwLjU2IDYuOTUtNTYuNjkgMTkuNzJsLTExMC4wOSA4NS43OTd2MTA0LjQ4M2g1My41MjlsNzYuNDcxLTY1aDEyNi44MnYtMTQ1eiIgZmlsbD0iI2ZmZGRjZSIvPjwvZz48cGF0aCBkPSJtNTAyLjE3IDI4NC43MmMwIDguOTUtMy42IDE3Ljg5LTEwLjc4IDI0LjQ2bC0xNDguNTYgMTM1LjgyaC03OC4xOHYtODVoNjguMThsMTE0LjM0LTEwMC4yMWMxMi44Mi0xMS4yMyAzMi4wNi0xMC45MiA0NC41LjczIDcgNi41NSAxMC41IDE1LjM4IDEwLjUgMjQuMnoiIGZpbGw9IiNmZmNjYmQiLz48cGF0aCBkPSJtMzMyLjgzIDM0OS42M3YxMC4zN2gtNjguMTh2LTYwaDE4LjU1YzI3LjQxIDAgNDkuNjMgMjIuMjIgNDkuNjMgNDkuNjN6IiBmaWxsPSIjZmZjY2JkIi8+PHBhdGggZD0ibTM5OS44IDc3LjN2OC4wMWMwIDIwLjY1LTguMDQgNDAuMDctMjIuNjQgNTQuNjdsLTExMi41MSAxMTIuNTF2LTIyNi42NmwzLjE4LTMuMTljMTQuNi0xNC42IDM0LjAyLTIyLjY0IDU0LjY3LTIyLjY0IDQyLjYyIDAgNzcuMyAzNC42OCA3Ny4zIDc3LjN6IiBmaWxsPSIjZDAwMDUwIi8+PHBhdGggZD0ibTI2NC42NSAyNS44M3YyMjYuNjZsLTExMi41MS0xMTIuNTFjLTE0LjYtMTQuNi0yMi42NC0zNC4wMi0yMi42NC01NC42N3YtOC4wMWMwLTQyLjYyIDM0LjY4LTc3LjMgNzcuMy03Ny4zIDIwLjY1IDAgNDAuMDYgOC4wNCA1NC42NiAyMi42NHoiIGZpbGw9IiNmZjRhNGEiLz48cGF0aCBkPSJtMjEyLjgzIDM2MC4xMnYzMGg1MS44MnYtMzB6IiBmaWxsPSIjZmZjY2JkIi8+PHBhdGggZD0ibTI2NC42NSAzNjAuMTJ2MzBoMzYuMTRsMzIuMDQtMzB6IiBmaWxsPSIjZmZiZGE5Ii8+PC9nPjwvc3ZnPg==)





# File Uploader for Google Drive V 1.4.18B

This repository contains a Google Colab notebook that allows you to upload files from a given download link to your Google Drive with real-time progress tracking. The code is written in Python and utilizes the `requests` library for file download and the `tqdm` library for progress tracking.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/akhi07rx/File-Uploader-for-Google-Drive/blob/main/File_Uploader_for_Google_Drive_V_1_217B.ipynb)
<br />

## Features

- Upload files to Google Drive from a download link.
- Real-time progress tracking using a progress bar.
- Preserve the original file name during the upload process.
- Automatically create a destination folder if it doesn't already exist.
- Ability to insert multiple download links: The code now allows the user to enter multiple download links one after the other until they choose to exit the program by typing "exit".

- Option to exit the program: The user can type "exit" to quit the program instead of providing a download link.


<br />

## Screenshots

![image](https://github.com/akhi07rx/File-Uploader-for-Google-Drive/assets/89210430/f215a80d-c5ea-4899-81a5-87a0f7174050)

![image](https://github.com/akhi07rx/File-Uploader-for-Google-Drive/assets/89210430/81241900-87c2-4004-ab1e-b131c6aa97f9)

![image](https://github.com/akhi07rx/File-Uploader-for-Google-Drive/assets/89210430/005edd65-1c32-4bf5-8e1f-0975391ba592)


<br />

## Prerequisites

- Google Colab: This code is designed to be run in a Google Colab notebook. If you don't have one, you can create a new notebook on the [Google Colab](https://colab.research.google.com) platform.

<br />

## How to Use

1. Open the Google Colab notebook.
2. Run each cell in the notebook to execute the code.
3. When prompted, enter the download link of the file you want to upload.
4. The code will upload the file to a folder named "Downloads" in your Google Drive.
5. The progress bar will display the real-time progress of the file upload.

<br />

<hr style="border:2px solid gray">

<br />


1. Mount Google Drive by running the following code in Google Colab:
<br />

```python
from google.colab import drive

drive.mount('/content/drive')
```
<br />

2. Run the script and provide the download link when prompted:
<br />

```python
Enter the download link: [insert download link here]
```

<br />

3. The script will create a folder named downloads in your Google Drive if it doesn't exist already.

4. The file will be downloaded from the provided URL and saved to the downloads folder.

<br />

Please note that the progress of the download will be displayed using a progress bar provided by the tqdm library.

Once the download is complete, the script will print a success message indicating the name of the downloaded file and the destination folder.

Make sure to replace ' [insert download link here] ' with the actual URL from which you want to download the file.

Feel free to modify the destination folder according to your preference by changing the 'destination_folder' variable.


<br />

## Customizing the Destination Folder

By default, the code uploads files to the "downloads" folder in your Google Drive. If you want to upload the files to a different folder, you can modify the `destination_folder` variable in the code to specify the desired folder path.

```python
destination_folder = '/content/drive/MyDrive/your-folder/'
```

<br />

## Code Components
<br />

The main components of the code are as follows:
<br />
<br />


- Mounting Google Drive: This step allows the notebook to access your Google Drive and perform file operations.

- Parsing the Download Link: The download link provided by the user is parsed using the urlparse function to extract the file name. This ensures that the file is saved with its original name.

- Downloading the File: The code uses the requests library to download the file from the provided link. The file is downloaded in chunks to enable real-time progress tracking.

- Uploading the File to Google Drive: The downloaded file is then saved to the specified destination folder in Google Drive. The open function is used to create the file in write binary mode, and the file is written in chunks to ensure efficient upload.

- Progress Tracking: The tqdm library is used to create a progress bar that updates in real time as the file is being uploaded. The progress bar displays the current progress and the total file size.

<br />
<br />

## Limitations
<br />

**This code is designed for uploading files to Google Drive from a download link. It may not be suitable for other file upload scenarios.
The upload speed is dependent on your internet connection and the server's capacity from which you are downloading the file.**

<br />

## License
<br />

This project is licensed under the MIT License.