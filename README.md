# video-stream-services

Set of microservices

To boot the video service and other commands

    docker-compose up --build
    docker-compose stop
    docker-compose ps

### ENV

    export PORT=4002
    export STORAGE_ACCOUNT_NAME=videosstorage
    export STORAGE_ACCESS_KEY=

### Test

    npm start
    http://localhost:4002/video?path=SampleVideo_1280x720_1mb.mp4
