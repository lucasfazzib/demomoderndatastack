# demo-modern-data-stack

Tasks: 

- Repository to store Pipeline stores using Modern Data Stack with AirByte + DBT + Airflow + SnowFlake + Metabase

- Create SnowFlake account

- Create DBT account

- Build the Pipeline environment $ ./setup.sh up

- Copy the airbyte connection id in the terminal to finish installing the environment and create a dag in the airflow

- Enter Airbyte on port 8000

- Set connection to google spreadsheet using credentials and spreadsheet id

- Set connection to Big Query using credentials and project id and dataset id

- Manual Sync and Data Overwrite

- Configures or changes the Transfomation pointed to the dbt github 

- Comes back with no airflow and starts the dag trigger_airbyte_dbt_job

- Check in Airbyte if Sync is running

Check in SnowFlake if you uploaded the dataset correctly

- Metabase climbs on port 3000

- Airflow goes up on port 8080

Key Files:

docker-compose-airflow.yaml
docker-compose-airbyte.yaml
setup.sh
dags/dag_airbyte_dbt.py
