# calorieking-database-troubleshoot

## if you want to increase the size of the volume mount
## 1. remove the balast file from the mount
## 2. There is no docker-compose file. All docker containers are running as a deamon.
## 3. deamon services are found here - https://bitbucket.org/calorieking/ck-infrastructure/src/master/services-server/cloud-init-primary.yaml
## 4. first step is to increase the volume size from gcp console. next run commands on the vm to increase the volume size.
## 5. To run volume increase commands we must switch to root user. Notmal user does not has access to run those commands.
## 6. 
