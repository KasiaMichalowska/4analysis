FROM jboss/wildfly:latest

ADD config /opt/jboss/wildfly/config/

COPY target/ROOT.war /opt/jboss/wildfly/config/

CMD ["/opt/jboss/wildfly/config/execute.sh"]