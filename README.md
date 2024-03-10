# StreamDownload

## Overview
YouTube Downloader is a collection of Python scripts facilitating the download of music and videos from YouTube through the YouTube API. The scripts are designed with simplicity in mind, catering to various use cases.

## Features
1. **musicdownload.py**

Download music from YouTube by providing the corresponding URL.

2. **videodownload.py**

Download videos from YouTube using the provided YouTube URL.

3. **streamdownload.py**

Download either music or video based on user preference. The script prompts the user to choose between the two, performs a YouTube search based on user input, and downloads the selected content.

4. **requirement.txt**

Contains the necessary Python packages required to run the scripts. Install dependencies using the following command:

```bash
pip install -r requirements.txt
```
## Usage

Prerequisites
Before running the scripts, make sure you have the required dependencies installed. You can install them using:

```bash
pip install -r requirements.txt
```

### One-Time Music/Video Download (musicdownload.py, videodownload.py)

1. Clone the repository:

´´´bash
git clone https://github.com/your-username/youtube_downloader.git
cd youtube_downloader

2. Run the desired script:

* For music:

```bash
python musicdownload.py
```

* For videos:

```bash
python videodownload.py
```

### Stream Download (streamdownload.py)

1. Clone the repository:

```bash
git clone https://github.com/your-username/youtube_downloader.git
cd youtube_downloader
```

2. Run the script:

```bash
python streamdownload.py
```

## Example

Suppose you want to download content from YouTube based on user input and organize it in your local "Downloads" folder using the streamdownload.py.

1. Clone the repository:

´´´bash
git clone https://github.com/your-username/youtube_downloader.git
cd youtube_downloader
´´´

2. Install dependencies:

´´´bash
pip install -r requirements.txt
´´´

3. Run the script:

´´´bash
python streamdownload.py
´´´

4. Choose between downloading music or video:

´´´bash
Do you want to download 'audio' or 'video': 
´´´

If you choose Music, the script will prompt you to enter a search query and then download the first result.

If you choose Video, the script will prompt you to enter a search query and then download the first video result.
´´´bash
Enter the search query to download: 
´´´

5. The script will download the content and save it in the current working directory or a specified output folder based on your preference.

Now, you have successfully used the streamdownload.py script to download music or video from YouTube based on your input. Customize the script and rules according to your specific needs for an enhanced user experience.

## Contributing

If you find any issues or have suggestions for improvement, feel free to open an issue
