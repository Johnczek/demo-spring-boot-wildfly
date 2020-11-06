# Demo Spring boot app on WildFly docker container with debug enabled

To build image, run `docker build --tag=app .`

To run container type `docker run -p 8080:8080 -p 9990:9990 -p 8787:8787 -it app /opt/jboss/wildfly/bin/standalone.sh -b 0.0.0.0 -bmanagement 0.0.0.0 --debug`