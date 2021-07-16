FROM jupyter/scipy-notebook

ADD requirements.txt /requirements.txt
RUN pip install -r /requirements.txt

RUN jupyter lab build
CMD jupyter lab --ip=0.0.0.0 --allow-root --no-browser --NotebookApp.token='' --NotebookApp.iopub_data_rate_limit=1e10 \
    --notebook-dir=/home/jovyan/work