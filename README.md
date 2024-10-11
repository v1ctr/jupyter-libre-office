# Dockerized JupyterLab with LibreOffice installed

## Build Image

```
docker build  -t jupyter-libre-office .
```

## Run Image

```
docker run -p "8888:8888" -v ./work:/home/jovyan/work jupyter-libre-office
```
