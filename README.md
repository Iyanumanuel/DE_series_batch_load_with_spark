# DE_series_batch_load_with_spark

## Add to .bashrc file
export JAVA_HOME="$HOME/spark/jdk-11.0.2"
export SPARK_HOME="$HOME/spark/spark-3.0.3-bin-hadoop3.2"
export PYTHONPATH=$SPARK_HOME/python:$PYTHONPATH
export PYSPARK_DRIVER_PYTHON="jupyter"
export PYSPARK_DRIVER_PYTHON_OPTS="notebook"
export PYSPARK_PYTHON=python3
export PATH=$SPARK_HOME/bin:$PATH:~/.local/bin:$JAVA_HOME/bin:$JAVA_HOME/jre/bin

export PYTHONPATH="${SPARK_HOME}/python/:$PYTHONPATH"
export PYTHONPATH="${SPARK_HOME}/python/lib/py4j-0.10.9-src.zip:$PYTHONPATH"

## Links
https://medium.datadriveninvestor.com/how-to-install-the-jupyter-notebook-server-on-linux-b2c14c47b446
https://dlcdn.apache.org/spark/spark-3.1.3/spark-3.1.3-bin-hadoop3.2.tgz
https://opensource.com/article/18/11/pyspark-jupyter-notebook

## copy files from local computer to remote server
scp /mnt/c/Users/RoyaltyBook/Downloads/spark-3.0.3-bin-hadoop3.2.tgz  iyanumanuel@66.94.120.221:/home/iyanumanuel/spark


## add port 4040 to forwarded port to access Spark UI
