# Music-Tag-Fixer
![Static Badge](https://img.shields.io/badge/project%20status-in%20progress-yellow?style=for-the-badge&logo=github&logoColor=white)

A Python project that uses Spotify API to get data for a music track by its artist name and title.

## Pending
![Static Badge](https://img.shields.io/badge/pending-code-orange?style=flat-square&logo=python&logoColor=white)

- Complete the code.
- Freeze requirments.

![Static Badge](https://img.shields.io/badge/pending-package-orange?style=flat-square&logo=python&logoColor=white)

- Package the project.

![Static Badge](https://img.shields.io/badge/pending-readme-orange?style=flat-square&logo=markdown&logoColor=white)

- Update README.

## Requirments
### Create a Virtual Enviroment
```bash
py -m venv venv
```

### Install Dependencies
```bash
py -m pip install -r requirements.txt
```

### Create an app (Spotify API) 
Please follow the directions at [Create an app](https://developer.spotify.com/documentation/web-api/tutorials/getting-started#create-an-app) and generate a `CLIENT_ID` and a `CLIENT_SECRET`.

### Create the .env file
Create an `.env` file and put them inside in the following format:

```.env
CLIENT_ID     = blahblahblah
CLIENT_SECRET = blahblahblah
```

## Start
### Activate it the Virtual Enviroment
```bash
.\venv\Scripts\activate
```

### Run the script
```bash
py .\main.py
```
