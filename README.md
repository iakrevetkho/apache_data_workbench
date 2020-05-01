# apache_data_workbench
Open source Data Warehouse + Data Science Workbench on Apache Open Source components

## Init

1. `git submodule update --init  --recursive`
2.  Create folder for jupyterlab: `mkdir jupyterlab; chmod 777 jupyterlab`
3.  Create folder for jupyterlab: `mkdir -p druid; chmod 777 druid`

## Run

1. Remove previous containers: `docker-compose down --remove-orphans`
2. Run all containers: `docker-compose up -d`