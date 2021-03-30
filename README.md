# Urban open platform MQTT bridge

Listen certain data streams and publish messages in a MQTT topic in SensorThings format   


## Development

Rename `.env.dev-sample` to `.env.dev`.

If you want to run python app locally (not in Docker container),
you can activate environment variables running this command:  
`export $(xargs < .env.dev)`


### Python 

Run first  
`docker-compose up -d --build`  
and then  
`docker-compose up`
and you should see output like this:
```
$ docker-compose up 
Starting fvhstandardtemplate_python_1 ... done
Attaching to fvhstandardtemplate_python_1
python_1  | Hello 0 times!
python_1  | Hello 1 times!
python_1  | Hello 2 times!
python_1  | Hello 3 times!
python_1  | Hello 4 times!
fvhstandardtemplate_python_1 exited with code 0
```
