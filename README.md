![status: inactive](https://img.shields.io/badge/status-inactive-red.svg)

This project is no longer actively developed or maintained.

For new work on this check out these repos [getting-started-java](https://github.com/GoogleCloudPlatform/getting-started-java) and [java-docs-samples](https://github.com/GoogleCloudPlatform/java-docs-samples).

Weld Numberguess Example
========================

This example demonstrates the use of Weld in a Servlet container in App Engine Managed VMs. 
This is an adaptation of <https://github.com/weld/core/tree/master/examples/jsf/numberguess>

Run  with Google App Engine Managed VMs (Assuming you have installed the Cloud SDK)
--------------------

        mvn gcloud:run

Now you can view the application at <http://localhost:8080>.

The Jetty specific configurations can be seen under [src/main/webapp/WEB-INF/jetty-context.xml](src/main/webapp/WEB-INF/jetty-context.xml)
 and [src/main/webapp/WEB-INF/jetty-env.xml](src/main/webapp/WEB-INF/jetty-env.xml).
