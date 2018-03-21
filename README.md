# srvmanager
   > graceful shutdown
   > manager process via pidfile
   > log something easier

## Examples
   1. Via https://github.com/gin-gonic/gin :
   > 

## Usage
```
Usage of ./main/bin/calculate-service:
  -accesslog string
    	log file (default "/var/log/calculate-service_access.log")
  -errorlog string
    	log file (default "/var/log/calculate-service_error.log")
  -pid string
    	pid file (default "/var/run/calculate-service.pid")
  -p string
    	Listen port (default "8080")
  -s string
    	Send a signal to the process.  The argument signal can be one of: start stop reload restart,
    	The following table shows the corresponding system signals:
    	stop	SIGTERM
    	reload	SIGHUP
    	restart	SIGHUP
    	 (default "start")
```
