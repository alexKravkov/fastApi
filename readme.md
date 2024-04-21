

#### Install Requirements ####
```commandline
pip install -r requirements.txt
```

#### Run the server ####
I use port number 8005 but you can change it to anything you like. Just make sure its not being used by anything else.
```commandline
uvicorn main:app --port 8005 --reload
```


#### To test the server API, use *test_main.http* or go to [http://127.0.0.1:8005/docs]() ####
