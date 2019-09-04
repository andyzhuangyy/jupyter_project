# jupyter_project


## start jupyter notebook

run these command

    cd $project    
    pyspark
    ## or
    jupyter notebook
    
## .bashrc or .zshrc

    # spark
    export SPARK_HOME=/Users/andyzhuang/usr/local/spark
    export PATH=$SPARK_HOME/bin:$PATH
    # pyspark: not use cli python, use jupyter notebook
    export PYSPARK_DRIVER_PYTHON=jupyter
    export PYSPARK_DRIVER_PYTHON_OPTS='notebook'


## Reference

* [get-started-pyspark-jupyter-guide](https://blog.sicara.com/get-started-pyspark-jupyter-guide-tutorial-ae2fe84f594f)


