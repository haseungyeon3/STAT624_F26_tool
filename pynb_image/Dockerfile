FROM python:3.11.7-slim
LABEL version="pyn1.4"
LABEL description="Python Jupyter notebook development environment"

RUN apt-get update -y
RUN apt-get install -y gcc
RUN apt-get install -y build-essential libpq-dev
RUN apt-get update
RUN apt-get install -y graphviz
RUN apt-get install -y xdg-utils
RUN pip install --upgrade pip
RUN pip install numpy==1.26.3  pandas==2.2.0 seaborn==0.13.2 jupyter==1.0.0 scikit-learn==1.4.0 SQLAlchemy==2.0.36 psycopg2==2.9.9 statsmodels==0.14.1 dask[complete]==2024.10.0 dask-ml==2024.4.4 graphviz==0.20.3

WORKDIR /home/notebooks/

CMD jupyter notebook --no-browser --allow-root --ip 0.0.0.0
