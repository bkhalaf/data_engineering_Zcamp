# data_engineering_Zcamp
The repo contains all my works done during the data engineering zoomcamp with 4 talented and experienced data engineers.

The topics included :

### Docker + Postgres

[Code](2_docker_sql)

* [Introduction to Docker](https://www.youtube.com/watch?v=EYNwNlOrpr0&list=PL3MmuxUbc_hJed7dXYoJw8DoCuVHhGEQb)
  * Why do we need Docker
  * Creating a simple "data pipeline" in Docker
* [Ingesting NY Taxi Data to Postgres](https://www.youtube.com/watch?v=2JM-ziJt0WI&list=PL3MmuxUbc_hJed7dXYoJw8DoCuVHhGEQb)
  * Running Posgtres locally with Docker
  * Exploring the NY Taxi dataset
  * Ingesting the data to the database
* [Connecting pgAdmin and Postgres](https://www.youtube.com/watch?v=hCAIVe9N0ow&list=PL3MmuxUbc_hJed7dXYoJw8DoCuVHhGEQb)
  * The pgAdmin tool
  * Docker networks
* [Putting the ingestion script to Docker](https://www.youtube.com/watch?v=B1WwATwf-vY&list=PL3MmuxUbc_hJed7dXYoJw8DoCuVHhGEQb)
  * Converting the Jupyter notebook to a Python script
  * Parametrizing the script with argparse
  * Dockerizing the ingestion script
* [Running Postgres and pgAdmin with Docker-Compose](https://www.youtube.com/watch?v=hKI6PkPhpa0&list=PL3MmuxUbc_hJed7dXYoJw8DoCuVHhGEQb)
  * Why do we need Docker-compose
  * Docker-compose YAML file
  * Running multiple containers with `docker-compose up`
* [SQL refreshser](https://www.youtube.com/watch?v=QEcps_iskgg&list=PL3MmuxUbc_hJed7dXYoJw8DoCuVHhGEQb)
  * Adding the Zones table
  * Inner joins
  * Basic data quality checks
  * Left, Right and Outer joins
  * Group by


### GCP + Terraform

[Code](1_terraform_gcp)

* Introduction to GCP (Google Cloud Platform)
  * [Video](https://www.youtube.com/watch?v=18jIzE41fJ4&list=PL3MmuxUbc_hJed7dXYoJw8DoCuVHhGEQb)
* Introduction to Terraform Concepts & GCP Pre-Requisites
  * [Video](https://www.youtube.com/watch?v=Hajwnmj0xfQ&list=PL3MmuxUbc_hJed7dXYoJw8DoCuVHhGEQb)
  * [Companion Notes](1_terraform_gcp)
* Workshop: Creating GCP Infrastructure with Terraform
  * [Video](https://www.youtube.com/watch?v=dNkEgO-CExg&list=PL3MmuxUbc_hJed7dXYoJw8DoCuVHhGEQb)
  * [Workshop](1_terraform_gcp/terraform)
* Configuring terraform and GCP SDK on Windows
  * [Instructions](1_terraform_gcp/windows.md)


### Environment setup 

For the course you'll need:

* Python 3 (e.g. installed with Anaconda)
* Google Cloud SDK
* Docker with docker-compose
* Terraform

If you have problems setting up the env, you can check this video:

* [Setting up the environment on cloud VM](https://www.youtube.com/watch?v=ae-CV2KfoN0&list=PL3MmuxUbc_hJed7dXYoJw8DoCuVHhGEQb)
  * Generating SSH keys
  * Creating a virtual machine on GCP
  * Connecting to the VM with SSH
  * Installing Anaconda
  * Installing Docker
  * Creating SSH `config` file
  * Accessing the remote machine with VS Code and SSH remote
  * Installing docker-compose
  * Installing pgcli
  * Port-forwarding with VS code: connecting to pgAdmin and Jupyter from the local computer
  * Installing terraform
  * Using `sftp` for putting the credentials to the remote machine
  * Shutting down and removing the instance
