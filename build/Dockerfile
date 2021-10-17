FROM maven:3.8.3-openjdk-8
RUN git clone https://github.com/shephertz/App42PaaS-Java-MySQL-Sample.git /source
VOLUME [ "/source/target" ]
CMD ["mvn", "-f", "/source", "package"]