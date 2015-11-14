# ELK

ELK v2

## Usage
```sh
$ docker-compose up
```
> You need to configure volumes in `docker-compose.yml`

## Listened ports
- `5140` for Nginx
- `5141` for pfSense

## Testing
```sh
$ nc localhost 5140 < /path/to/logfile.log
```
