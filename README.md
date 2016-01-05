# pipeline-microservice-server-conf

## Daemonizing the application

The [pipelines-microservice](https://github.com/InSilicoDB/pipelines-microservice) can be runned as a daemon using `start-stop-daemon` program from debian/ubuntu machines.

To do use this program place the TODO file in the `/etc/init.d` folder of the host. When this is done you should be able to:

1. Start the daemon:`sudo service TODO FILENAME start`

2. Stop the daemon: `sudo service TODO FILENAME stop`

3. Check if the daemon is running: `sudo service TODO FILENAME status`
