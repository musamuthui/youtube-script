# Getting Started

- Clone this repository to your local machine:
```bash
git clone https://github.com/musamuthui/youtube-script.git
```

- Navigate to the project directory:

```shell
cd /path/to/your/project/youtube-script
```

- Create the virtual environment:
    
    On Windows:
    ```powershell
    python -m venv .venv
    ```

    On Linux or Mac:
    ```bash
    python3 -m venv .venv
    ```

- Activate the virtual environment

    On Windows:
    ```powershell
    .venv\Scripts\Activate.ps1
    ```

    On Linux or Mac:
    ```bash
    source .venv/bin/activate
    ```

- Install the required packages:
```python
pip install -r requirements.txt
```

- Install ffmpeg on your machine (Windows/MacOS or Linux) for the script to work
```
https://www.ffmpeg.org/download.html
```

- To run:
    
    On Windows:
    ```powershell
    python script.py
    ```

    On Linux or Mac:
    ```bash
    python3 script.py
    ```

- To deactivate the virtual environment:
```python
deactivate
```

# Note 
- The video quality is in 1080p but may be unavailable for videos uploaded without that quality.

- The videos are stored in the same folder not in your set downloads folder.

- The version of packages may be latest than what is given in the ```requirements.txt``` and are the user is advised to use the latest versions of the packages for compatibility.

- Use of yt-dlp to download YouTube videos without the video creators' copyright permission may be illegal in several jurisdictions.
