FROM jupyter/datascience-notebook:lab-2.2.9

USER root
RUN pip install -U pip

RUN mkdir /home/jovyan/notebooks
RUN chown jovyan:users /home/jovyan/notebooks

RUN pip install google-cloud==0.34.0
RUN pip install google-cloud-bigquery==1.18.0
RUN pip install google-cloud-storage==1.20.0
# RUN pip install pyarrow
RUN pip install pydata-google-auth

USER jovyan
WORKDIR /home/jovyan