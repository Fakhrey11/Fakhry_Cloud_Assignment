FROM jupyter/base-notebook

USER root

COPY ./ /home/jovyan/work/

RUN chown -R jovyan:users /home/jovyan/work/

USER jovyan

CMD ["start-notebook.sh", "--NotebookApp.token=''", "--NotebookApp.password=''"]
