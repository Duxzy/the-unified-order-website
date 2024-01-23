<!-- PROJECT LOGO -->
<br />
<div align="center">
    <img src="static/TUO-Brand.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">TUO Website</h3>

  <p align="center">
    An awesome README template to jumpstart your projects!
    <br />
    <a href="https://github.com/othneildrew/Best-README-Template"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/othneildrew/Best-README-Template">View Demo</a>
    ·
    <a href="https://github.com/othneildrew/Best-README-Template/issues">Report Bug</a>
    ·
    <a href="https://github.com/othneildrew/Best-README-Template/issues">Request Feature</a>
  </p>
</div>

### Built With

* [![Bootstrap][Bootstrap.com]][Bootstrap-url]

<!-- Installation -->
## Installation

### Virtual environment

Windows: Activate virtual environment with the command
```
tuoenv\Scripts\activate
```
Mac: Activate virtual environment with the command
```
source tuoenv\Scripts\activate
```

Install requirements.txt with pip if needed:
```
$ pip install -r requirements.txt
```

## Project Structure
### Logic 
URL Routes, backend logic, etc. for the moment live in 
```
app.py
```
If we build out some huge app for a bingo we'll add another directory
### HTML Templates
Are called from the templates directory by default in flask applications.
Reference them in ```app.py``` with code:
```return render_template('main/home-page.html')```

### Static Assets
For now let's store static assets in the static directory under an appropriate subdirectory

### Flask App
For local testing run flask in a development state, enables hot reloading:
```
flask --debug run
```