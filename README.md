docker run -it --rm --network host -v C:\Users\josep\projects\educba\pysparks\spark:/home/spark -v C:\Users\josep\projects\educba\pysparks\workdir:/opt/spark/work-dir spark:python3 bash
export PATH=$PATH:/home/spark/.local/bin
pip install mysql-connector-python
pip install pandas
pip install numpy
/opt/spark/bin/pyspark --jars /opt/spark/work-dir/mysql-connector-j-9.0.0.jar


https://spark.apache.org/docs/latest/api/python/getting_started/quickstart_df.html
