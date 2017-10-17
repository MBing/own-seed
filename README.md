# Own seed project with Node and Angular + Dockerfile (WIP)

### Run Commands
Install dependencies and run watcher
```
    $ yarn install
    $ yarn build
        # open other terminal window/tab
    $ yarn start  
``` 

Extra for Production:
```
    $ yarn build:prod
```

### Docker Commands
Start up a docker container with node.
```
    $ docker build -t own-seed
    $ docker run -it --name whatever-name own-seed
    > |
```

### Future updates
    - Create container to serve instance of angular-node seed
    - Add MongoDB to have a MEAN app
    - ...
    