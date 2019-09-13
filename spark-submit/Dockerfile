FROM spark-base:2.4.4

COPY spark-submit.sh /

ENV SPARK_MASTER_URL="spark://spark-master:7077"
ENV SPARK_SUBMIT_ARGS=""
ENV SPARK_APPLICATION_ARGS ""
#ENV SPARK_APPLICATION_JAR_LOCATION app.jar
#ENV SPARK_APPLICATION_MAIN_CLASS my.main.Application
ENV SPARK_CORES="1"

CMD ["/bin/bash", "/spark-submit.sh"]