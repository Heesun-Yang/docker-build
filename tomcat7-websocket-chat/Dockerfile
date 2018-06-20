FROM rockplace/tomcat7-s2i-openshift:7.0.82
EXPOSE 8080 8888

RUN chmod -R g+wrx $CATALINA_HOME/
COPY websocket-chat.war $CATALINA_HOME/webapps/
