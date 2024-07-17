# AIRFLOW EXPERIMENTS 
This repo contains various Airflow configurations for the purpose of learning the tool

### AIRFLOW BASIC INFO 
![image](https://github.com/user-attachments/assets/8b9b2a69-1d05-4765-82d9-5f27e9d6077a)

COMPONENTS 
- Webserver - graphical user interface to inspect, trigger, and debug dags and tasks. available on localhost8080
- Scheduler - schedules jobs. Triggers and schedules workflows. Submits tasks to the executor to run. Monitors all tasks and dags and then triggers tasks instances once their dependencies are complete
- Worker - component that executes the tasks assigned by the scheduler
- Metadata DB - backend to airflow. Used by the Scheduler, Executer and Webserver to store the status of the tasks
- OPTIONAL COMPONENTS
  - Reddis service - message broker that for frowards messages from the scheduler to worker
  - Flower App - for monitoring the workers available on localhost: 5555
  




