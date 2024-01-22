To view the Jupyter notebooks, use the JetBrains IDE, GitHub viewer, or run the container:
```shell
docker run -it -p 6660:8888 -v "${PWD}":/home/jovyan jupyter/pyspark-notebook start.sh jupyter notebook --NotebookApp.token=''
```

  * http://localhost:6660