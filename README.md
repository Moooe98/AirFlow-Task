This repository contains a Docker Compose configuration to set up a complete Airflow Environment using Celery Executor. The environment includes the following components:
- Airflow Webserver: The user interface to monitor, schedule, and manage workflows.
- Airflow Scheduler: Handles the scheduling of workflows and triggers tasks as per the defined schedule.
- Celery Executor: Distributes the execution of tasks across multiple workers.
- 3 Workers: Responsible for executing the tasks assigned by the Celery Executor.
