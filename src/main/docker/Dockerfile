FROM registry.cn-hangzhou.aliyuncs.com/choerodon-tools/javabase:0.5.0
COPY app.jar /file-service.jar
ENTRYPOINT exec java $JAVA_OPTS  -jar /file-service.jar
