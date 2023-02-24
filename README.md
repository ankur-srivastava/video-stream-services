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
    <!-- http://localhost:4002/video?path=SampleVideo_1280x720_1mb.mp4 -->
    http://localhost:4002/video?id=5d9e690ad76fe06a3d7ae416

### MongoDB

    connect to - localhost:4000
    
    create a new database called video-streaming, create a collection called videos, and then insert a document into that collection. For our purposes, use the content from this listing.
