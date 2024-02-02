To view the Jupyter notebooks, use the [Jetbrains Big Data Tools](https://www.jetbrains.com/help/idea/jupyter-notebook-support.html), GitHub viewer, or run the container:
```shell
docker run -it -p 6660:8888 -v "${PWD}":/home/jovyan jupyter/pyspark-notebook start.sh jupyter notebook --NotebookApp.token=''
```

  * http://localhost:6660