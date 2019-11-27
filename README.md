# Data management in large-scale distributed systems
Many students had some problems to install Spark and Jupyter Notebook to use it in the laboratory for the course 
data management in large-scale distributed systems.
In order to avoid these problems I decided to use Docker and create a configuration file for easy deployment.
Finally this repository contains the exercises and the solutions that I got so you can compare with yours.

## Data
GitHub limits the files to 100MB. You need to download the datasets and put it in the data folder.
The dataset that we used were:

- [Laboratory-1](https://filesender.renater.fr/?s=download&token=83e84215-b3df-a411-8a7c-05894c2acdfb) 


## Pre-requisites
- [Docker](https://www.docker.com/) 
- [Docker-compose](https://docs.docker.com/compose/)


## Instalation and usage
Clone the repository and use docker compose to run the containers with the image of the Spark and Jupyter Notebook.
```bash
git clone https://github.com/alvarogonjim/DMLSDS.git
cd DMLSDS/
docker-compose up
```

### WARNING! 

The output in the terminal will be the URL of the notebook some users had problems to connect to the notebook using the format http://127.0.0.1:8888/?token=... **you have to replace 127.0.0.1 by localhost** like that:
http://localhost:8888/?token=...


## Contributing
Pull requests are welcome. If you have different solutions, please open an issue first to discuss what you would like to change.

## License
[MIT](https://choosealicense.com/licenses/mit/)
