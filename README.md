# File Uploader for Google Drive V 1.217B

This repository contains a Google Colab notebook that allows you to upload files from a given download link to your Google Drive with real-time progress tracking. The code is written in Python and utilizes the `requests` library for file download and the `tqdm` library for progress tracking.


## Features

- Upload files to Google Drive from a download link.
- Real-time progress tracking using a progress bar.
- Preserve the original file name during the upload process.
- Automatically create a destination folder if it doesn't already exist.

<br />

## Screenshots


![image](https://github.com/akhi07rx/test-repo/assets/89210430/1bac0be8-4de5-4d1d-aded-93c3d00f0c33)


<br />

## Prerequisites

- Google Colab: This code is designed to be run in a Google Colab notebook. If you don't have one, you can create a new notebook on the [Google Colab](https://colab.research.google.com) platform.

<br />

## How to Use

1. Open the Google Colab notebook.
2. Run each cell in the notebook to execute the code.
3. When prompted, enter the download link of the file you want to upload.
4. The code will upload the file to a folder named "downloads" in your Google Drive.
5. The progress bar will display the real-time progress of the file upload.

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