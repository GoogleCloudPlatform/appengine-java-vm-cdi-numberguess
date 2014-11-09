Weld Numberguess Example
========================

This example demonstrates the use of Weld in a Servlet container in App Engine Managed VMs. 
This is an adaption from <https://github.com/weld/core/tree/master/examples/jsf/numberguess>

Run  with Google App Engine Managed VMs
--------------------

        mvn appengine:gcloud_app_run

Now you can view the application at <http://localhost:8080>.

The Jetty specific configurations can be seen under <src/main/webapp/WEB-INF/jetty-context.xml>
 and <src/main/webapp/WEB-INF/jetty-env.xml>