## Database dumper

### To Install Dumper (docker image: giustech/database-dumper)
    make generate-docker-dumper
    
### To Install Restore (docker image: giustech/database-restore)
    make generate-docker-restore
    this image needs to execute only in empty databases to restore dump

### Available Dialects
    - postgres
