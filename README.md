# Music-Tag-Fixer
This project uses Spotify API to get data for a music track by its artist name and title.

## Requirments
### Create a Virtual Enviroment and Activate it
```bash
py -m venv venv
.\venv\Scripts\activate
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

## Run the script
```bash
py .\main.py
```
