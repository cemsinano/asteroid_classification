## Asteroid Classification

__Cem Sinan Ozturk__

_October 6, 2020_

In this project, I am going to perform a prediction analysis for classifying hazardous asteroids.

### Running the Analysis on Docker

Docker image for the project can be found at https://hub.docker.com/r/cemsinan/asteroid_classification/ .

To access the analysis from your current directory, please run following command:

`docker run -p 8888:8888 cemsinan/asteroid_classification`

After running the docker command, please navigate to the `localhost:8888/?token=<token-value-on-terminal>` into your web browser.


### Dependencies:
It is performed on Python3.8 via JupiterNotebook.

- pandas == 1.0.5
- numpy == 1.19.1
- xgboost == 1.2.0
- sklearn == 0.22.1
- lightgbm == 3.0.0
- seaborn == 0.11.0
