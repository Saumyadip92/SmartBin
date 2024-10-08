### Login Credentials
```
Username: admin
Password: pass
```

## API Calls
### Send Garbage Data
```
URL: https://smartbin.pythonanywhere.com/add_garbage_data/
allowed method: [POST, GET]
parametes required: ["bin_id", "garbage_level", "moisture_status"]

POST JSON Example:
{
    "bin_id": 2,
    "garbage_level": 80,
    "moisture_status": true
}
```

### Get Garbage Data
```
URL: https://smartbin.pythonanywhere.com/get_garbage_data/
allowed method: [GET]
parametes required: ["bin_id"]

Example:
https://smartbin.pythonanywhere.com/get_garbage_data/?bin_id=2
```

## Local Setup
### Install dependency
```
pip install -r requirements.txt
```
### Run Server
```
python manage.py runserver
```

## Outputs
### User Login
![image](https://user-images.githubusercontent.com/42216008/196500983-1c4602f7-0400-4aff-82b7-6b79360f35e7.png)


### Bin DashBoard
![image](https://user-images.githubusercontent.com/42216008/196501095-812807b4-8c86-454c-aaea-679c75b4c282.png)


### Add/Update a Bin Details
![image](https://user-images.githubusercontent.com/42216008/196501211-23a78e39-24f6-43a7-a7ff-dfcfd6ec458c.png)


### Bin Details
![image](https://user-images.githubusercontent.com/42216008/196501361-b070a30b-c3f7-46b6-b674-4a1dd87ff0c5.png)
