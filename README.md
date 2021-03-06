# nas-streamproof-generator
A stream proof generator for New Artist Spotlight using the scrobbles from Last.fm.

## Usage

The user must input a Last.fm username and the date and time of the last scrobbled track at your last uploaded stream proof image (Using UTC timezone). The script will automatically generate a stream proof image for every 1 hour of listening time. Next time it will remember the date and time for you.


## Setup
To run this project, grab the Windows executable file in the release page, or use the python script directly.

### Windows
Create a virtual environment in the folder you are at:

```
python -m venv venv
```
Activate it:

```
.\venv\Scripts\activate.bat
```

Install the required modules using the requirements.txt file:

```
pip install -r requirements.txt
```

Finally, run the python script:

```
python -m script.py
```
### MacOS
Create a virtual environment in the folder you are at:

```
python -m venv venv
```

Activate it:

```
source venv/bin/activate
```

Install the required modules using the requirements.txt file:

```
pip install -r requirements_MacOS.txt
```

Finally, run the python script:

```
python -m script_MacOS.py
```
