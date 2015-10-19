Fuse WAR Project
========================

This project includes a sample route as as a WAR.
You can build the WAR by running

    mvn install

You can then run the project by dropping the WAR into your 
favorite web container or just run

    mvn jetty:run

to start up and deploy to Jetty.

If you have JBoss AS running you can deploy using

   mvn jboss-as:deploy

Or to redeploy

    mvn jboss-as:redeploy

For more help see the Apache Camel documentation

    http://camel.apache.org/
    
    
    features:addurl mvn:com.github/fuse-web-swagger-ui/1.0.0/xml/features
	features:install fuse-web-swagger-ui

	install war:file:///root/.m2/repository/com/github/fuse-web-swagger-ui/1.0.0/fuse-web-swagger-ui-1.0.0.war?Web-ContextPath=swagger-ui
