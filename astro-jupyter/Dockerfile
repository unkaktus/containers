FROM python:3.10
RUN pip install astropy h5py scipy jupyterlab
EXPOSE 8888
ENTRYPOINT [ "jupyter-lab", "--ServerApp.token='astro'", "--no-browser", "--allow-root"]